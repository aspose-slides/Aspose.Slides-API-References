---
title: MoveToNext()
second_title: Aspose.Slides pro C++ – reference API
description: Když je přepsána v odvozené třídě, přesune XPathNavigator na následující sourozenecký uzel aktuálního uzlu.
type: docs
weight: 586
url: /cs/system.xml.xpath/xpathnavigator/movetonext/
---
## XPathNavigator::MoveToNext() metoda


Když je přepsána v odvozené třídě, přesune [XPathNavigator](../) na následující sourozenecký uzel aktuálního uzlu.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNext()=0
```


### Návratová hodnota

**true** pokud je [XPathNavigator](../) úspěšné při přesunu na další sourozenecký uzel; jinak **false**, pokud neexistují další sourozenci nebo pokud je [XPathNavigator](../) aktuálně umístěn na uzlu atributu. Pokud **false**, pozice [XPathNavigator](../) zůstane nezměněna.

## XPathNavigator::MoveToNext(String, String) metoda


Přesune [XPathNavigator](../) na další sourozenecký uzel s určeným lokálním názvem a URI jmenného prostoru.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNext(String localName, String namespaceURI)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Lokální název dalšího sourozeneckého uzlu, na který se má přesunout. |
| namespaceURI | [String](../../../system/string/) | URI jmenného prostoru dalšího sourozeneckého uzlu, na který se má přesunout. |

### Návratová hodnota

**true** pokud je [XPathNavigator](../) úspěšné při přesunu na další sourozenecký uzel; **false**, pokud neexistují další sourozenci nebo pokud je [XPathNavigator](../) aktuálně umístěn na uzlu atributu. Pokud **false**, pozice [XPathNavigator](../) zůstane nezměněna.

## XPathNavigator::MoveToNext(XPathNodeType) metoda


Přesune [XPathNavigator](../) na další sourozenecký uzel aktuálního uzlu, který odpovídá zadanému XPathNodeType.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNext(XPathNodeType type)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | XPathNodeType sourozeneckého uzlu, na který se má přesunout. |

### Návratová hodnota

**true** pokud je [XPathNavigator](../) úspěšné při přesunu na další sourozenecký uzel; jinak **false**, pokud neexistují další sourozenci nebo pokud je [XPathNavigator](../) aktuálně umístěn na uzlu atributu. Pokud **false**, pozice [XPathNavigator](../) zůstane nezměněna.

## Viz také

* Enum [XPathNodeType](../../xpathnodetype/)
* Třída [XPathNavigator](../)
* Třída [String](../../../system/string/)
* Jmenný prostor [System::Xml::XPath](../../)
* Knihovna [Aspose.Slides](../../../)