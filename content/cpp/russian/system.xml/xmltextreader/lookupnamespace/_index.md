---
title: LookupNamespace()
second_title: Справочник API Aspose.Slides для C++
description: Разрешает префикс пространства имён в области видимости текущего элемента.
type: docs
weight: 612
url: /ru/system.xml/xmltextreader/lookupnamespace/
---
## XmlTextReader::LookupNamespace(const String\&) метод


Разрешает префикс пространства имён в области видимости текущего элемента.

```cpp
String System::Xml::XmlTextReader::LookupNamespace(const String &prefix) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Префикс, пространство имён которого вы хотите разрешить. Чтобы сопоставить префикс со стандартным пространством имён, передайте пустую строку. Эта строка не обязана быть атомизирована. |

### Возвращаемое значение

URI пространства имён, к которому сопоставлен префикс, или **nullptr**, если соответствующий префикс не найден.

## См. также

* Класс [String](../../../system/string/)
* Класс [XmlTextReader](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)