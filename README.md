# Работа с GIT и файлами формата .md

### <font color="#1589F0">Работа с GIT</font>
#### <font color="green">Преднастройка GIT</font>

* git *config* --global user.name **"your_name"** - первоначальная аутентификация (имя)
* git *config* --global user.email **"your_email"** - первоначальная аутентификация (эл. почта)

#### <font color="green">Основные команды GIT</font>
* git *init* - инициализация локального репозитория
* git *add* **file_name** - добавить файл (файлы) к следующему коммиту
* git *status* - получить информацию от git о его текущем состоянии
* git *commit* -m **"message"** - создание коммита
* git *log* - вывод на экран истории всех коммитов с их хэш-кодами (можно использовать с флагами *--all* / *--oneline* для большего удобства)
* git *checkout* **commit_id** - переход от одного коммита к другому
* git *checkout* **branch_name** - переход на ветку branch_name
* git *chechout* **master** (или *main*) - вернуться к актуальному состоянию и продолжить работу
* git *diff* - показать разницу между текущим файлом и закоммиченным файлом
* git *merge* **branch_name** - влить ветку branch_name в текущую ветку
