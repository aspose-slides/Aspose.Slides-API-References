---
title: IsCppContainer
second_title: Aspose.Slides für C++ API-Referenz
description: "Überprüft, ob ein bestimmter Typ ein STL-ähnlicher Container ist. Dazu wird geprüft, ob die Membertypen iterator und const_iterator existieren. Wenn beide existieren, erbt es von std::true_type, andernfalls erbt es von std::false_type."
type: docs
weight: 40
url: /de/system.testpredicates.typetraits/iscppcontainer/
---
## IsCppContainer Struktur

Überprüft, ob ein bestimmter Typ ein STL-ähnlicher Container ist. Dazu wird geprüft, ob die Membertypen iterator und const_iterator existieren. Wenn beide existieren, erbt es von std::true_type, andernfalls erbt es von std::false_type.

```cpp
template<typename T,typename Enable>class IsCppContainer : public std::false_type
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Typ, der geprüft werden soll. |
| Enable | Formales Argument, damit SFINAE funktioniert. |

## Siehe auch

* Namensraum [System::TestPredicates::TypeTraits](../)
* Bibliothek [Aspose.Slides](../../)