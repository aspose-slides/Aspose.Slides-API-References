---
title: get_Value()
second_title: Aspose.Slides pro C++ API Reference
description: Vrací textovou hodnotu aktuálního uzlu.
type: docs
weight: 79
url: /cs/system.xml/xmlvalidatingreader/get_value/
---
## XmlValidatingReader::get_Value() metoda

Vrací textovou hodnotu aktuálního uzlu.

```cpp
String System::Xml::XmlValidatingReader::get_Value() override
```

### Návratová hodnota

Vrácená hodnota závisí na XmlValidatingReader::NodeType uzlu.

## Poznámky

Následující tabulka uvádí typy uzlů, které mají hodnotu k vrácení. Všechny ostatní typy uzlů vracejí [String::Empty](../../../system/string/empty/). 

| Typ uzlu | Hodnota |
| --- | --- |
| [Attribute](../../../system/attribute/)| Hodnota atributu. |
| CDATA| Obsah sekce CDATA. |
| Comment| Obsah komentáře. |
| DocumentType| Vnitřní podmnožina. |
| ProcessingInstruction| Celý obsah, kromě cíle. |
| SignificantWhitespace| Mezery mezi značkami v modelu smíšeného obsahu. |
| [Text](../../../system.text/)| Obsah textového uzlu. |
| Whitespace| Mezery mezi značkami. |
| [XmlDeclaration](../../xmldeclaration/)| Obsah deklarace. |

## Viz také

* Třída [String](../../../system/string/)
* Třída [XmlValidatingReader](../)
* Obor názvů [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)