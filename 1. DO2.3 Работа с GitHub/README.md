1. Основы работы с СКВ в графическом режиме
Цель работы
Познакомиться на практике с основными приемами работы в современных системах контроля версий.
Задания для выполнения
1.	Установить на компьютер графический клиент Git.
 ![image](https://user-images.githubusercontent.com/80482468/137908742-5270e5d9-1dca-4079-974b-43750a4b0a35.png)
2.	Создайте в своей домашней папке (или в любой другой на ваш выбор) каталог, который будет содержать файлы нового программного проекта.
 ![image](https://user-images.githubusercontent.com/80482468/137908903-5eda98dd-82ed-416b-bc00-17c5a744b55a.png)
3.	Выберите тематику программы, которую собираетесь написать. Язык программирования и используемые инструменты разработки сейчас не важны.
4.	Инициализируйте в этой директории репозиторий гит.![image](https://user-images.githubusercontent.com/80482468/137908968-7c9eb461-f4c8-493d-9744-3f2ba500573d.png)

5.	Обратите внимание на появление в этой папке скрытой подпапки с названием .git. Если вы ее не видите, то скорее всего, у вас отключено отображение скрытых папок.
 
6.	Создайте новый файл для исходного текста программы. Если вы используете программный фреймворк, инициализируйте его в рабочий каталог.
7.	Напишите несколько строк вашей программы.
8.	Добавьте файл с исходным текстом (несколько файлов, если необходимо) в индекс вашего репозитория.![image](https://user-images.githubusercontent.com/80482468/137909045-bb6efd98-7b05-42c4-be5d-ea879b135b1d.png)

 
9.	Совершите ваш первый коммит. Напишите осмысленное сообщение коммита.![image](https://user-images.githubusercontent.com/80482468/137909063-958eb836-1bf9-4ee9-bc7c-90be2ff42b10.png)

 
10.	Повторите несколько раз. Каждый раз, завершая определенный этап работы, выполняйте коммит и описывайте проделанные изменения в сообщении коммита.  ![image](https://user-images.githubusercontent.com/80482468/137909077-f8e0793e-1563-430d-bf53-a87fdeb5f09d.png)

11.	Просмотрите историю коммитов. Попробуйте перейти на один из прошлых коммитов. Вернитесь в актуальное состояние программы.![image](https://user-images.githubusercontent.com/80482468/137909100-e25ac5e2-3789-465a-8719-3602e6a9a8a1.png)
![image](https://user-images.githubusercontent.com/80482468/137909106-b091089a-ac48-407c-8556-b664e8619244.png)

  
Методические указания
Для выполнения лабораторной работы необходимо воспользоваться любым консольным клиентом системы контроля версий Git, подходящую для рабочей операционной системы. Для Windows подойдет, например, дистрибутив git-scm. Этот же пакет включает в себя и консольную утилиту git, необходимую для выполнения следующих работ. Для Linux существует, например, пакет Git Cola.
Для написания сообщений коммита необходимо придерживаться следующего общепринятого правила: в первой строке сообщения следует кратко описать произведенные изменения; если необходимо подробное описание, состоящее из многих строк, то его приводят, отступив от первой строки одну пустую. Помните, что заголовок описания коммита - это то, что будете видеть вы и ваши коллеги в истории изменений проекта.
Контрольные вопросы
1.	Опишите своими словами значение следующих терминов:
1.	рабочий каталог
Каталог, в котором ведется отслеживание файлов
2.	репозиторий
виртуальное хранилище всех данных(файлов) проекта
3.	коммит
сохранение текущего состояния всех файлов
4.	ветка
указатель на переход к определенному состоянию сохранения файлов
2.	Ознакомьтесь с гайдом по выбранной вами программе-клиенту Git.
Дополнительные задания
1.	Представьте, что вы начинаете большой раздел работы. Для изоляции изменений создайте новую ветку. Назовите ее, чтобы было понятно, что вы в ней будете делать.![image](https://user-images.githubusercontent.com/80482468/137909159-8612b72c-4233-4b4f-ab8e-3cab19bdb73e.png)

 
2.	Перейдите в новую ветку и сделайте несколько коммитов.![image](https://user-images.githubusercontent.com/80482468/137909163-9fe4a1fa-4003-455b-b11b-ef46bfb61ac1.png)

 
3.	Перейдите в основную ветку и обратите внимание на состояние рабочей директории.![image](https://user-images.githubusercontent.com/80482468/137909172-da3ce209-c497-4dcd-8f23-b6eb4cc64c24.png)

 
Стала как до образования новой ветки и перехода в неё
4.	Создайте еще одну ветку для работы над другим направлением в вашей программе. Обычно так работают в команде, каждый участник в собственной ветке. Либо в ветках может идти параллельная работа над разными возможностями программы. В таком случае эти ветки называются тематическими.![image](https://user-images.githubusercontent.com/80482468/137909186-a2bbe2f9-86e5-4935-99d6-58c80a880e94.png)

 
5.	Сделайте несколько коммитов во вновь созданную ветку.![image](https://user-images.githubusercontent.com/80482468/137909194-d2f9969c-dc1d-4a3a-a86e-2789e626d1a0.png)

 
6.	Перейдите в основную ветку и слейте в нее первую тематическую ветку.![image](https://user-images.githubusercontent.com/80482468/137909202-965278c7-9b97-43af-9dbe-85c09183a603.png)

 
7.	Слейте в основную ветку вторую тематическую. Если возникли конфликты слияния, разрешите их и завершите слияние.
8.	Удалите более не нужные тематические ветки. Обратите внимание в истории, что даже при удалении веток никакие коммиты не теряются.
2. Работа с Git в терминале
Цель работы
На основе уже полученных знаний о принципах работы СКВ получить более глубокое представление о работе Git при помощи команд терминала.
Задания для выполнения
1.	Выберите тематику программы, которую собираетесь написать. Создайте для нее рабочую директорию
2.	Инициализируйте в рабочей директории репозиторий при помощи команды git init.![image](https://user-images.githubusercontent.com/80482468/137909214-96b40372-3b93-4969-8b80-e24f0ed1e592.png)

 
3.	Выполните в репозитории команду git status. Проинтерпретируйте полученное сообщение.![image](https://user-images.githubusercontent.com/80482468/137909228-f6b751cb-c7ec-4478-89d7-1efcb8435e48.png)

 
4.	Создайте файл для исходного текста программы. Выполните команду git status.![image](https://user-images.githubusercontent.com/80482468/137909236-8e5760c5-19e6-46ca-8b6f-92df9373256c.png)

 
5.	Добавьте созданный файл под версионный контроль при помощи команды git add. Еще раз выполните git status.![image](https://user-images.githubusercontent.com/80482468/137909257-69e50bec-8e10-46ee-a79a-8ca1af6ad1d1.png)

 
6.	Сделайте начальный коммит при помощи команды git commit с опцией -m.![image](https://user-images.githubusercontent.com/80482468/137909265-c34335f0-5927-4337-80dd-89389fa4c0ec.png)

 
7.	Сделайте еще несколько коммитов. Выполните команду git log для просмотра истории коммитов.![image](https://user-images.githubusercontent.com/80482468/137909271-8e256a4a-79e0-45c6-974e-a03ebe68e6df.png)

 
8.	Сделайте так, чтобы при коммите измененные файлы автоматически добавлялись в коммит.
“git commit -a”
9.	Добавьте еще несколько файлов с исходным текстом программы.![image](https://user-images.githubusercontent.com/80482468/137909283-bb11fd87-8a71-4901-9376-ec0ff2c46033.png)

 
10.	Добавьте все новые файлы под версионный контроль одной командой.![image](https://user-images.githubusercontent.com/80482468/137909294-bbb30c95-cce3-4cfa-a13e-87b187f01f50.png)

 
11.	На всех стадиях работы пользуйтесь командой git status.

12.	Инициализируйте в рабочей директории виртуальное окружение (Если вы пишите не на Python, то можете инициализировать какой-либо программный фреймворк, либо начать работать в IDE, которая создает скрытую папку с настройками в рабочем каталоге).
13.	Добавьте созданную служебную папку в файл .gitignore. Проверьте, что они не добавляются в репозитории при добавлении новых файлов с исходным кодом.
14.	Создайте новую тематическую ветку git branch. Перейдите в нее с помощью git checkout. Выведите на экран список всех веток.![image](https://user-images.githubusercontent.com/80482468/137909302-a5f1b18a-6deb-4604-91d1-d2c680ab0efd.png)

 
15.	Сделайте несколько коммитов в основную и тематическую ветки.![image](https://user-images.githubusercontent.com/80482468/137909312-c3a39ad6-871e-4785-b42a-f636967769cc.png)

 
16.	Слейте изменения в основную ветку с помощью git merge. Если произошел конфликт слияния, разрешите его и завершите слияние с помощью git commit.![image](https://user-images.githubusercontent.com/80482468/137909318-78c61cf7-5bd4-41ea-b8cb-78f1c062fd45.png)

 
17.	При получении в процессе разработки программы в стабильно работающем состоянии, слейте это состояние в основную ветку и добавьте к коммиту слияния пометку с номером релиза.
Методические указания
Для работы в терминале изучите шпаргалки по основным командам git.
#apt install git
Главные команды, которые вам понадобятся это:
#git config --global init.defaultBranch PROJECTNAME
git init - создает репозиторий системы контроля версий в данной директории;
git add - добавляет указанный файл под версионный контроль;
git add . - добавляет все файлы текущей директории под версионный контроль;
git status - показывает состояние рабочей директории по сравнению с последним сохраненным состоянием:
git commit -m "(message)" - сохраняет текущее состояние рабочей директории как новое состояние (создает новый коммит); новый коммит получает сообщение, переданное как параметр;
git commit -am "(message)" - создает новый коммит и автоматически включает в него все изменившиеся отслеживаемые файлы;
git log - выводит историю коммитов репозитория;
git branch - показывает список веток репозитория;
git branch - создает новую ветку на основе текущего состояния с переданным названием;
git checkout -b - создает новую ветку и автоматически делает ее текущей;
git merge - сливает изменения, сделанные в ветке с переданным названием в текущую;
git branch -d - удаляет ветку с переданным названием;
git clone (repo URL) - клонирует удаленный репозиторий, находящийся по переданному адресу в текущую директорию; доступ обычно осуществляется по протоколам HTTP либо SSH;
Например https://github.com/pvkrotkov/0_git_basics
git fetch - считывает изменения в удаленном репозитории, отсутствующие в локальной копии;
git pull - считывает новые изменения в удаленном репозитории и сливает их в соответствующие локальные ветки;
git push –all - отправляет изменения, сделанные в локальном репозитории в удаленный;
Контрольные вопросы
1.	Что такое удаленный репозиторий?
Удалённые репозитории — это модификации проекта, которые хранятся в интернете или ещё где-то в сети. Их может быть несколько, каждый из которых, как правило, доступен для вас либо только на чтение, либо на чтение и запись.
2.	Где нужно вводить команды git?
В любую консоль /терминал
3.	Для чего нужны ветки в системах контроля веток?
Ветки нужны для того, чтобы программисты могли вести совместную работу над проектом и не мешать друг другу при этом. При создании проекта, Git создает базовую ветку.
4.	Как возникают конфликты слияния
Обычно конфликты возникают, когда два человека изменяют одни и те же строки в файле или один разработчик удаляет файл, который в это время изменяет другой разработчик. В таких случаях Git не может автоматически определить, какое изменение является правильным. Конфликты затрагивают только того разработчика, который выполняет слияние, остальная часть команды о конфликте не знает. Git помечает файл как конфликтующий и останавливает процесс слияния. В этом случае ответственность за разрешение конфликта несут разработчики.
5.	Как разрешать конфликты слияния?
Только сам разработчик вручную, который проводит слияние
Дополнительные задания
1.	Ознакомьтесь с методологией разработки GitFlow.
2.	Установите на свой компьютер инструментальное средство для работы с GitFlow.
3.	Выполните основные задания лабораторной работы с использованием команд git-flow.
3. Работа с удаленными репозиториями и GitHub
Цель работы
Освоить основные навыки работы с облачными и распределенными системами контроля версий, получить навыки работы с инструментальными средствами, обеспечивающими командную работу над разработкой ПО.
Задания для выполнения
1.	Зарегистрироваться на сайте github.com
2.	Установить на компьютере программу Git
3.	Форкнуть данный репозиторий в свой аккаунт![image](https://user-images.githubusercontent.com/80482468/137909366-8ffdf25c-c056-417d-99af-ff7c221597f6.png)

 
4.	Склонировать созданный удаленный репозиторий в директорию ~/git/test![image](https://user-images.githubusercontent.com/80482468/137909374-0fabf310-74fd-446f-a9bf-a731b168a123.png)

 
5.	На локальной машине пишем скрипт ~/git/test/backup.sh, с произвольным содержанием![image](https://user-images.githubusercontent.com/80482468/137909386-601db265-8210-4403-bb91-0d81a32777b3.png)

 
6.	Фиксируем скрипт в репозитории (делаем коммит)![image](https://user-images.githubusercontent.com/80482468/137909392-d32b3af9-c75c-4b0a-b764-9fcb0afe8c6b.png)

 
7.	Обновляем удаленный репозиторий репозиторий (делаем пуш)
8.	Через текстовый редактор добавить любую новую строку с комментарием![image](https://user-images.githubusercontent.com/80482468/137909402-0b874386-ce11-4e57-b45b-28d98ceb4a5d.png)

 
9.	Сделать коммит![image](https://user-images.githubusercontent.com/80482468/137909411-5113ebdd-b6bd-49a8-977a-eb11b52d00ae.png)

 
10.	Вности синтаксическую ошибку в скрипт![image](https://user-images.githubusercontent.com/80482468/137909429-f900402a-6787-4006-97cc-8e0dc5c9ddbb.png)

 
11.	Сделать коммит ошибочного скрипта![image](https://user-images.githubusercontent.com/80482468/137909440-d420d72b-0c86-42a1-b510-e9b4db7f023b.png)

 
12.	Откатываем до последней рабочей версии![image](https://user-images.githubusercontent.com/80482468/137909450-b156ad03-57e8-4de7-9c0a-7810f62875a0.png)

 
13.	Просмотреть историю коммитов![image](https://user-images.githubusercontent.com/80482468/137909460-b9f77f17-c31e-458e-bc2a-494fe48608cb.png)

 
Коммит с ошибочной строкой отсутствует
14.	Добавить несколько коммитов произвольного содержимого![image](https://user-images.githubusercontent.com/80482468/137909468-1d0ffbb9-748b-4fbe-ad4e-1326804f0f7c.png)

 
15.	Создать пулл реквест в данный репозиторий![image](https://user-images.githubusercontent.com/80482468/137909480-82b0c0fd-7345-4392-8ccc-d89e5b1a3d59.png)

 
Контрольные вопросы
1.	Зачем нужен облачный хостинг репозиториев?
Для совместной удалённой работы в сети.
2.	Какими основными функциями обладает сайт github.com?
Создание репозиториев, контроля версий, переносить репозитории на локальную машину с сети.
3.	Как организовать командную работу над открытым проектом?
Каждый должен четко выполнять свою роль, в своих ветках, также при создании какого-то новшества сначала протестировать на новой ветке прежде чем переносить в основную.
Дополнительные задания
1.	Дополнительно оценивается, если студент продемонстрирует работу с ветками в процессе написания более-сложного программного проекта (не менее трех файлов, двух веток, десяти коммитов, как минимум одно объединение).
2.	Дополнительно оценивается демонстрация командной работы. Для этого нужно склонировать репозиторий другому члену команды и коммитить от своего имени. При отправке истории на удаленный сервер (push) на сайте будет отображаться общая история. При скачивании истории с сервера (pull) общая история будет отображаться на локальном компьютере.
3.	Настройте работу с git вашей интегрированной среды разработки по выбору. Для работы с python рекомендуется использовать PyCharm. Выполните задания лабораторной работы в IDE используя встроенные средства работы с системами контроля версий.
