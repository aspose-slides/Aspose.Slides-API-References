---
title: XmlNodeType
second_title: Aspose.Slides pro C++ referenční příručka API
description: Určuje typ uzlu.
type: docs
weight: 833
url: /cs/system.xml/xmlnodetype/
---
## XmlNodeType enum

Určuje typ uzlu.

```cpp
enum class XmlNodeType
```

### Hodnoty

| Název | Hodnota | Popis |
| --- | --- | --- |
| None | 0 | Toto je vráceno [XmlReader](../xmlreader/), pokud nebyla zavolána metoda **Read**. |
| Element | 1 | Prvek (například **<item>**). |
| Attribute | 2 | Atribut (například **id='123'**). |
| Text | 3 | Textový obsah uzlu. Uzel [XmlNodeType::Text](./) nemůže mít žádné podřízené uzly. Může se objevit jako podřízený uzel uzlů [XmlNodeType::Attribute](./), [XmlNodeType::DocumentFragment](./), [XmlNodeType::Element](./) a [XmlNodeType::EntityReference](./). |
| CDATA | 4 | Sekce CDATA (například **my escaped text**). |
| EntityReference | 5 | Odkaz na entitu (například **&num;**). |
| Entity | 6 | Deklarace entity (například **<!ENTITY...>**). |
| ProcessingInstruction | 7 | Zpracovatelská instrukce (například **<?pi test?>**). |
| Comment | 8 | Komentář (například ****). |
| Document | 9 | Objekt dokumentu, který jako kořen stromu dokumentu poskytuje přístup k celému XML dokumentu. |
| DocumentType | 10 | Deklarace typu dokumentu, označená následujícím tagem (například **<!DOCTYPE...>**). |
| DocumentFragment | 11 | Fragment dokumentu. |
| Notation | 12 | Notace v deklaraci typu dokumentu (například **<!NOTATION...>**). |
| Whitespace | 13 | Bílý prostor mezi značkami. |
| SignificantWhitespace | 14 | Bílý prostor mezi značkami v modelu smíšeného obsahu nebo bílý prostor v rozsahu **xml:space=\"preserve\"**. |
| EndElement | 15 | Značka koncového elementu (například ****). |
| EndEntity | 16 | Vráceno, když [XmlReader](../xmlreader/) dosáhne konce nahrazení entity v důsledku volání [XmlReader::ResolveEntity](../xmlreader/resolveentity/). |
| XmlDeclaration | 17 | Deklarace XML (například **<?xml version='1.0'?>**). Uzel [XmlNodeType::XmlDeclaration](./) musí být prvním uzlem v dokumentu. Nemůže mít podřízené uzly. Je podřízeným uzlem uzlu [XmlNodeType::Document](./). Může mít atributy poskytující informace o verzi a kódování. |

## Viz také

* Jmenný prostor [System::Xml](../)
* Knihovna [Aspose.Slides](../../)