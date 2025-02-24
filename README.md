Born2beroot
Что такое ЛМВ?
LMV (Logical Volume Manager) — это уровень абстракции между устройством хранения данных и файловой системой. Он берет группу физических дисков и создает группу томов, а затем внутри этой группы томов вы создаете логические тома (swap, root, home...).

Главное преимущество использования LMV: гораздо больше гибкости в управлении разделами.
Примечание: Используя LMV, мы можем расширить хранилище любого раздела (с логическим томом).

Физический том (PV): физическое устройство хранения данных. Это может быть жесткий диск, SD-карта и т. д.
Группа томов (VG): чтобы использовать пространство, предоставляемое PV, его необходимо выделить в группу томов.

Логический том (LV): эти устройства мы будем использовать для создания файловых систем, обмена виртуальными машинами и т. д.
Примечание: Если VG — это диск хранения данных, то LV — это разделы, созданные на диске.

Различия между Debian и CentOS:

Debian проще в установке и использовании.
CentOS не так прост в установке.
Debian имеет графический пользовательский интерфейс (GUI ).
CentOS не имеет простого графического интерфейса.
В чем разница между программным обеспечением и операционной системой?

Системное программное обеспечение — это программное обеспечение, которое управляет ресурсами и позволяет пользователю взаимодействовать с системой.
Операционная система действует как интерфейс между пользователем и аппаратным обеспечением компьютера.
Что такое APT (Advanced Package Tool)?

используется для установки всех необходимых зависимостей при установке программы.

Различия между apt и aptitude:

Если вы хотите установить пакеты с помощью apt, то apt, если обнаружит неправильный Advantage, ничего не сделает, в отличие от aptitude, если он обнаружит какие-либо неправильные Advantage, обновит их и установит пакет без каких-либо проблем.

Что такое «/dev» в Linux?

Символ «/» в начале — это корень в Linux, а «dev» — это файл каталога, содержащий файлы устройств в корне. Корневая файловая система содержит все инструменты, необходимые для поддержания работоспособности системы.

\ботинок:

Загрузочный раздел — это раздел диска, содержащий папку операционной системы, а также основной раздел, содержащий загрузчик.

Что такое /dev/sda в Linux?

Термин «sd» означает диск SCSI (Small System Computer Interface), поэтому «sda» означает первый жесткий диск SCSI, каждый раздел на диске имеет такие имена, как «sda1», «sda2» и т. д.

МАЖ:МИН :

«Основные и второстепенные номера», основной номер — это номер драйвера устройства, а второстепенный номер — это номер самого устройства.

Ext4:

Файловая система ext4 представляет собой обновленную версию файловой системы ext3 и может поддерживать файлы и файловые системы размером до 16 терабайт.

разница между первичным и логическим разделом?

На одном диске может существовать только 4 основных раздела, количество логических разделов, которые могут существовать на диске, не ограничено.

Что такое точка монтирования?

Точка монтирования — это каталог в файловой системе, который логически связан с другой файловой системой.

Область обмена:

Пространство подкачки в Linux используется, когда объем физической памяти (ОЗУ) заполнен. Если системе требуется больше ресурсов памяти, а ОЗУ заполнено, неактивные страницы в памяти перемещаются в пространство подкачки.

SSH-соединение:

ssh или Secure Shell — это сетевой протокол связи, позволяющий двум компьютерам общаться.

Уровни SSH:

Транспортный уровень: обеспечение безопасной связи между сервером и клиентом, мониторинг шифрования/дешифрования данных.

Уровень аутентификации: проводит процедуру аутентификации клиента.

Уровень соединения: управляет каналами связи после аутентификации.

что такое сервер?

Сервер — это компьютерная программа или устройство, предоставляющее услуги другой компьютерной программе и ее пользователям.

/и т. д :

содержит все файлы конфигурации системы. Всякий раз, когда вы хотите изменить что-то, что влияет на всех пользователей вашего компьютера, например, способ подключения к Интернету или тип вашей видеокарты, вам, вероятно, придется войти в систему как root и изменить файл в /etc.

Что такое порт?

порт НЕ является физическим соединением.

Это логическое соединение, используемое программами и серверами для обмена информацией.

он конкретно определяет, какая программа или служба на компьютере или сервере будет использоваться.

что такое гипервизор?

- Гипервизор — это монитор виртуальной машины, программное обеспечение, которое создает и запускает виртуальную машину.

