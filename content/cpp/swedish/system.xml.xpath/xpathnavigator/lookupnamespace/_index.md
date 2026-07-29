---
title: LookupNamespace()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar namnrymdens URI för det angivna prefixet.
type: docs
weight: 404
url: /sv/system.xml.xpath/xpathnavigator/lookupnamespace/
---
## XPathNavigator::LookupNamespace(const String\&) metod

Returnerar namnrymdens URI för det angivna prefixet.

```cpp
String System::Xml::XPath::XPathNavigator::LookupNamespace(const String &prefix) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Prefixet vars namnrymds-URI du vill lösa. För att matcha standardnamnrymden, skicka [String::Empty](../../../system/string/empty/). |

### Returvärde

En [String](../../../system/string/) som innehåller namnrymdens URI som tilldelats det angivna namnrymdsprefixet; **nullptr** om ingen namnrymds-URI är tilldelad det angivna prefixet. Den returnerade [String](../../../system/string/) är atomiserad.

## Se också

* Klass [String](../../../system/string/)
* Klass [XPathNavigator](../)
* Namnrymd [System::Xml::XPath](../../)
* Bibliotek [Aspose.Slides](../../../)