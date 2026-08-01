---
title: Equals()
second_title: Aspose.Slides voor C++ API-referentie
description: Bepaalt de gelijkheid van de opgegeven waarde met behulp van operator==().
type: docs
weight: 66
url: /nl/system.boxedvaluedetail/equals/
---
## System::BoxedValueDetail::Equals(T, T) functie

Bepaalt de gelijkheid van de opgegeven waarde met behulp van [operator==()](../../system/operator_equal_equal/).

```cpp
template<typename T> std::enable_if<detail::has_operator_equal<T>::value, bool>::type System::BoxedValueDetail::Equals(T value1, T value2)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| De | type van de te vergelijken waarden |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value1 | T | De eerste te vergelijken waarde |
| value2 | T | De tweede te vergelijken waarde |

### Retourwaarde

True als de opgegeven waarden gelijk zijn zoals bepaald door [operator==()](../../system/operator_equal_equal/), anders - false

## System::BoxedValueDetail::Equals(T, T) functie

Bepaalt de gelijkheid van de opgegeven waarde met methode [System::Object::Equals()](../../system/object/equals/).

```cpp
template<typename T> std::enable_if<detail::has_only_method_equals<T>::value, bool>::type System::BoxedValueDetail::Equals(T value1, T value2)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| De | type van de te vergelijken waarden |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value1 | T | De eerste te vergelijken waarde |
| value2 | T | De tweede te vergelijken waarde |

### Retourwaarde

True als de opgegeven waarden gelijk zijn zoals bepaald door methode [Equals()](./), anders - false

## Zie ook

* Naamruimte [System::BoxedValueDetail](../)
* Bibliotheek [Aspose.Slides](../../)