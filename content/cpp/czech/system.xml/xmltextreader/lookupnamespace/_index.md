---
title: LookupNamespace()
second_title: Aspose.Slides pro C++ referenci API
description: Vyřeší prefix jmenného prostoru v rozsahu aktuálního elementu.
type: docs
weight: 612
url: /cs/system.xml/xmltextreader/lookupnamespace/
---
## XmlTextReader::LookupNamespace(const String\&) metoda


Vyřeší prefix jmenného prostoru v rozsahu aktuálního elementu.

```cpp
String System::Xml::XmlTextReader::LookupNamespace(const String &prefix) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Prefix, jehož URI jmenného prostoru chcete vyřešit. Pro shodu s výchozím jmenným prostorem předávejte prázdný řetězec. Tento řetězec není nutné atomizovat. |

### Návratová hodnota

URI jmenného prostoru, na který se prefix mapuje, nebo **nullptr**, pokud není nalezen odpovídající prefix.

## Viz také

* Třída [String](../../../system/string/)
* Třída [XmlTextReader](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)