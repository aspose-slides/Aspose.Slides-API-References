---
title: WriteProcessingInstruction()
second_title: Aspose.Slides C++ API Referencia
description: "Ha felülírják egy leszármazott osztályban, egy feldolgozási utasítást ír ki, a név és a szöveg között szóközzel, a következőképpen: <?name text?>."
type: docs
weight: 196
url: /hu/system.xml/xmlwriter/writeprocessinginstruction/
---
## XmlWriter::WriteProcessingInstruction(String, String) metódus


Ha felülírják egy leszármazott osztályban, egy feldolgozási utasítást ír ki, a név és a szöveg között szóközzel, a következőképpen: **<?name text?>**.

```cpp
virtual void System::Xml::XmlWriter::WriteProcessingInstruction(String name, String text)=0
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | A feldolgozási utasítás neve. |
| text | [String](../../../system/string/) | A feldolgozási utasításba belefoglalt szöveg. |
## Megjegyzések



Ez a metódus egy XML deklaráció létrehozására használatos, miután a [XmlWriter::WriteStartDocument](../writestartdocument/) már meghívásra került. 
## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [XmlWriter](../)
* Névterület [System::Xml](../../)
* Library [Aspose.Slides](../../../)