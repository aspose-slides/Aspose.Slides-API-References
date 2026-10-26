---
title: ReadString()
second_title: Aspose.Slides pro C++ API reference
description: Načte obsah elementu nebo textového uzlu jako řetězec.
type: docs
weight: 391
url: /cs/system.xml/xmlnodereader/readstring/
---
## XmlNodeReader::ReadString() metoda


Načte obsah elementu nebo textového uzlu jako řetězec.

```cpp
String System::Xml::XmlNodeReader::ReadString() override
```


### Návratová hodnota

Obsah elementu nebo textového uzlu (Může zahrnovat CDATA, [Text](../../../system.text/) uzly a tak dále). Může to být prázdný řetězec, pokud je čtečka umístěna na něco jiného než element nebo textový uzel, nebo pokud v aktuálním kontextu neexistuje žádný další textový obsah k vrácení. Poznámka: Textový uzel může být buď element, nebo textový uzel atributu.

## Viz také

* Třída [String](../../../system/string/)
* Třída [XmlNodeReader](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)