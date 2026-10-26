---
title: LookupPrefix()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Vrací předponu deklarovanou pro zadané URI jmenného prostoru.
type: docs
weight: 417
url: /cs/system.xml.xpath/xpathnavigator/lookupprefix/
---
## XPathNavigator::LookupPrefix(const String\&) metoda

Vrací předponu deklarovanou pro zadané URI jmenného prostoru.

```cpp
String System::Xml::XPath::XPathNavigator::LookupPrefix(const String &namespaceURI) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| namespaceURI | const [String](../../../system/string/)\& | URI jmenného prostoru, které má být vyřešeno pro předponu. |

### Návratová hodnota

Objekt [String](../../../system/string/) obsahující předponu jmenného prostoru přiřazenou k zadanému URI jmenného prostoru; jinak [String::Empty](../../../system/string/empty/), pokud k zadanému URI jmenného prostoru není přiřazena žádná předpona. Vrácený [String](../../../system/string/) je atomizován.

## Viz také

* Třída [String](../../../system/string/)
* Třída [XPathNavigator](../)
* Jmenný prostor [System::Xml::XPath](../../)
* Knihovna [Aspose.Slides](../../../)