---
title: get_LocalName()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает локальное имя текущего узла.
type: docs
weight: 27
url: /ru/system.xml/xmltextreader/get_localname/
---
## XmlTextReader::get_LocalName() метод


Возвращает локальное имя текущего узла.

```cpp
String System::Xml::XmlTextReader::get_LocalName() override
```


### Возвращаемое значение

Имя текущего узла без префикса. Например, **LocalName** равно **book** для элемента **<bk:book>**. Для типов узлов, у которых нет имени (например, **[Text](../../../system.text/)**, **Comment** и т.д.), этот метод возвращает [String::Empty](../../../system/string/empty/).

## См. также

* Класс [String](../../../system/string/)
* Класс [XmlTextReader](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)