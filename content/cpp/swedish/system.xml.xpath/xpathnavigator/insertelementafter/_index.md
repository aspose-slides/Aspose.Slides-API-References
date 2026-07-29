---
title: InsertElementAfter()
second_title: Aspose.Slides för C++ API-referens
description: Skapar ett nytt syskonelement efter den aktuella noden med det angivna namnrymdsprefixet, det lokala namnet och den angivna namnrymdens URI, med det angivna värdet.
type: docs
weight: 1028
url: /sv/system.xml.xpath/xpathnavigator/insertelementafter/
---
## XPathNavigator::InsertElementAfter(String, String, String, String) metod

Skapar ett nytt syskonelement efter den aktuella noden med det angivna namnrymdsprefixet, det lokala namnet och den angivna namnrymdens URI, med det angivna värdet.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertElementAfter(String prefix, String localName, String namespaceURI, String value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | Namnrymdsprefixet för det nya barn-elementet (om någon). |
| localName | [String](../../../system/string/) | Det lokala namnet för det nya barn-elementet (om någon). |
| namespaceURI | [String](../../../system/string/) | Namnrymdens URI för det nya barn-elementet (om någon). [String::Empty](../../../system/string/empty/) och **nullptr** är ekvivalenta. |
| value | [String](../../../system/string/) | Värdet för det nya barn-elementet. Om [String::Empty](../../../system/string/empty/) eller **nullptr** skickas, skapas ett tomt element. |

## Se även

* Klass [String](../../../system/string/)
* Klass [XPathNavigator](../)
* Namnrymd [System::Xml::XPath](../../)
* Bibliotek [Aspose.Slides](../../../)