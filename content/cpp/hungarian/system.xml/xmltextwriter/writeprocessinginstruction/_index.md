---
title: WriteProcessingInstruction()
second_title: Aspose.Slides for C++ API referenciája
description: "Kiír egy feldolgozási utasítást, ahol a név és a szöveg között szóköz van, a következő módon: <?name text?>."
type: docs
weight: 326
url: /hu/system.xml/xmltextwriter/writeprocessinginstruction/
---
## XmlTextWriter::WriteProcessingInstruction(String, String) metódus

Kiír egy feldolgozási utasítást, ahol a név és a szöveg között szóköz van, a következő módon: **<?name text?>**.

```cpp
void System::Xml::XmlTextWriter::WriteProcessingInstruction(String name, String text) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | [String](../../../system/string/) | A feldolgozási utasítás neve. |
| text | [String](../../../system/string/) | [Text](../../../system.text/) a feldolgozási utasításba. |
## Megjegyzések

Ez a metódus egy XML deklaráció létrehozására használatos, miután [XmlTextWriter::WriteStartDocument](../writestartdocument/) már meghívásra került. 
## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [XmlTextWriter](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)