- Гипервизор позволяет одному хост-компьютеру поддерживать несколько гостевых виртуальных машин, виртуально разделяя свои ресурсы, такие как память, ЦП…

что такое сервер?

Сервер — это компьютерная программа или устройство, предоставляющее услуги другой компьютерной программе.

Примечание: ядро ​​имеет 4 задачи:

Управление памятью, управление процессами, драйверы устройств, системные вызовы и безопасность.

что такое AppArmor?

AppArmor — это приложение, которое позволяет нам ограничивать доступ к некоторым приложениям и программам… и разрешать доступ только к некоторым частям системы.

Что такое TCP?

TCP означает протокол управления передачей — стандарт связи, позволяющий приложениям, программам и компьютерным устройствам обмениваться сообщениями по сети.

Что такое ИС?

IP-адрес (интернет-протокол) однозначно идентифицирует компьютер/сервер в Интернете.

Что такое телетайп:

Операционная система Linux представляет все в файловой системе, Терминал также представлен как файл. Существует команда, называемая tty, которая отображает информацию, связанную с терминалом.

что такое УФВ?

Брандмауэр (от англ. uncomplicated firewall) — это система сетевой безопасности, которая предотвращает несанкционированный доступ в частную сеть.

что такое cron и crontab ?

Cron: происходит от chron, греческого префикса для «времени». Cron — это метод автоматического запуска команд по расписанию. Запланированное задание называется cronjob и создается в файле crontab. Это самый простой и старый способ для пользователей компьютеров автоматизировать свои задачи.
Что такое команда «Стена»?

Команда wall в Linux используется для написания сообщения всем пользователям. Эта команда отображает сообщение или содержимое файла.

✏️ Автор: Нозель
https://github.com/benmaia/42_Born2beRoot_Guide/tree/master/Born2beRoot
2cursus - Born2beroot
Оглавление
Установка
судо
Шаг 1: Установка sudo
Шаг 2: Добавление пользователя в группу sudo
Шаг 3: Запуск привилегированных команд root
Шаг 4: Настройка sudo
SSH
Шаг 1: Установка и настройка SSH
Шаг 2: Установка и настройка UFW
Шаг 3: Подключение к серверу через SSH
Управление пользователями
Шаг 1: Настройка надежной политики паролей
Возраст пароля
Надежность пароля
Шаг 2: Создание нового пользователя
Шаг 3: Создание новой группы
хрон
Настройка задания cron
Бонус
Установка
Linux Lighttpd MariaDB PHP (LLMP) Стек
Шаг 1: Установка Lighttpd
Шаг 2: Установка и настройка MariaDB
Шаг 3: Установка PHP
Шаг 4: Загрузка и настройка WordPress
Шаг 5: Настройка Lighttpd
Протокол передачи файлов (FTP)
Шаг 1: Установка и настройка FTP
Шаг 2: Подключение к серверу через FTP
Установка
На момент написания статьи последней стабильной версией Debian является Debian 10 Buster . Посмотрите бонусное пошаговое руководство по установке (без звука) здесь .

судо
Шаг 1: Установка sudo
Переключитесь на root и его среду через su -.

$ su -
Password:
#
Установите sudo через apt install sudo.

# apt install sudo
Проверьте, успешно ли был установлен sudodpkg -l | grep sudo с помощью .

# dpkg -l | grep sudo
Шаг 2: Добавление пользователя в группу sudo
Добавьте пользователя в группу sudoadduser <username> sudo через .

# adduser <username> sudo
Либо добавьте пользователя в группу sudousermod -aG sudo <username> через .

# usermod -aG sudo <username>
Проверьте, был ли пользователь успешно добавлен в группу sudogetent group sudo с помощью .

$ getent group sudo
rebootЧтобы изменения вступили в силу, войдите в систему и проверьте sudopowers через sudo -v.

# reboot
<--->
Debian GNU/Linux 10 <hostname> tty1

<hostname> login: <username>
Password: <password>
<--->
$ sudo -v
[sudo] password for <username>: <password>
Шаг 3: Запуск привилегированных команд root
С этого момента запускайте команды root -привилегированные через префикс sudo. Например:

$ sudo apt update
Шаг 4: Настройка sudo
Настройте sudo через sudo vi /etc/sudoers.d/<filename>. <filename>не должно заканчиваться на . ~или содержать ..

$ sudo vi /etc/sudoers.d/<filename>
Чтобы ограничить аутентификацию с помощью sudo тремя попытками (по умолчанию установлено 3) в случае неверного пароля, добавьте в файл следующую строку.

