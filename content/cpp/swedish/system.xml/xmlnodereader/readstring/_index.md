---
title: ReadString()
second_title: Aspose.Slides för C++ API-referens
description: Läser innehållet i ett element eller en textnod som en sträng.
type: docs
weight: 391
url: /sv/system.xml/xmlnodereader/readstring/
---
## XmlNodeReader::ReadString() metod


Läser innehållet i ett element eller en textnod som en sträng.

```cpp
String System::Xml::XmlNodeReader::ReadString() override
```


### Returnvärde

Innehållet i elementet eller den textliknande noden (Det här kan inkludera CDATA, [Text](../../../system.text/) noder och så vidare). Detta kan vara en tom sträng om läsaren är placerad på något annat än ett element eller en textnod, eller om det inte finns mer textinnehåll att returnera i det aktuella sammanhanget. Obs: Textnoden kan vara antingen ett element eller ett attributtextnod.

## Se även

* Klass [String](../../../system/string/)
* Klass [XmlNodeReader](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)