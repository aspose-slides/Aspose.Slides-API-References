---
title: get_Encoding()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает уровень кодировки XML-документа.
type: docs
weight: 14
url: /ru/system.xml/xmldeclaration/get_encoding/
---
## XmlDeclaration::get_Encoding() метод


Возвращает уровень кодировки XML-документа.

```cpp
String System::Xml::XmlDeclaration::get_Encoding()
```


### Возвращаемое значение

Допустимое имя кодировки символов.
## Примечания



Наиболее часто поддерживаемые имена кодировок символов для XML следующие: 

| Категория | Имена кодировок |
| --- | --- |
| Unicode | UTF-8, UTF-16 |
| ISO 10646 | ISO-10646-UCS-2, ISO-10646-UCS-4 |
| ISO 8859 | ISO-8859-n (где "n" — цифра от 1 до 9) |
| JIS X-0208-1997 | ISO-2022-JP, Shift_JIS, EUC-JP |


Это значение является необязательным. Если значение не установлено, этот метод возвращает [String::Empty](../../../system/string/empty/). Если атрибут кодировки не включён, считается, что используется кодировка UTF-8 при записи или сохранении документа. 
## См. также

* Класс [String](../../../system/string/)
* Класс [XmlDeclaration](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)