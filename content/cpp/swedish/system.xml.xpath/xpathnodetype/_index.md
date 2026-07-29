---
title: XPathNodeType
second_title: Aspose.Slides för C++ API-referens
description: Definierar XPath-nodtyperna som kan returneras från klassen XPathNavigator.
type: docs
weight: 157
url: /sv/system.xml.xpath/xpathnodetype/
---
## XPathNodeType enum

Definierar de [XPath](../) nodtyper som kan returneras från klassen [XPathNavigator](../xpathnavigator/).

```cpp
enum class XPathNodeType
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Root | 0 | Rotnoden i XML-dokumentet eller nodträdet. |
| Element | 1 | Ett element, till exempel **<element>**. |
| Attribute | 2 | Ett attribut, till exempel **id='123'**. |
| Namespace | 3 | Ett namnrymd, till exempel **xmlns=\"namespace\"**. |
| Text | 4 | Textinnehållet i en nod. Motsvarar Document [Object](../../system/object/) Model (DOM) [Text](../../system.text/) och CDATA-nodtyper. Innehåller minst ett tecken. |
| SignificantWhitespace | 5 | En nod med blankstegstecken och **xml:space** satt till **preserve**. |
| Whitespace | 6 | En nod med endast blankstegstecken och ingen betydelsefull blanksteg. Blankstegstecken är **'\x20'**, **'\x0d'**, **'\x0a'**, **'\x09'**. |
| ProcessingInstruction | 7 | En processinstruktion, till exempel **<?pi test?>**. Detta inkluderar inte XML-deklarationer, som inte är synliga för klassen [XPathNavigator](../xpathnavigator/). |
| Comment | 8 | En kommentar, till exempel ****. |
| All | 9 | Alla XPathNodeType-nodtyper. |

## Se också

* Namespace [System::Xml::XPath](../)
* Library [Aspose.Slides](../../)