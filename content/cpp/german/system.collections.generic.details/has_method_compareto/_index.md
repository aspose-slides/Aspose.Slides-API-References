---
title: has_method_compareto
second_title: Aspose.Slides für C++ API-Referenz
description: "Überprüft, ob die CompareTo-Methode im angegebenen Typ vorhanden ist. Falls ja, erbt std::true_type, andernfalls erbt std::false_type. Kann in std::enable_if verwendet werden."
type: docs
weight: 170
url: /de/system.collections.generic.details/has_method_compareto/
---
## has_method_compareto struct

Überprüft, ob die CompareTo-Methode im angegebenen Typ vorhanden ist. Falls ja, erbt std::true_type, andernfalls erbt std::false_type. Kann in std::enable_if verwendet werden.

```cpp
template<typename T,typename Sfinae>class has_method_compareto : public std::false_type
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Typ, um das Vorhandensein der Equals-Methode zu prüfen. |
| Sfinae | Formales Template-Argument, damit SFINAE funktioniert. |

## Siehe auch

* Namensraum [System::Collections::Generic::Details](../)
* Bibliothek [Aspose.Slides](../../)