---
title: UnknownIsNull()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Sprawdza, czy obiekt nieznanego typu jest nullptr. Przeciążenie dla typów nieskalarowych.
type: docs
weight: 144
url: /pl/system/objectext/unknownisnull/
---
## ObjectExt::UnknownIsNull(T) metoda


Sprawdza, czy obiekt nieznanego typu jest nullptr. Przeciążenie dla typów nieskalarowych.

```cpp
template<typename T> static std::enable_if<!std::is_scalar<T>::value, bool>::type System::ObjectExt::UnknownIsNull(T obj)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | [Object](../../object/) typ. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | T | [Object](../../object/) do sprawdzenia. |

### Wartość zwracana

Prawda, jeśli 'obj == nullptr' jest prawdziwe, w przeciwnym razie fałsz.

## ObjectExt::UnknownIsNull(T) metoda


Sprawdza, czy obiekt nieznanego typu jest nullptr. Przeciążenie dla typów skalarowych.

```cpp
template<typename T> static std::enable_if<std::is_scalar<T>::value, bool>::type System::ObjectExt::UnknownIsNull(T obj)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | [Object](../../object/) typ. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | T | [Object](../../object/) do sprawdzenia. |

### Wartość zwracana

Zawsze zwraca fałsz.

## Zobacz także

* Klasa [ObjectExt](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)