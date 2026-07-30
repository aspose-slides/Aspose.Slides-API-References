---
title: WriteProcessingInstruction()
second_title: Aspose.Slides pro C++ API Reference
description: "Zapisuje instrukci zpracování s mezerou mezi názvem a textem takto: <?name text?>."
type: docs
weight: 326
url: /cs/system.xml/xmltextwriter/writeprocessinginstruction/
---
## XmlTextWriter::WriteProcessingInstruction(String, String) metoda


Zapisuje instrukci zpracování s mezerou mezi názvem a textem takto: **<?name text?>**.

```cpp
void System::Xml::XmlTextWriter::WriteProcessingInstruction(String name, String text) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| name | [String](../../../system/string/) | Název instrukce zpracování. |
| text | [String](../../../system/string/) | [Text](../../../system.text/) k zahrnutí do instrukce zpracování. |
## Poznámky



Tato metoda se používá k vytvoření deklarace XML po tom, co byla [XmlTextWriter::WriteStartDocument](../writestartdocument/) již volána. 
## Viz také

* Třída [String](../../../system/string/)
* Třída [XmlTextWriter](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)