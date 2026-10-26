---
title: get_Name()
second_title: Aspose.Slides pro C++ API Reference
description: Vrací plně kvalifikovaný název aktuálního uzlu.
type: docs
weight: 14
url: /cs/system.xml/xmlvalidatingreader/get_name/
---
## XmlValidatingReader::get_Name() metoda

Vrací plně kvalifikovaný název aktuálního uzlu.

```cpp
String System::Xml::XmlValidatingReader::get_Name() override
```

### Návratová hodnota

Plně kvalifikovaný název aktuálního uzlu. Například **Name** je **bk:book** pro prvek **<bk:book>**.

## Poznámky

Název, který je vrácen, závisí na XmlValidatingReader::NodeType uzlu. Následující typy uzlů vracejí uvedené hodnoty. Všechny ostatní typy uzlů vracejí prázdný řetězec.

| Typ uzlu | Název |
| --- | --- |
| [Attribute](../../../system/attribute/)| Název atributu. |
| DocumentType| Název typu dokumentu. |
| Element| Název značky. |
| EntityReference| Název odkazované entity. |
| ProcessingInstruction| Cíl instrukce zpracování. |
| [XmlDeclaration](../../xmldeclaration/)| Literální řetězec `xml`. |

## Viz také

* Třída [String](../../../system/string/)
* Třída [XmlValidatingReader](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)