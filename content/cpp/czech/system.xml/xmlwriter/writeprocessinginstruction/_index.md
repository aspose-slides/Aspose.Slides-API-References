---
title: WriteProcessingInstruction()
second_title: Aspose.Slides pro C++ API Reference
description: "Když je přepsána v odvozené třídě, zapíše instrukci zpracování s mezerou mezi názvem a textem následujícím způsobem: <?name text?>."
type: docs
weight: 196
url: /cs/system.xml/xmlwriter/writeprocessinginstruction/
---
## XmlWriter::WriteProcessingInstruction(String, String) metoda

Když je přepsána v odvozené třídě, zapíše instrukci zpracování s mezerou mezi názvem a textem následujícím způsobem: **<?name text?>**.

```cpp
virtual void System::Xml::XmlWriter::WriteProcessingInstruction(String name, String text)=0
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Název instrukce zpracování. |
| text | [String](../../../system/string/) | Text, který se má zahrnout do instrukce zpracování. |

## Poznámky

Tato metoda se používá k vytvoření deklarace XML poté, co byl [XmlWriter::WriteStartDocument](../writestartdocument/) již volán.

## Viz také

* Třída [String](../../../system/string/)
* Třída [XmlWriter](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)