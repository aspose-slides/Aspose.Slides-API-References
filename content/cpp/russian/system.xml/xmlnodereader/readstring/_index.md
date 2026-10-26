---
title: ReadString()
second_title: Справочник API Aspose.Slides для C++
description: Считывает содержимое элемента или текстового узла в виде строки.
type: docs
weight: 391
url: /ru/system.xml/xmlnodereader/readstring/
---
## XmlNodeReader::ReadString() method

Считывает содержимое элемента или текстового узла в виде строки.

```cpp
String System::Xml::XmlNodeReader::ReadString() override
```

### Возвращаемое значение

Содержимое элемента или текстоподобного узла (может включать CDATA, [Text](../../../system.text/) узлы и т.д.). Может быть пустой строкой, если читатель находится не на элементе или текстовом узле, либо если в текущем контексте нет дополнительного текстового содержимого для возврата. Примечание: Текстовый узел может быть как элементом, так и атрибутом текстового узла.

## См. также

* Класс [String](../../../system/string/)
* Класс [XmlNodeReader](../)
* Пространство имён [System::Xml](../../)
* Library [Aspose.Slides](../../../)