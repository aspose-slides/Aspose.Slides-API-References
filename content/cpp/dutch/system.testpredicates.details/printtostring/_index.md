---
title: PrintToString()
second_title: Aspose.Slides voor C++ API-referentie
description: Printt object naar string door de juiste serializer-functie te selecteren.
type: docs
weight: 1
url: /nl/system.testpredicates.details/printtostring/
---
## System::TestPredicates::Details::PrintToString(const T\&) functie

Printt object naar string door de juiste serializer-functie te selecteren.

```cpp
template<typename T> std::enable_if_t<!TypeTraits::IsEnumerable<T>::value, std::string> System::TestPredicates::Details::PrintToString(const T &value)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) om af te drukken. |

### Retourwaarde

[String](../../system/string/) representaties van het doorgegeven object.

## System::TestPredicates::Details::PrintToString(const T\&) functie

Printt ICollection-stijl containers naar string door hun elementen af te drukken (maximaal 32).

```cpp
template<typename T> std::enable_if_t<TypeTraits::IsEnumerable<T>::value, std::string> System::TestPredicates::Details::PrintToString(const T &value)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) om af te drukken. |

### Retourwaarde

Samengevoegde stringrepresentaties van de bevatte elementen.

## System::TestPredicates::Details::PrintToString(std::nullptr_t) functie

Printt nullptr naar string.

```cpp
std::string System::TestPredicates::Details::PrintToString(std::nullptr_t)
```

### Retourwaarde

"nullptr"-string.

## System::TestPredicates::Details::PrintToString(const Collections::Generic::IEnumerable\<bool\>\&) functie

Printt [IEnumerable<bool>](../../system.collections.generic/ienumerable/)-collecties naar string door hun elementen af te drukken (maximaal 32).

```cpp
std::string System::TestPredicates::Details::PrintToString(const Collections::Generic::IEnumerable<bool> &value)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<**bool**\>\& | [Object](../../system/object/) om af te drukken. |

### Retourwaarde

Samengevoegde stringrepresentaties van de bevatte elementen.

## Zie ook

* Klasse [IEnumerable](../../system.collections.generic/ienumerable/)
* Struct [IsEnumerable](../../system.testpredicates.typetraits/isenumerable/)
* Naamruimte [System::TestPredicates::Details](../)
* Library [Aspose.Slides](../../)