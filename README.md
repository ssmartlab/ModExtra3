## Быстрый старт

* Учтановитт MODX Revolution v3.*

* Загрузите этот пакет в каталог `Extras` в корне сайта.

* Вам нужно переименовать пакет в название вашего пакета (например: `AnyOtherName`), поэтому войдите в консоль SSH и запустите
```
php ~/www/Extras/ModExtra3/rename_it.php AnyOtherName
```
*название пакета может быть любым но начинаться с большой буквы*

* Установка пакета на сайте разработки
```
php ~/www/Extras/AnyOtherName/_build/build.php
``` 

## Настройки

См. `_build/config.inc.php` для редактируемых параметров пакета.

Все resolvers и elements находятся в пути `_build`. Все файлы, начинающиеся не с `.` или `_`, будут добавлены автоматически.

Если вы добавите новый тип элемента, вам также нужно будет добавить метод с таким именем в скрипт `build.php`.

## Собрать и скачать

Вы можете собрать пакет в любое время, открыв `http://dev.site.com/Extras/AnyOtherName/_build/build.php`

Если вы хотите скачать готовый пакет - добавьте `?download=1` в адрес сборки.
