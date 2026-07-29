---
title: MoveToChild()
second_title: Aspose.Slides för C++ API-referens
description: Flyttar XPathNavigator till barnnoden med det angivna lokala namnet och namnrymdens URI.
type: docs
weight: 690
url: /sv/system.xml.xpath/xpathnavigator/movetochild/
---
## XPathNavigator::MoveToChild(String, String) metod


Flyttar [XPathNavigator](../) till barnnoden med det angivna lokala namnet och namnrymdens URI.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToChild(String localName, String namespaceURI)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Det lokala namnet på barnnoden att flytta till. |
| namespaceURI | [String](../../../system/string/) | Namnrymdens URI för barnnoden att flytta till. |

### Returvärde

**true** om [XPathNavigator](../) lyckas flytta till barnnoden; annars **false**. Om **false** förblir positionen för [XPathNavigator](../) oförändrad.

## XPathNavigator::MoveToChild(XPathNodeType) metod


Flyttar [XPathNavigator](../) till barnnoden för den angivna XPathNodeType.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToChild(XPathNodeType type)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | XPathNodeType för barnnoden att flytta till. |

### Returvärde

**true** om [XPathNavigator](../) lyckas flytta till barnnoden; annars **false**. Om **false** förblir positionen för [XPathNavigator](../) oförändrad.

## Se även

* Enum [XPathNodeType](../../xpathnodetype/)
* Klass [String](../../../system/string/)
* Klass [XPathNavigator](../)
* Namnrymd [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)