---
title: has_print_to_method
second_title: Aspose.Slides für C++ API-Referenz
description: "Überprüft, ob es eine Überladung der PrintTo-Funktion gibt, die den angegebenen Typ als erstes Argument akzeptiert. Wenn eine Überladung existiert, erbt std::true_type, andernfalls erbt std::false_type."
type: docs
weight: 27
url: /de/system.testpredicates.typetraits/has_print_to_method/
---
## has_print_to_method struct

Überprüft, ob es eine Überladung der PrintTo-Funktion gibt, die den angegebenen Typ als erstes Argument akzeptiert. Wenn eine Überladung existiert, erbt std::true_type, andernfalls erbt std::false_type.

```cpp
template<typename T,typename Enable>class has_print_to_method : public std::false_type
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Typ zum Prüfen. |
| Enable | Formales Argument, damit SFINAE funktioniert. |

## Siehe auch

* Namensraum [System::TestPredicates::TypeTraits](../)
* Bibliothek [Aspose.Slides](../../)