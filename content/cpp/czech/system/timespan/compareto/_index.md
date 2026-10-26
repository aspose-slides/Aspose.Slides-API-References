---
title: CompareTo()
second_title: Aspose.Slides pro C++ API Referenci
description: Porovnává aktuální a určené objekty.
type: docs
weight: 27
url: /cs/system/timespan/compareto/
---
## TimeSpan::CompareTo(TimeSpan) const metoda

Porovnává aktuální a určené objekty.

```cpp
constexpr int System::TimeSpan::CompareTo(TimeSpan value) const
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [TimeSpan](../) | Objekt [TimeSpan](../) k porovnání s aktuálním objektem |

### Návratová hodnota

- 1 pokud aktuální objekt představuje interval, který je kratší než **value**; 0 pokud aktuální objekt představuje interval, který je roven **value**; 1 pokud aktuální objekt představuje interval, který je delší než **value**

## TimeSpan::CompareTo(const SharedPtr\<Object\>\&) const metoda

Porovnává aktuální a určené objekty.

```cpp
int System::TimeSpan::CompareTo(const SharedPtr<Object> &obj) const
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Objekt [TimeSpan](../) k porovnání s aktuálním objektem |

### Návratová hodnota

- 1 pokud aktuální objekt představuje interval, který je kratší než **value**; 0 pokud aktuální objekt představuje interval, který je roven **value**; 1 pokud aktuální objekt představuje interval, který je delší než **value**

## Viz také

* Typedef [SharedPtr](../../sharedptr/)
* Class [TimeSpan](../)
* Class [Object](../../object/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)