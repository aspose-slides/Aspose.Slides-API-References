---
title: AppendChildElement()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en ny underordnad elementnod i slutet av listan med underordnade noder för den aktuella noden med hjälp av namnrymdsprefixet, det lokala namnet och namnrymds-URI:n som anges tillsammans med det specificerade värdet.
type: docs
weight: 1002
url: /sv/system.xml.xpath/xpathnavigator/appendchildelement/
---
## XPathNavigator::AppendChildElement(String, String, String, String) metod

Skapar en ny underordnad elementnod i slutet av listan med underordnade noder för den aktuella noden med hjälp av namnrymdsprefixet, det lokala namnet och namnrymds-URI:n som anges tillsammans med det specificerade värdet.

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChildElement(String prefix, String localName, String namespaceURI, String value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | Namnrymdsprefixet för den nya underordnade elementnoden (om någon). |
| localName | [String](../../../system/string/) | Det lokala namnet för den nya underordnade elementnoden (om någon). |
| namespaceURI | [String](../../../system/string/) | Namnrymds-URI:n för den nya underordnade elementnoden (om någon). [String::Empty](../../../system/string/empty/) och **nullptr** är ekvivalenta. |
| value | [String](../../../system/string/) | Värdet för den nya underordnade elementnoden. Om [String::Empty](../../../system/string/empty/) eller **nullptr** skickas, skapas ett tomt element. |

## Se också

* Klass [String](../../../system/string/)
* Klass [XPathNavigator](../)
* Namnrymd [System::Xml::XPath](../../)
* Bibliotek [Aspose.Slides](../../../)