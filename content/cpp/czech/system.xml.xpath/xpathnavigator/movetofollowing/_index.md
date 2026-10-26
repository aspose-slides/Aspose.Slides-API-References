---
title: MoveToFollowing()
second_title: Aspose.Slides pro C++ API Reference
description: Přesune XPathNavigator na prvek s určeným lokálním názvem a URI jmenného prostoru v pořadí dokumentu.
type: docs
weight: 703
url: /cs/system.xml.xpath/xpathnavigator/movetofollowing/
---
## XPathNavigator::MoveToFollowing(String, String) metoda

Přesune [XPathNavigator](../) na prvek s určeným lokálním názvem a URI jmenného prostoru v pořadí dokumentu.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(String localName, String namespaceURI)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Lokální název prvku. |
| namespaceURI | [String](../../../system/string/) | URI jmenného prostoru prvku. |

### Návratová hodnota

**true** pokud se [XPathNavigator](../) úspěšně přesunul; jinak **false**.

## XPathNavigator::MoveToFollowing(String, String, SharedPtr\<XPathNavigator\>) metoda

Přesune [XPathNavigator](../) na prvek s určeným lokálním názvem a URI jmenného prostoru, až k určenému omezení, v pořadí dokumentu.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(String localName, String namespaceURI, SharedPtr<XPathNavigator> end)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Lokální název prvku. |
| namespaceURI | [String](../../../system/string/) | URI jmenného prostoru prvku. |
| end | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | Objekt [XPathNavigator](../) umístěný na hranici prvku, za kterou se aktuální [XPathNavigator](../) při hledání následujícího prvku nepřesune. |

### Návratová hodnota

**true** pokud se [XPathNavigator](../) úspěšně přesunul; jinak **false**.

## XPathNavigator::MoveToFollowing(XPathNodeType) metoda

Přesune [XPathNavigator](../) na následující prvek typu XPathNodeType v pořadí dokumentu.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(XPathNodeType type)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | XPathNodeType prvku. XPathNodeType nemůže být [XPathNodeType::Attribute](../../xpathnodetype/) nebo [XPathNodeType::Namespace](../../xpathnodetype/). |

### Návratová hodnota

**true** pokud se [XPathNavigator](../) úspěšně přesunul; jinak **false**.

## XPathNavigator::MoveToFollowing(XPathNodeType, SharedPtr\<XPathNavigator\>) metoda

Přesune [XPathNavigator](../) na následující prvek typu XPathNodeType, až k určenému omezení, v pořadí dokumentu.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(XPathNodeType type, SharedPtr<XPathNavigator> end)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | XPathNodeType prvku. XPathNodeType nemůže být [XPathNodeType::Attribute](../../xpathnodetype/) nebo [XPathNodeType::Namespace](../../xpathnodetype/). |
| end | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | Objekt [XPathNavigator](../) umístěný na hranici prvku, za kterou se aktuální [XPathNavigator](../) při hledání následujícího prvku nepřesune. |

### Návratová hodnota

**true** pokud se [XPathNavigator](../) úspěšně přesunul; jinak **false**.

## Viz také

* Výčet [XPathNodeType](../../xpathnodetype/)
* Definice typu [SharedPtr](../../../system/sharedptr/)
* Třída [String](../../../system/string/)
* Třída [XPathNavigator](../)
* Jmenný prostor [System::Xml::XPath](../../)
* Knihovna [Aspose.Slides](../../../)