---
title: License()
second_title: Справочник API Aspose.Slides для C++
description: Инициализирует новый экземпляр этого класса.
type: docs
weight: 1
url: /ru/aspose.slides/license/license/
---
## License::License() конструктор

Инициализирует новый экземпляр этого класса.

```cpp
Aspose::Slides::License::License()
```

## Примечания

В этом примере будет выполнена попытка найти файл лицензии с именем MyLicense.lic в папке, содержащей компонент, в папке, содержащей вызывающую сборку, в папке входной сборки, а затем во встроенных ресурсах вызывающей сборки.
```cpp
auto license = MakeObject<License>();
license->SetLicense(u"MyLicense.lic");
```

## Смотрите также

* Класс [License](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)