---
title: MoveToNext()
second_title: Aspose.Slides för C++ API-referens
description: När den åsidosätts i en avledd klass, flyttar den XPathNavigator till nästa syskonnod till den aktuella noden.
type: docs
weight: 586
url: /sv/system.xml.xpath/xpathnavigator/movetonext/
---
## XPathNavigator::MoveToNext() metod


När den åsidosätts i en avledd klass, flyttar [XPathNavigator](../) till nästa syskonnod till den aktuella noden.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNext()=0
```


### Returvärde

**true** om [XPathNavigator](../) lyckas flytta till nästa syskonnod; annars **false** om det inte finns fler syskon eller om [XPathNavigator](../) för närvarande är placerad på en attributnod. Om **false**, förblir positionen för [XPathNavigator](../) oförändrad.

## XPathNavigator::MoveToNext(String, String) metod


Flyttar [XPathNavigator](../) till nästa syskonnod med det lokala namnet och namnrymds-URI:n som anges.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNext(String localName, String namespaceURI)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Det lokala namnet på nästa syskonnod att flytta till. |
| namespaceURI | [String](../../../system/string/) | Namnområdets URI för nästa syskonnod att flytta till. |

### Returvärde

**true** om [XPathNavigator](../) lyckas flytta till nästa syskonnod; **false** om det inte finns fler syskon, eller om [XPathNavigator](../) för närvarande är placerad på en attributnod. Om **false**, förblir positionen för [XPathNavigator](../) oförändrad.

## XPathNavigator::MoveToNext(XPathNodeType) metod


Flyttar [XPathNavigator](../) till nästa syskonnod till den aktuella noden som matchar den angivna XPathNodeType.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNext(XPathNodeType type)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | XPathNodeType för syskonnoden att flytta till. |

### Returvärde

**true** om [XPathNavigator](../) lyckas flytta till nästa syskonnod; annars **false** om det inte finns fler syskon eller om [XPathNavigator](../) för närvarande är placerad på en attributnod. Om **false**, förblir positionen för [XPathNavigator](../) oförändrad.

## Se även

* Enum [XPathNodeType](../../xpathnodetype/)
* Klass [XPathNavigator](../)
* Klass [String](../../../system/string/)
* Namnrymd [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)