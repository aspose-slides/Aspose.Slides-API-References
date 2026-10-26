---
title: HasOperatorEqualsHelper()
second_title: Aspose.Slides voor C++ API-referentie
description: Helperfunctie om te bepalen of een specifieke klasse operator == heeft.
type: docs
weight: 235
url: /nl/system.collections.generic.details/hasoperatorequalshelper/
---
## System::Collections::Generic::Details::HasOperatorEqualsHelper(T *, T *) functie

Helperfunctie om te bepalen of een specifieke klasse operator == heeft.

```cpp
template<class T,typename Dummy> std::true_type System::Collections::Generic::Details::HasOperatorEqualsHelper(T *, T *)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Type om te controleren. |
| Dummy | Dummy-argument voor SFINAE-magic. |

### Retourwaarde

Waarde van std::true_type als operator == aanwezig is en anders false.

## System::Collections::Generic::Details::HasOperatorEqualsHelper(void *, void *) functie

Helperfunctie om te bepalen of een specifieke klasse operator == heeft.

```cpp
std::false_type System::Collections::Generic::Details::HasOperatorEqualsHelper(void *, void *)
```

### Retourwaarde

Waarde van std::true_type als operator == aanwezig is en anders false.

## Zie ook

* Naamruimte [System::Collections::Generic::Details](../)
* Bibliotheek [Aspose.Slides](../../)