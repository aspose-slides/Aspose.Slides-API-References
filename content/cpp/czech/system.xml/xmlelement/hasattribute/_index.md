---
title: HasAttribute()
second_title: Aspose.Slides pro C++ – referenční dokumentace API
description: Určuje, zda aktuální uzel má atribut se zadaným názvem.
type: docs
weight: 300
url: /cs/system.xml/xmlelement/hasattribute/
---
## XmlElement::HasAttribute(String) metoda

Určuje, zda aktuální uzel má atribut se zadaným názvem.

```cpp
virtual bool System::Xml::XmlElement::HasAttribute(String name)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| name | [String](../../../system/string/) | Název atributu, který se má najít. Jedná se o kvalifikovaný název. Je porovnáván s hodnotou **get_Name** odpovídajícího uzlu. |

### Návratová hodnota

**true** pokud aktuální uzel má zadaný atribut; jinak **false**.

## XmlElement::HasAttribute(String, String) metoda

Určuje, zda aktuální uzel má atribut se zadaným místním názvem a URI jmenného prostoru.

```cpp
virtual bool System::Xml::XmlElement::HasAttribute(String localName, String namespaceURI)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Místní název atributu, který se má najít. |
| namespaceURI | [String](../../../system/string/) | URI jmenného prostoru atributu, který se má najít. |

### Návratová hodnota

**true** pokud aktuální uzel má zadaný atribut; jinak **false**.

## Viz také

* Třída [String](../../../system/string/)
* Třída [XmlElement](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)