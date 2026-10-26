---
title: get_LocalName()
second_title: Справка API Aspose.Slides для C++
description: Когда переопределяется в производном классе, возвращает локальное имя текущего узла.
type: docs
weight: 40
url: /ru/system.xml/xmlreader/get_localname/
---
## XmlReader::get_LocalName() метод


Когда переопределяется в производном классе, возвращает локальное имя текущего узла.

```cpp
virtual String System::Xml::XmlReader::get_LocalName()=0
```


### Возвращаемое значение

Имя текущего узла без префикса. Например, **LocalName** равно **book** для элемента **<bk:book>**. Для типов узлов, которые не имеют имени (например, **[Text](../../../system.text/)**, **Comment**, и т.д.), этот метод возвращает [String::Empty](../../../system/string/empty/).

## См. также

* Класс [String](../../../system/string/)
* Класс [XmlReader](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)