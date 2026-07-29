---
title: CreateAttribute()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en attributnod på det aktuella elementnoden med hjälp av namnrymdsprefixet, det lokala namnet och namnrymds-URI:n som angivits med det angivna värdet.
type: docs
weight: 1041
url: /sv/system.xml.xpath/xpathnavigator/createattribute/
---
## XPathNavigator::CreateAttribute(String, String, String, String) metod

Skapar en attributnod på det aktuella elementnoden med hjälp av namnrymdsprefixet, det lokala namnet och namnrymds-URI:n som angivits med det angivna värdet.

```cpp
virtual void System::Xml::XPath::XPathNavigator::CreateAttribute(String prefix, String localName, String namespaceURI, String value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | Namnrymdsprefixet för den nya attributnoden (om någon). |
| localName | [String](../../../system/string/) | Det lokala namnet på den nya attributnoden som inte kan [String::Empty](../../../system/string/empty/) eller **nullptr**. |
| namespaceURI | [String](../../../system/string/) | Namnrymds-URI:n för den nya attributnoden (om någon). |
| value | [String](../../../system/string/) | Värdet på den nya attributnoden. Om [String::Empty](../../../system/string/empty/) eller **nullptr** skickas, skapas en tom attributnod. |

## Se även

* Klass [String](../../../system/string/)
* Klass [XPathNavigator](../)
* Namnrymd [System::Xml::XPath](../../)
* Bibliotek [Aspose.Slides](../../../)