---
title: get_LocalName()
second_title: Aspose.Slides для справочника API C++
description: Возвращает локальное имя текущего узла.
type: docs
weight: 27
url: /ru/system.xml/xmlvalidatingreader/get_localname/
---
## XmlValidatingReader::get_LocalName() метод


Возвращает локальное имя текущего узла.

```cpp
String System::Xml::XmlValidatingReader::get_LocalName() override
```


### Возвращаемое значение

Имя текущего узла без префикса. Например, **LocalName** равно **book** для элемента **<bk:book>**. Для типов узлов, которые не имеют имени (например, **[Text](../../../system.text/)**, **Comment**, и так далее), этот метод возвращает [String::Empty](../../../system/string/empty/).

## Смотрите также

* Класс [String](../../../system/string/)
* Класс [XmlValidatingReader](../)
* Пространство имен [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)