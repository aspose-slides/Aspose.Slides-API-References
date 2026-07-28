---
title: LookupPrefix()
second_title: Aspose.Slides dla C++ - referencja API
description: Zwraca prefiks zadeklarowany dla określonego identyfikatora URI przestrzeni nazw.
type: docs
weight: 417
url: /pl/system.xml.xpath/xpathnavigator/lookupprefix/
---
## XPathNavigator::LookupPrefix(const String\&) metoda

Zwraca prefiks zadeklarowany dla określonego identyfikatora URI przestrzeni nazw.

```cpp
String System::Xml::XPath::XPathNavigator::LookupPrefix(const String &namespaceURI) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| namespaceURI | const [String](../../../system/string/)\& | Identyfikator URI przestrzeni nazw, dla którego ma zostać rozwiązany prefiks. |

### Return Value

[String](../../../system/string/) zawierający prefiks przestrzeni nazw przypisany do określonego identyfikatora URI przestrzeni nazw; w przeciwnym razie [String::Empty](../../../system/string/empty/), jeśli żaden prefiks nie jest przypisany do określonego identyfikatora URI przestrzeni nazw. Zwrócony [String](../../../system/string/) jest atomizowany.

## See Also

* Klasa [String](../../../system/string/)
* Klasa [XPathNavigator](../)
* Przestrzeń nazw [System::Xml::XPath](../../)
* Biblioteka [Aspose.Slides](../../../)