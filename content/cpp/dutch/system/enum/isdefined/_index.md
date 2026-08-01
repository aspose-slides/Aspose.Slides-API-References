---
title: IsDefined()
second_title: Aspose.Slides voor C++ API-referentie
description: Bepaalt of de opgegeven waarde een lid is van enumeratietype E.
type: docs
weight: 27
url: /nl/system/enum/isdefined/
---
## Enum::IsDefined(E) methode


Bepaalt of de opgegeven waarde een lid is van enumeratietype **E**.

```cpp
static bool System::Enum<E, Guard>::IsDefined(E value)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | E | De te controleren waarde |

### Retourwaarde

True als **value** een lid is van enumeratie **E**, anders - false

## Enum::IsDefined(T) methode


Bepaalt of de opgegeven waarde een lid is van enumeratietype **T**.

```cpp
template<class T> static std::enable_if<std::is_convertible<T, UnderlyingType>::value, bool>::type System::Enum<E, Guard>::IsDefined(T value)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | T | De te controleren waarde |

### Retourwaarde

True als **value** een lid is van enumeratie **T**, anders - false

## Enum::IsDefined(const String\&) methode


Bepaalt of de waarde met de opgegeven naam een van de leden van enum **E** is.

```cpp
static bool System::Enum<E, Guard>::IsDefined(const String &name)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | const [String](../../string/)\& | De te controleren naam |

### Retourwaarde

True als een lid van enum **E** met de opgegeven naam bestaat.

## Zie ook

* Typedef [UnderlyingType](../underlyingtype/)
* Class [String](../../string/)
* Struct [Enum](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)