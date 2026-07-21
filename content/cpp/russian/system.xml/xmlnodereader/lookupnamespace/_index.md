---
title: LookupNamespace()
second_title: Aspose.Slides для C++ справочник API
description: Разрешает префикс пространства имен в области видимости текущего элемента.
type: docs
weight: 404
url: /ru/system.xml/xmlnodereader/lookupnamespace/
---
## XmlNodeReader::LookupNamespace(const String\&) метод

Разрешает префикс пространства имен в области видимости текущего элемента.

```cpp
String System::Xml::XmlNodeReader::LookupNamespace(const String &prefix) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Префикс, чье пространство имён URI вы хотите разрешить. Чтобы сопоставить пространство имён по умолчанию, передайте пустую строку. Эта строка не обязана быть атомизирована. |

### Возвращаемое значение

URI пространства имён, к которому сопоставлен префикс, или **nullptr**, если соответствующий префикс не найден.

## См. также

* Класс [String](../../../system/string/)
* Класс [XmlNodeReader](../)
* Пространство имен [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)