---
title: WriteProcessingInstruction()
second_title: Aspose.Slides för C++ API-referens
description: "När den åsidosätts i en avledd klass skriver den ut en bearbetningsinstruktion med ett mellanslag mellan namn och text enligt följande: <?name text?>."
type: docs
weight: 196
url: /sv/system.xml/xmlwriter/writeprocessinginstruction/
---
## XmlWriter::WriteProcessingInstruction(String, String) metod


När den åsidosätts i en avledd klass skriver den ut en bearbetningsinstruktion med ett mellanslag mellan namn och text enligt följande: **<?name text?>**.

```cpp
virtual void System::Xml::XmlWriter::WriteProcessingInstruction(String name, String text)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | [String](../../../system/string/) | Namnet på bearbetningsinstruktionen. |
| text | [String](../../../system/string/) | Texten som ska inkluderas i bearbetningsinstruktionen. |
## Anmärkningar



Denna metod används för att skapa en XML-deklaration efter att [XmlWriter::WriteStartDocument](../writestartdocument/) redan har anropats. 
## Se också

* Klass [String](../../../system/string/)
* Klass [XmlWriter](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)