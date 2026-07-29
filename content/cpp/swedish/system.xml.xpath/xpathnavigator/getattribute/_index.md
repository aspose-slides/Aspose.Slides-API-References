---
title: GetAttribute()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar värdet på attributet med det angivna lokala namnet och namnrymdens URI.
type: docs
weight: 482
url: /sv/system.xml.xpath/xpathnavigator/getattribute/
---
## XPathNavigator::GetAttribute(String, String) metod


Returnerar värdet på attributet med det angivna lokala namnet och namnrymdens URI.

```cpp
virtual String System::Xml::XPath::XPathNavigator::GetAttribute(String localName, String namespaceURI)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Det lokala namnet på attributet. **localName** är skiftlägeskänsligt. |
| namespaceURI | [String](../../../system/string/) | Namnrymdens URI för attributet. |

### Returvärde

En [String](../../../system/string/) som innehåller värdet på det angivna attributet; [String::Empty](../../../system/string/empty/) om ett matchande attribut inte hittas, eller om [XPathNavigator](../) inte är placerad på en elementnod.

## Se också

* Klass [String](../../../system/string/)
* Klass [XPathNavigator](../)
* Namnrymd [System::Xml::XPath](../../)
* Bibliotek [Aspose.Slides](../../../)