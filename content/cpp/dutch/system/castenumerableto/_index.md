---
title: CastEnumerableTo()
second_title: Aspose.Slides voor C++ API-referentie
description: Voert de expliciete cast uit van elementen van het opgegeven enumerable-object naar een ander type.
type: docs
weight: 2965
url: /nl/system/castenumerableto/
---
## System::CastEnumerableTo(const From\&) functie

Voert de expliciete cast van elementen van het opgegeven enumerate-object uit naar een ander type.

```cpp
template<class To,class From> std::enable_if<!System::detail::has_method_get_Count<From>::value, Collections::Generic::ListPtr<To>>::type System::CastEnumerableTo(const From &enumerable)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| To | Het type waarnaar de elementen van het enumerate-object statisch gecast worden |
| From | Het type van het enumerate-object |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| enumerable | const From\& | Enumerate-object met de elementen die gecast moeten worden |

### Retourwaarde

Een pointer naar een nieuwe collectie met elementen van type **To** gelijk aan de elementen van **enumerable**

## System::CastEnumerableTo(const From\&) functie

Voert de expliciete cast van elementen van het opgegeven enumerate-object uit naar een ander type.

```cpp
template<class To,class From> std::enable_if<System::detail::has_method_get_Count<From>::value, Collections::Generic::ListPtr<To>>::type System::CastEnumerableTo(const From &enumerable)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| To | Het type waarnaar de elementen van het enumerate-object statisch gecast worden |
| From | Het type van het enumerate-object |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| enumerable | const From\& | is een afstammeling van Enumerable-object met een gedefinieerde get_Count-methode en bevat de te casten elementen |

### Retourwaarde

Een pointer naar een nieuwe collectie met elementen van type **To** gelijk aan de elementen van **enumerable**

## Zie ook

* Klasse [ListPtr](../../system.collections.generic/listptr/)
* Naamruimte [System](../)
* Bibliotheek [Aspose.Slides](../../)