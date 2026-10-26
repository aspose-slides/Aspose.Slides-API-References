---
title: PrependChildElement()
second_title: Aspose.Slides för C++ API-referens
description: Skapar ett nytt underordnat element i början av listan med underordnade noder för den aktuella noden med hjälp av namnrymdsprefixet, det lokala namnet och namnrymds-URI:n som anges med det angivna värdet.
type: docs
weight: 989
url: /sv/system.xml.xpath/xpathnavigator/prependchildelement/
---
## XPathNavigator::PrependChildElement(String, String, String, String) metod


Skapar ett nytt underordnat element i början av listan med underordnade noder för den aktuella noden med hjälp av namnrymdsprefixet, det lokala namnet och namnrymds-URI:n som anges med det angivna värdet.

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChildElement(String prefix, String localName, String namespaceURI, String value)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | Namnrymdsprefixet för det nya underordnade elementet (om någon). |
| localName | [String](../../../system/string/) | Det lokala namnet på det nya underordnade elementet (om någon). |
| namespaceURI | [String](../../../system/string/) | Namnrymds-URI:n för det nya underordnade elementet (om någon). [String::Empty](../../../system/string/empty/) och **nullptr** är ekvivalenta. |
| value | [String](../../../system/string/) | Värdet för det nya underordnade elementet. Om [String::Empty](../../../system/string/empty/) eller **nullptr** skickas, skapas ett tomt element. |

## Se även

* Klass [String](../../../system/string/)
* Klass [XPathNavigator](../)
* Namnrymd [System::Xml::XPath](../../)
* Bibliotek [Aspose.Slides](../../../)