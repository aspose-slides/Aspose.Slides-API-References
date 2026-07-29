---
title: KeyValuePair()
second_title: Aspose.Slides för C++ API-referens
description: Initierare för null nyckel-värde-par.
type: docs
weight: 1
url: /sv/system.collections.generic/keyvaluepair/keyvaluepair/
---
## KeyValuePair::KeyValuePair() konstruktor

Initierare för null nyckel-värde-par.

```cpp
System::Collections::Generic::KeyValuePair<TKey, TValue>::KeyValuePair()
```

## KeyValuePair::KeyValuePair(const TKey\&, const TValue\&) konstruktor

Konstruktor.

```cpp
System::Collections::Generic::KeyValuePair<TKey, TValue>::KeyValuePair(const TKey &key, const TValue &value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| key | const TKey\& | Nyckel. |
| value | const TValue\& | Värde. |

## KeyValuePair::KeyValuePair(const std::pair\<OtherK, OtherV\>\&) konstruktor

Typkonverteringskonstruktor.

```cpp
template<typename OtherK,typename OtherV> System::Collections::Generic::KeyValuePair<TKey, TValue>::KeyValuePair(const std::pair<OtherK, OtherV> &pair)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| OtherK | Annat nyckeltyp. |
| OtherV | Annat värdetyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pair | const std::pair\<OtherK, OtherV\>\& | Parvärde. |

## Se även

* Klass [KeyValuePair](../)
* Namnrymd [System::Collections::Generic](../../)
* Bibliotek [Aspose.Slides](../../../)