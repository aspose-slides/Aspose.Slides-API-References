---
title: get_LocalName()
second_title: Aspose.Slides для C++ справочник API
description: Возвращает локальное имя текущего узла.
type: docs
weight: 27
url: /ru/system.xml/xmlnodereader/get_localname/
---
## XmlNodeReader::get_LocalName() метод


Возвращает локальное имя текущего узла.

```cpp
String System::Xml::XmlNodeReader::get_LocalName() override
```


### Возвращаемое значение

Имя текущего узла без префикса. Например, **LocalName** равно **book** для элемента **<bk:book>**. Для типов узлов, которые не имеют имени (например, **[Text](../../../system.text/)**, **Comment** и т.д.), этот метод возвращает [String::Empty](../../../system/string/empty/).

## См. также

* Класс [String](../../../system/string/)
* Класс [XmlNodeReader](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)