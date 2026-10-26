---
title: AddNamespace()
second_title: Aspose.Slides för C++ API-referens
description: Lägger till den angivna namnrymden i samlingen.
type: docs
weight: 66
url: /sv/system.xml/xmlnamespacemanager/addnamespace/
---
## XmlNamespaceManager::AddNamespace(String, String) metod


Lägger till den angivna namnrymden i samlingen.

```cpp
virtual void System::Xml::XmlNamespaceManager::AddNamespace(String prefix, String uri)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | Prefixen som ska associeras med den namnrymd som läggs till. Använd [String::Empty](../../../system/string/empty/) för att lägga till en standardnamnrymd. Om [XmlNamespaceManager](../) kommer att användas för att lösa namnrymder i ett XML Path Language ([XPath](../../../system.xml.xpath/))-uttryck, måste en prefix specificeras. Om ett [XPath](../../../system.xml.xpath/)-uttryck inte innehåller ett prefix, antas att namnrymdens Uniform Resource Identifier (URI) är den tomma namnrymden. För mer information om [XPath](../../../system.xml.xpath/)-uttryck och [XmlNamespaceManager](../), se metoderna XmlNode::SelectNodes(String) och XPathExpression::SetContext(SharedPtr<XmlNamespaceManager>). |
| uri | [String](../../../system/string/) | Namnrymden att lägga till. |

## Se också

* Klass [String](../../../system/string/)
* Klass [XmlNamespaceManager](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)