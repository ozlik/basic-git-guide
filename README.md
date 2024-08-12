# Гайд по Git для новичков  
## Описание программы  
Git — это специальная программа, которая позволяет отслеживать любые изменения в файлах, хранить их версии и оперативно возвращаться в любое сохранённое состояние.  
Git может быть локальным, централизованным или распределённым:  
* **Локальный** установлен на одном компьютере и хранит файлы только в одном экземпляре в рамках настроенного окружения — подходит, если программист пишет код в одиночку.  
* **Централизованный** находится на общем севере и хранит все файлы на нем.
* **Распределённый** хранит данные и в общем облачном хранилище, и в устройствах участников команды.  
[Источник](https://practicum.yandex.ru/blog/chto-takoe-git-i-dlya-chego-nuzhen/ ""Яндекс Практикум") 
Для работы с Git понадобится консоль.  
Для операционной системы Windows можно воспользоваться программой Bash.  
Для операционно системы Linux воспользоваться строенной программой Terminal.  

## Основные команды 
######Показать текущую директорию (print working directory)
```bash
 pwd
``` 
######Вывести содержимое директории (list)
```bash
ls
```
######Вывести содержимое директории, включая скрытые файлы
```bash
 ls -a
```
######Вывести содержимое домашней директории
```bash
 ls ~
```
######Сменить директорию (change directory)
```bash
 cd
```
######Создать директорию (make directory)
```bash
 mkdir
```
######Создать структуру директорий
```bash
 mkdir -p dir1/dir-inside/dir-deeper-inside
```
######Создать файл в текущей директории
```bash
 touch
```