---
title: MoveToFirst()
second_title: Aspose.Slides för C++ API-referens
description: Flyttar XPathNavigator till den första syskonnoden för den aktuella noden.
type: docs
weight: 612
url: /sv/system.xml.xpath/xpathnavigator/movetofirst/
---
## XPathNavigator::MoveToFirst() method


Flyttar [XPathNavigator](../) till den första syskonnoden för den aktuella noden.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFirst()
```


### Returvärde

**true** om [XPathNavigator](../) lyckas att flytta till den första syskonnoden för den aktuella noden; **false** om det inte finns någon första syskon, eller om [XPathNavigator](../) för närvarande är placerad på en attributnod. Om [XPathNavigator](../) redan är placerad på den första syskonen, kommer [XPathNavigator](../) att returnera **true** och kommer inte att ändra sin position. Om [XPathNavigator::MoveToFirst](./) returnerar **false** eftersom det inte finns någon första syskon, eller om [XPathNavigator](../) för närvarande är placerad på ett attribut, förblir positionen för [XPathNavigator](../) oförändrad.

## Se även

* Klass [XPathNavigator](../)
* Namnrymd [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)