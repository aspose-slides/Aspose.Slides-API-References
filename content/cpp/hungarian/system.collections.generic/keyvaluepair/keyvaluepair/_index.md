---
title: KeyValuePair()
second_title: Aspose.Slides C++ API referenciája
description: Null kulcs-érték pár inicializáló.
type: docs
weight: 1
url: /hu/system.collections.generic/keyvaluepair/keyvaluepair/
---
## KeyValuePair::KeyValuePair() konstruktor


Null kulcs-érték pár inicializáló.

```cpp
System::Collections::Generic::KeyValuePair<TKey, TValue>::KeyValuePair()
```

## KeyValuePair::KeyValuePair(const TKey\&, const TValue\&) konstruktor


Konstruktor.

```cpp
System::Collections::Generic::KeyValuePair<TKey, TValue>::KeyValuePair(const TKey &key, const TValue &value)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| key | const TKey\& | Kulcs. |
| value | const TValue\& | Érték. |

## KeyValuePair::KeyValuePair(const std::pair\<OtherK, OtherV\>\&) konstruktor


Típuskonverziós konstruktor.

```cpp
template<typename OtherK,typename OtherV> System::Collections::Generic::KeyValuePair<TKey, TValue>::KeyValuePair(const std::pair<OtherK, OtherV> &pair)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| OtherK | Másik kulcs típusa. |
| OtherV | Másik érték típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pair | const std::pair\<OtherK, OtherV\>\& | Pár érték. |

## Lásd még

* Osztály [KeyValuePair](../)
* Névterület [System::Collections::Generic](../../)
* Könyvtár [Aspose.Slides](../../../)