Defaults        passwd_tries=3
Чтобы добавить пользовательское сообщение об ошибке в случае неверного пароля:

Defaults        badpass_message="<custom-error-message>"
Чтобы записать все команды sudo/var/log/sudo/<filename> в :

$ sudo mkdir /var/log/sudo
<~~~>
Defaults        logfile="/var/log/sudo/<filename>"
<~~~>
Чтобы архивировать все входы и выходы sudo в /var/log/sudo/:

Defaults        log_input,log_output
Defaults        iolog_dir="/var/log/sudo"
Чтобы запросить TTY :

Defaults        requiretty
Чтобы задать пути sudo/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin:/snap/bin :

Defaults        secure_path="/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin:/snap/bin"
SSH
Шаг 1: Установка и настройка SSH
Установите openssh-server через sudo apt install openssh-server.

$ sudo apt install openssh-server
Проверьте, успешно ли был установлен openssh-serverdpkg -l | grep ssh с помощью .

$ dpkg -l | grep ssh
Настройте SSH через sudo vi /etc/ssh/sshd_config.

$ sudo vi /etc/ssh/sshd_config
Чтобы настроить SSH с использованием порта 4242, замените следующую строку:

13 #Port 22
с:

13 Port 4242
Чтобы отключить вход по SSH как root независимо от механизма аутентификации, замените следующую строку:

32 #PermitRootLogin prohibit-password
с:

32 PermitRootLogin no
Проверьте статус SSH через sudo service ssh status.

$ sudo service ssh status
Либо проверьте статус SSH через systemctl status ssh.

$ systemctl status ssh
Шаг 2: Установка и настройка UFW
Установите UFW через sudo apt install ufw.

$ sudo apt install ufw
Проверьте, успешно ли был установлен UFWdpkg -l | grep ufw с помощью .

$ dpkg -l | grep ufw
Включить брандмауэр через sudo ufw enable.

$ sudo ufw enable
Разрешить входящие соединения через порт 4242 через sudo ufw allow 4242.

$ sudo ufw allow 4242
Проверьте статус UFW через sudo ufw status.

$ sudo ufw status
Шаг 3: Подключение к серверу через SSH
Подключитесь к своей виртуальной машине по SSH, используя порт 4242 через ssh <username>@<ip-address> -p 4242.

$ ssh <username>@<ip-address> -p 4242
Завершить сеанс SSH можно в любое время с помощью logout.

$ logout
Либо завершите сеанс SSH с помощью exit.

$ exit
Управление пользователями
Шаг 1: Настройка надежной политики паролей
Возраст пароля
Настройте политику срока действия паролей с помощью sudo vi /etc/login.defs.

$ sudo vi /etc/login.defs
Чтобы установить срок действия пароля каждые 30 дней, замените следующую строку

160 PASS_MAX_DAYS   99999
с:

160 PASS_MAX_DAYS   30
Чтобы установить минимальное количество дней между сменами пароля равным 2 дням, замените строку ниже

161 PASS_MIN_DAYS   0
с:

161 PASS_MIN_DAYS   2
Чтобы отправить пользователю предупреждающее сообщение за 7 дней (по умолчанию за 7 дней) до истечения срока действия пароля, оставьте строку ниже как есть.

162 PASS_WARN_AGE   7
Надежность пароля
Во-вторых, чтобы настроить политики в отношении надежности пароля, установите пакет libpam-pwquality .

$ sudo apt install libpam-pwquality
Проверьте, была ли успешно установлена ​​libpam-pwqualitydpkg -l | grep libpam-pwquality с помощью .

$ dpkg -l | grep libpam-pwquality
Настройте политику надежности пароля с помощью sudo vi /etc/pam.d/common-password, в частности, следующей строки:

$ sudo vi /etc/pam.d/common-password
<~~~>
25 password        requisite                       pam_pwquality.so retry=3
<~~~>
Чтобы установить минимальную длину пароля в 10 символов, добавьте указанную ниже опцию в строку выше.

minlen=10
Чтобы пароль содержал как минимум заглавную букву и цифру:

ucredit=-1 dcredit=-1
Чтобы установить максимум 3 последовательных одинаковых символа:

maxrepeat=3
Чтобы отклонить пароль, если он содержит <username>в какой-либо форме:

reject_username
Чтобы установить необходимое количество изменений старого пароля в новом пароле равным 7:

difok=7
Чтобы реализовать ту же политику для root :

enforce_for_root
В конечном итоге это должно выглядеть так, как показано ниже:

