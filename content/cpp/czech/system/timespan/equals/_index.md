---
title: Equals()
second_title: Aspose.Slides pro C++ API Reference
description: Určuje, zda časový interval reprezentovaný aktuálním objektem je roven časovému intervalu reprezentovanému zadaným objektem.
type: docs
weight: 40
url: /cs/system/timespan/equals/
---
## TimeSpan::Equals(TimeSpan) const metoda

Určuje, zda časový interval reprezentovaný aktuálním objektem je roven časovému intervalu reprezentovanému zadaným objektem.

```cpp
constexpr bool System::TimeSpan::Equals(TimeSpan value) const
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [TimeSpan](../) | [TimeSpan](../) objekt, se kterým se porovnává aktuální objekt |

### Návratová hodnota

True if the current object and the specified object represent the same time interval, otherwise - false

## TimeSpan::Equals(const SharedPtr\<Object\>\&) const metoda

Určuje, zda časový interval reprezentovaný aktuálním objektem je roven časovému intervalu reprezentovanému zadaným objektem.

```cpp
bool System::TimeSpan::Equals(const SharedPtr<Object> &obj) const
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | [TimeSpan](../) objekt, se kterým se porovnává aktuální objekt |

### Návratová hodnota

True if the current object and the specified object represent the same time interval, otherwise - false

## TimeSpan::Equals(TimeSpan, TimeSpan) metoda

Vrací true, pokud zadané objekty představují stejný časový interval, jinak - false.

```cpp
static constexpr bool System::TimeSpan::Equals(TimeSpan a, TimeSpan b)
```

## Viz také

* Typedef [SharedPtr](../../sharedptr/)
* třída [TimeSpan](../)
* třída [Object](../../object/)
* jmenný prostor [System](../../)
* Library [Aspose.Slides](../../../)