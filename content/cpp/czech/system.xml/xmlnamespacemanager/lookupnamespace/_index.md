---
title: LookupNamespace()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Vrací URI jmenného prostoru pro zadaný prefix.
type: docs
weight: 118
url: /cs/system.xml/xmlnamespacemanager/lookupnamespace/
---
## XmlNamespaceManager::LookupNamespace(const String\&) metoda

Vrátí URI jmenného prostoru pro zadaný prefix.

```cpp
String System::Xml::XmlNamespaceManager::LookupNamespace(const String &prefix) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Prefix, jehož URI jmenného prostoru chcete vyřešit. Pro shodu s výchozím jmenným prostorem předávejte [String::Empty](../../../system/string/empty/). |

### Návratová hodnota

URI jmenného prostoru pro **prefix** nebo **nullptr**, pokud neexistuje přiřazený jmenný prostor. Vrácený řetězec je atomizovaný. Další informace o atomizovaných řetězcích naleznete ve třídě [XmlNameTable](../../xmlnametable/).

## Viz také

* Třída [String](../../../system/string/)
* Třída [XmlNamespaceManager](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)