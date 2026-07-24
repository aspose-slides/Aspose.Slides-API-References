---
title: HasOperatorEqualsHelper()
second_title: Aspose.Slides für C++ API-Referenz
description: Hilfsfunktion, um zu bestimmen, ob die spezifische Klasse den Operator == hat.
type: docs
weight: 235
url: /de/system.collections.generic.details/hasoperatorequalshelper/
---
## System::Collections::Generic::Details::HasOperatorEqualsHelper(T *, T *) Funktion

Hilfsfunktion, um zu bestimmen, ob die spezifische Klasse den Operator == hat.

```cpp
template<class T,typename Dummy> std::true_type System::Collections::Generic::Details::HasOperatorEqualsHelper(T *, T *)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Typ, der überprüft werden soll. |
| Dummy | Dummy-Argument für SFINAE-Magie. |

### Rückgabewert

Wert von std::true_type, wenn operator == vorhanden ist, andernfalls false.

## System::Collections::Generic::Details::HasOperatorEqualsHelper(void *, void *) Funktion

Hilfsfunktion, um zu bestimmen, ob die spezifische Klasse den Operator == hat.

```cpp
std::false_type System::Collections::Generic::Details::HasOperatorEqualsHelper(void *, void *)
```

### Rückgabewert

Wert von std::true_type, wenn operator == vorhanden ist, andernfalls false.

## Siehe auch

* Namensraum [System::Collections::Generic::Details](../)
* Bibliothek [Aspose.Slides](../../)