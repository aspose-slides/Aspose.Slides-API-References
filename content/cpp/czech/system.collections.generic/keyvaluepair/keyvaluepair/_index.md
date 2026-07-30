---
title: KeyValuePair()
second_title: Aspose.Slides pro C++ API Reference
description: Inicializátor nulového páru klíč-hodnota.
type: docs
weight: 1
url: /cs/system.collections.generic/keyvaluepair/keyvaluepair/
---
## KeyValuePair::KeyValuePair() konstruktor


Inicializátor nulového páru klíč-hodnota.

```cpp
System::Collections::Generic::KeyValuePair<TKey, TValue>::KeyValuePair()
```

## KeyValuePair::KeyValuePair(const TKey\&, const TValue\&) konstruktor


Konstruktor.

```cpp
System::Collections::Generic::KeyValuePair<TKey, TValue>::KeyValuePair(const TKey &key, const TValue &value)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| key | const TKey\& | Klíč. |
| value | const TValue\& | Hodnota. |

## KeyValuePair::KeyValuePair(const std::pair\<OtherK, OtherV\>\&) konstruktor


Konstruktor převodu typu.

```cpp
template<typename OtherK,typename OtherV> System::Collections::Generic::KeyValuePair<TKey, TValue>::KeyValuePair(const std::pair<OtherK, OtherV> &pair)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| OtherK | Typ ostatního klíče. |
| OtherV | Typ ostatní hodnoty. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| pair | const std::pair\<OtherK, OtherV\>\& | Hodnota páru. |

## Viz také

* Třída [KeyValuePair](../)
* Jmenný prostor [System::Collections::Generic](../../)
* Knihovna [Aspose.Slides](../../../)