---
title: LookupNamespace()
second_title: Aspose.Slides pro C++ API Reference
description: Vrátí URI jmenného prostoru pro zadaný prefix.
type: docs
weight: 404
url: /cs/system.xml.xpath/xpathnavigator/lookupnamespace/
---
## XPathNavigator::LookupNamespace(const String\&) metoda


Vrátí URI jmenného prostoru pro zadaný prefix.

```cpp
String System::Xml::XPath::XPathNavigator::LookupNamespace(const String &prefix) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Předpona, jejíž URI jmenného prostoru chcete vyřešit. Pro shodu s výchozím jmenným prostorem použijte [String::Empty](../../../system/string/empty/). |

### Návratová hodnota

Objekt [String](../../../system/string/), který obsahuje URI jmenného prostoru přiřazeného k zadané předponě; **nullptr**, pokud není žádné URI jmenného prostoru přiřazeno k zadané předponě. Vrácený [String](../../../system/string/) je atomizován.

## Viz také

* Třída [String](../../../system/string/)
* Třída [XPathNavigator](../)
* Jmenný prostor [System::Xml::XPath](../../)
* Knihovna [Aspose.Slides](../../../)