password        requisite                       pam_pwquality.so retry=3 minlen=10 ucredit=-1 dcredit=-1 maxrepeat=3 reject_username difok=7 enforce_for_root
Шаг 2: Создание нового пользователя
Создайте нового пользователя через sudo adduser <username>.

$ sudo adduser <username>
Проверьте, был ли пользователь успешно создан с помощью getent passwd <username>.

$ getent passwd <username>
Проверьте информацию об истечении срока действия пароля вновь созданного пользователя с помощью sudo chage -l <username>.

$ sudo chage -l <username>
Last password change					: <last-password-change-date>
Password expires					: <last-password-change-date + PASS_MAX_DAYS>
Password inactive					: never
Account expires						: never
Minimum number of days between password change		: <PASS_MIN_DAYS>
Maximum number of days between password change		: <PASS_MAX_DAYS>
Number of days of warning before password expires	: <PASS_WARN_AGE>
Шаг 3: Создание новой группы
Создайте новую группу user42sudo addgroup user42 через .

$ sudo addgroup user42
Добавьте пользователя в группу user42sudo adduser <username> user42 через .

$ sudo adduser <username> user42
Либо добавьте пользователя в группу user42sudo usermod -aG user42 <username> через .

$ sudo usermod -aG user42 <username>
Проверьте, был ли пользователь успешно добавлен в группу user42getent group user42 через .

$ getent group user42
хрон
Настройка задания cron
Настройте cron как root через sudo crontab -u root -e.

$ sudo crontab -u root -e
Чтобы запланировать запуск скрипта оболочки каждые 10 минут, замените следующую строку

23 # m h  dom mon dow   command
с:

23 */10 * * * * sh /path/to/script
Проверьте запланированные задания cron пользователя root с помощью .sudo crontab -u root -l

$ sudo crontab -u root -l
Бонус
#1: Установка
Посмотрите бонусное пошаговое руководство по установке (без звука) здесь .

#2: Linux Lighttpd MariaDB PHP (LLMP) Стек
Шаг 1: Установка Lighttpd
Установите lighttpd через sudo apt install lighttpd.

$ sudo apt install lighttpd
Проверьте, успешно ли был установлен lighttpddpkg -l | grep lighttpd с помощью .

$ dpkg -l | grep lighttpd
Разрешить входящие соединения через порт 80 через sudo ufw allow 80.

$ sudo ufw allow 80
Шаг 2: Установка и настройка MariaDB
Установите mariadb-server через sudo apt install mariadb-server.

$ sudo apt install mariadb-server
Проверьте, успешно ли был установлен mariadb-serverdpkg -l | grep mariadb-server с помощью .

$ dpkg -l | grep mariadb-server
Запустить интерактивный скрипт для удаления небезопасных настроек по умолчанию через sudo mysql_secure_installation.

$ sudo mysql_secure_installation
Enter current password for root (enter for none): #Just press Enter (do not confuse database root with system root)
Set root password? [Y/n] n
Remove anonymous users? [Y/n] Y
Disallow root login remotely? [Y/n] Y
Remove test database and access to it? [Y/n] Y
Reload privilege tables now? [Y/n] Y
Войдите в консоль MariaDB через sudo mariadb.

$ sudo mariadb
MariaDB [(none)]>
Создать новую базу данных через CREATE DATABASE <database-name>;.

MariaDB [(none)]> CREATE DATABASE <database-name>;
Создайте нового пользователя базы данных и предоставьте ему полные привилегии для вновь созданной базы данных через GRANT ALL ON <database-name>.* TO '<username-2>'@'localhost' IDENTIFIED BY '<password-2>' WITH GRANT OPTION;.

MariaDB [(none)]> GRANT ALL ON <database-name>.* TO '<username-2>'@'localhost' IDENTIFIED BY '<password-2>' WITH GRANT OPTION;
Сбросьте привилегии через FLUSH PRIVILEGES;.

MariaDB [(none)]> FLUSH PRIVILEGES;
Выйдите из оболочки MariaDB через exit.

MariaDB [(none)]> exit
Проверьте, был ли успешно создан пользователь базы данных, войдя в консоль MariaDB через mariadb -u <username-2> -p.

$ mariadb -u <username-2> -p
Enter password: <password-2>
MariaDB [(none)]>
Подтвердите, имеет ли пользователь базы данных доступ к базе данных через SHOW DATABASES;.

MariaDB [(none)]> SHOW DATABASES;
+--------------------+
| Database           |
+--------------------+
| <database-name>    |
| information_schema |
+--------------------+
Выйдите из оболочки MariaDB через exit.

