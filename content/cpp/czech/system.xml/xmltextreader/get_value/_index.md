---
title: get_Value()
second_title: Aspose.Slides pro C++ API Reference
description: Vrací textovou hodnotu aktuálního uzlu.
type: docs
weight: 79
url: /cs/system.xml/xmltextreader/get_value/
---
## XmlTextReader::get_Value() metoda


Vrací textovou hodnotu aktuálního uzlu.

```cpp
String System::Xml::XmlTextReader::get_Value() override
```


### Návratová hodnota

Vrácená hodnota závisí na hodnotě [XmlTextReader::get_NodeType](../get_nodetype/) uzlu.
## Poznámky



Následující tabulka uvádí typy uzlů, které mají hodnotu k vrácení. Všechny ostatní typy uzlů vracejí [String::Empty](../../../system/string/empty/). 

| Node Type | Value |
| --- | --- |
| [Attribute](../../../system/attribute/)| Hodnota atributu. |
| CDATA| Obsah sekce CDATA. |
| Comment| Obsah komentáře. |
| DocumentType| Vnitřní podmnožina. |
| ProcessingInstruction| Celý obsah, s výjimkou cíle. |
| SignificantWhitespace| Bílý prostor v rozsahu `xml:space='preserve'`. |
| [Text](../../../system.text/)| Obsah textového uzlu. |
| Whitespace| Bílý prostor mezi značkami. |
| [XmlDeclaration](../../xmldeclaration/)| Obsah deklarace. |


## Viz také

* Třída [String](../../../system/string/)
* Třída [XmlTextReader](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)