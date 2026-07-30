---
title: MoveToChild()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Přesune XPathNavigator na podřízený uzel se zadaným lokálním názvem a URI jmenného prostoru.
type: docs
weight: 690
url: /cs/system.xml.xpath/xpathnavigator/movetochild/
---
## XPathNavigator::MoveToChild(String, String) metoda

Přesune [XPathNavigator](../) do podřízeného uzlu se zadaným lokálním názvem a URI jmenného prostoru.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToChild(String localName, String namespaceURI)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Lokální název podřízeného uzlu, na který se má přesunout. |
| namespaceURI | [String](../../../system/string/) | URI jmenného prostoru podřízeného uzlu, na který se má přesunout. |

### Návratová hodnota

**true** pokud je [XPathNavigator](../) úspěšný při přesunu do podřízeného uzlu; jinak **false**. Pokud je **false**, pozice [XPathNavigator](../) zůstává beze změny.

## XPathNavigator::MoveToChild(XPathNodeType) metoda

Přesune [XPathNavigator](../) do podřízeného uzlu určeného typu XPathNodeType.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToChild(XPathNodeType type)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | Typ XPathNodeType podřízeného uzlu, na který se má přesunout. |

### Návratová hodnota

**true** pokud je [XPathNavigator](../) úspěšný při přesunu do podřízeného uzlu; jinak **false**. Pokud je **false**, pozice [XPathNavigator](../) zůstává beze změny.

## Viz také

* Enum [XPathNodeType](../../xpathnodetype/)
* Třída [String](../../../system/string/)
* Třída [XPathNavigator](../)
* Jmenný prostor [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)