MariaDB [(none)]> exit
Шаг 3: Установка PHP
Установите php-cgi и php-mysql через sudo apt install php-cgi php-mysql.

$ sudo apt install php-cgi php-mysql
Проверьте, успешно ли установлены php-cgi и php-mysqldpkg -l | grep php с помощью .

$ dpkg -l | grep php
Шаг 4: Загрузка и настройка WordPress
Установите wget через sudo apt install wget.

$ sudo apt install wget
Загрузите WordPress /var/www/htmlчерез sudo wget http://wordpress.org/latest.tar.gz -P /var/www/html.

$ sudo wget http://wordpress.org/latest.tar.gz -P /var/www/html
Извлеките загруженный контент через sudo tar -xzvf /var/www/html/latest.tar.gz.

$ sudo tar -xzvf /var/www/html/latest.tar.gz
Удалить тарбол через sudo rm /var/www/html/latest.tar.gz.

$ sudo rm /var/www/html/latest.tar.gz
Копировать содержимое /var/www/html/wordpressв /var/www/htmlчерез sudo cp -r /var/www/html/wordpress/* /var/www/html.

$ sudo cp -r /var/www/html/wordpress/* /var/www/html
Удалить /var/www/html/wordpressчерезsudo rm -rf /var/www/html/wordpress

$ sudo rm -rf /var/www/html/wordpress
Создайте файл конфигурации WordPress из его примера с помощью sudo cp /var/www/html/wp-config-sample.php /var/www/html/wp-config.php.

$ sudo cp /var/www/html/wp-config-sample.php /var/www/html/wp-config.php
Настройте WordPress для ссылки на ранее созданную базу данных MariaDB и пользователя через sudo vi /var/www/html/wp-config.php.

$ sudo vi /var/www/html/wp-config.php
Заменить нижеприведенное

23 define( 'DB_NAME', 'database_name_here' );^M
26 define( 'DB_USER', 'username_here' );^M
29 define( 'DB_PASSWORD', 'password_here' );^M
с:

23 define( 'DB_NAME', '<database-name>' );^M
26 define( 'DB_USER', '<username-2>' );^M
29 define( 'DB_PASSWORD', '<password-2>' );^M
Шаг 5: Настройка Lighttpd
Включите указанные ниже модули через sudo lighty-enable-mod fastcgi; sudo lighty-enable-mod fastcgi-php; sudo service lighttpd force-reload.

$ sudo lighty-enable-mod fastcgi
$ sudo lighty-enable-mod fastcgi-php
$ sudo service lighttpd force-reload
#3: Протокол передачи файлов (FTP)
Шаг 1: Установка и настройка FTP
Установить FTP через sudo apt install vsftpd.

$ sudo apt install vsftpd
Проверьте, успешно ли был установлен vsftpddpkg -l | grep vsftpd с помощью .

$ dpkg -l | grep vsftpd
Разрешить входящие соединения через порт 21 через sudo ufw allow 21.

$ sudo ufw allow 21
Настройте vsftpd через sudo vi /etc/vsftpd.conf.

$ sudo vi /etc/vsftpd.conf
Чтобы включить любую форму команды записи FTP, раскомментируйте следующую строку:

31 #write_enable=YES
Чтобы задать корневую папку для пользователя, подключенного по FTP /home/<username>/ftp, добавьте следующие строки:

$ sudo mkdir /home/<username>/ftp
$ sudo mkdir /home/<username>/ftp/files
$ sudo chown nobody:nogroup /home/<username>/ftp
$ sudo chmod a-w /home/<username>/ftp
<~~~>
user_sub_token=$USER
local_root=/home/$USER/ftp
<~~~>
Чтобы запретить пользователю доступ к файлам или использование команд за пределами дерева каталогов, раскомментируйте следующую строку:

114 #chroot_local_user=YES
Чтобы добавить FTP в белый список, добавьте следующие строки:

$ sudo vi /etc/vsftpd.userlist
$ echo <username> | sudo tee -a /etc/vsftpd.userlist
<~~~>
userlist_enable=YES
userlist_file=/etc/vsftpd.userlist
userlist_deny=NO
<~~~>
Шаг 2: Подключение к серверу через FTP
Подключитесь к своей виртуальной машине по протоколу FTP через ftp <ip-address>.

$ ftp <ip-address>
Завершить сеанс FTP можно в любое время с помощью CTRL + D.
