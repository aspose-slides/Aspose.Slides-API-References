---
title: Box()
second_title: Aspose.Slides voor C++ API-referentie
description: Boxt waardetypen voor conversie naar Object. Implementatie voor enum-typen.
type: docs
weight: 40
url: /nl/system/objectext/box/
---
## ObjectExt::Box(const T\&) methode


Boxt waardetypen voor conversie naar [Object](../../object/). Implementatie voor enum-typen.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, System::SmartPtr<System::Object>>::type System::ObjectExt::Box(const T &value)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | [Enum](../../enum/) type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const T\& | [Enum](../../enum/) waarde om te boxen. |

### Retourwaarde

Slimme pointer naar object dat de ingepakte waarde behoudt.

## ObjectExt::Box(const T\&) methode


Boxt waardetypen voor conversie naar [Object](../../object/). Implementatie voor niet-enum-typen.

```cpp
template<typename T> static std::enable_if<!std::is_enum<T>::value &&!IsNullable<T>::value, System::SmartPtr<System::Object>>::type System::ObjectExt::Box(const T &value)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Waarde type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const T\& | Waarde om te boxen. |

### Retourwaarde

Slimme pointer naar object dat de ingepakte waarde behoudt.

## ObjectExt::Box(const T\&) methode


Boxt [Nullable](../../nullable/)-typen voor conversie naar [Object](../../object/).

```cpp
template<typename T> static std::enable_if<IsNullable<T>::value, System::SmartPtr<System::Object>>::type System::ObjectExt::Box(const T &value)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Waarde type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const T\& | Waarde om te boxen. |

### Retourwaarde

Slimme pointer naar object dat de ingepakte waarde behoudt.

## ObjectExt::Box(const String\&) methode


Boxt tekenreekswaarden.

```cpp
SmartPtr<Object> System::ObjectExt::Box(const String &value)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../string/)\& | Waarde om te boxen. |

### Retourwaarde

Boxed value of null, if source string is null.

## Zie ook

* Klasse [SmartPtr](../../smartptr/)
* Klasse [Object](../../object/)
* Klasse [ObjectExt](../)
* Klasse [String](../../string/)
* Struct [IsNullable](../../isnullable/)
* Naamruimte [System](../../)
* Bibliotheek [Aspose.Slides](../../../)