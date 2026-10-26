---
title: get_Value()
second_title: Aspose.Slides pro C++ API Reference
description: Vrací textovou hodnotu aktuálního uzlu.
type: docs
weight: 79
url: /cs/system.xml/xmlnodereader/get_value/
---
## XmlNodeReader::get_Value() metoda


Vrací textovou hodnotu aktuálního uzlu.

```cpp
String System::Xml::XmlNodeReader::get_Value() override
```


### Návratová hodnota

Vrácená hodnota závisí na [XmlNodeReader::get_NodeType](../get_nodetype/) uzlu.
## Poznámky



Následující tabulka uvádí typy uzlů, které mají hodnotu k vrácení. Všechny ostatní typy uzlů vracejí [String::Empty](../../../system/string/empty/). 

| Typ uzlu | Hodnota |
| --- | --- |
| [Attribute](../../../system/attribute/)| Hodnota atributu. |
| CDATA| Obsah sekce CDATA. |
| Comment| Obsah komentáře. |
| DocumentType| Interní podmnožina. |
| ProcessingInstruction| Celý obsah, kromě cíle. |
| SignificantWhitespace| Bílý prostor mezi značkami v modelu smíšeného obsahu. |
| [Text](../../../system.text/)| Obsah textového uzlu. |
| Whitespace| Bílý prostor mezi značkami. |
| [XmlDeclaration](../../xmldeclaration/)| Obsah deklarace. |


## Viz také

* Třída [String](../../../system/string/)
* Třída [XmlNodeReader](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)