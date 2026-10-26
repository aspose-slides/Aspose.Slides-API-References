---
title: IsStartElement()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: "Volá XmlReader::MoveToContent a testuje, zda je aktuální uzel obsahu začátková značka nebo značka prázdného elementu."
type: docs
weight: 885
url: /cs/system.xml/xmlreader/isstartelement/
---
## XmlReader::IsStartElement() metoda


Volá [XmlReader::MoveToContent](../movetocontent/) a testuje, zda je aktuální uzel obsahu začátková značka nebo značka prázdného elementu.

```cpp
virtual bool System::Xml::XmlReader::IsStartElement()
```


### Návratová hodnota

**true** pokud [XmlReader::MoveToContent](../movetocontent/) najde začátkovou značku nebo značku prázdného elementu; **false** pokud byl nalezen typ uzlu jiný než [XmlNodeType::Element](../../xmlnodetype/).

## XmlReader::IsStartElement(String) metoda


Volá [XmlReader::MoveToContent](../movetocontent/) a testuje, zda je aktuální uzel obsahu začátková značka nebo značka prázdného elementu a zda hodnota [XmlReader::get_Name](../get_name/) nalezeného elementu odpovídá zadanému argumentu.

```cpp
virtual bool System::Xml::XmlReader::IsStartElement(String name)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| name | [String](../../../system/string/) | Řetězec porovnaný s hodnotou **Name** nalezeného elementu. |

### Návratová hodnota

**true** pokud je výsledný uzel element a hodnota **Name** odpovídá zadanému řetězci. **false** pokud byl nalezen typ uzlu jiný než [XmlNodeType::Element](../../xmlnodetype/) nebo pokud hodnota **Name** elementu neodpovídá zadanému řetězci.

## XmlReader::IsStartElement(String, String) metoda


Volá [XmlReader::MoveToContent](../movetocontent/) a testuje, zda je aktuální uzel obsahu začátková značka nebo značka prázdného elementu a zda hodnoty [XmlReader::get_LocalName](../get_localname/) a [XmlReader::get_NamespaceURI](../get_namespaceuri/) nalezeného elementu odpovídají zadaným řetězcům.

```cpp
virtual bool System::Xml::XmlReader::IsStartElement(String localname, String ns)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| localname | [String](../../../system/string/) | Řetězec, který se má porovnat s hodnotou **LocalName** nalezeného elementu. |
| ns | [String](../../../system/string/) | Řetězec, který se má porovnat s hodnotou **NamespaceURI** nalezeného elementu. |

### Návratová hodnota

**true** pokud je výsledný uzel element. **false** pokud byl nalezen typ uzlu jiný než [XmlNodeType::Element](../../xmlnodetype/) nebo pokud hodnoty **LocalName** a **NamespaceURI** elementu neodpovídají zadaným řetězcům.

## Viz také

* Třída [XmlReader](../)
* Třída [String](../../../system/string/)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)