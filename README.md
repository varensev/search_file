
# Копирование файлов с использованием Node.js и VS Code
Этот код на JavaScript позволяет выполнять поиск файлов в указанной папке и копировать найденные файлы в другую папку. Ниже приведены инструкции для установки Node.js и VS Code, а также описание кода и его использование.
## Нужно скачать архив с программой
![image](https://github.com/meVarensev/search_file/assets/57268467/0c448703-4acf-4453-92fd-ce989616f254)

## Установка Node.js
* Посетите [официальный сайт Node.js](https://nodejs.org/en) и загрузите LTS версию установщик для своей операционной системы  .
* Запустите загруженный установщик Node.js.
* Следуйте инструкциям мастера установки, принимая стандартные настройки.
* По завершении установки у вас будет установлен Node.js и npm (менеджер пакетов Node.js).
## Установка VS Code
* Посетите официальный [сайт Visual Studio Code](https://code.visualstudio.com/) и загрузите установщик для вашей операционной системы.
* Запустите загруженный установщик VS Code.
* Следуйте инструкциям мастера установки, принимая стандартные настройки.
* По завершении установки у вас будет установлен и готов к использованию Visual Studio Code

## Открытие файла search_file.js с помощью VS Code
* Запустите Visual Studio Code.
* В меню выберите "File" (Файл) -> "Open" (Открыть).
* Укажите путь к файлу search_file.js и нажмите "Open" (Открыть).
* Теперь файл search_file.js будет открыт в редакторе VS Code и вы сможете вносить изменения в код.

## Указание имен файлов изображений
```
    const fileNames = [
    '6707',
    '6711',
    '6722',
    // Добавьте остальные неполные имена файлов
    ]
```
В массиве fileNames указаны неполные имена файлов, без расширений. Это означает, что код будет искать файлы, начинающиеся с указанных неполных имен.
## Запуск программы
* Откройте командную строку (терминал) в папке с файлом search_file.js.
* В командной строке введите команду:
```
    node search_file.js
```
* Нажмите клавишу "Enter" для запуска программы.
* Программа начнет поиск файлов с указанными именами и скопирует найденные файлы в другую папку.
* Пожалуйста, убедитесь, что у вас установлены Node.js и VS Code перед запуском программы.

  Этот скрипт предназначен для изменения размера фотографий и наложения водяных знаков. Он использует библиотеку Jimp для обработки изображений.

  
## add_logo.js
Установка
* Убедитесь, что у вас установлен Node.js на вашем компьютере.
* Скопируйте все файлы скрипта в локальную папку на вашем компьютере.
## Использование replace_files.py
Запуск команды через интерпретатор python, версии 3.8+
python3 replace_files.py --source <Путь до исходной папки с файлами> --destination <Путь до итоговой папки(должна существовать!)>
## Использование
* Откройте файл index.js в текстовом редакторе.
* Настройте пути к папке с фотографиями (photoFolderPath), горизонтальному водяному знаку (watermarkHorizontalPath) и вертикальному водяному знаку (watermarkVerticalPath), заменив соответствующие значения в строках кода.
* Задайте необходимые значения ширины и высоты целевого изображения (targetWidth и targetHeight), в зависимости от ориентации фотографии (горизонтальная или вертикальная).
* Откройте командную строку (терминал) и перейдите в папку, где находится скрипт.
* Выполните следующую команду для установки зависимостей:

```
    npm install jimp
```
* Запустите скрипт с помощью следующей команды:
  
```
    node add_logo.js
```
* Скрипт начнет обрабатывать фотографии в указанной папке. Обработанные фотографии будут сохранены в подпапке output в исходной папке с фотографиями. На каждой фотографии будет наложен соответствующий водяной знак в зависимости от ориентации.
## Примечания
* Поддерживаемые форматы изображений: JPEG, PNG, GIF.
* При использовании скрипта убедитесь, что папка с фотографиями содержит только нужные файлы, поскольку скрипт будет обрабатывать все файлы с расширениями JPEG, PNG и GIF.
* Убедитесь, что у вас есть достаточно свободного места на диске для сохранения обработанных фотографий.
