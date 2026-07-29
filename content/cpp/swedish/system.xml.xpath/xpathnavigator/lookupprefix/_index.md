---
title: LookupPrefix()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar prefixet som deklarerats för den angivna namnrymd-URI:n.
type: docs
weight: 417
url: /sv/system.xml.xpath/xpathnavigator/lookupprefix/
---
## XPathNavigator::LookupPrefix(const String\&) metod

Returnerar prefixet som deklarerats för den angivna namnrymd-URI:n.

```cpp
String System::Xml::XPath::XPathNavigator::LookupPrefix(const String &namespaceURI) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namespaceURI | const [String](../../../system/string/)\& | Namnrymd-URI:n som ska lösas för prefixet. |

### Returvärde

Ett [String](../../../system/string/) som innehåller namnrymdsprefixet som tilldelats den angivna namnrymd-URI:n; annars [String::Empty](../../../system/string/empty/) om inget prefix har tilldelats den angivna namnrymd-URI:n. Den returnerade [String](../../../system/string/) är atomiserad.

## Se även

* Klass [String](../../../system/string/)
* Klass [XPathNavigator](../)
* Namnrymd [System::Xml::XPath](../../)
* Bibliotek [Aspose.Slides](../../../)