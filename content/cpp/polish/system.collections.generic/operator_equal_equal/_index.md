---
title: operator==()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Porównuje dwie pary klucz-wartość przy użyciu semantyki „equals”. Używa operatora == lub metody EqualsTo zarówno dla kluczy, jak i wartości, w zależności od tego, która jest zdefiniowana.
type: docs
weight: 690
url: /pl/system.collections.generic/operator_equal_equal/
---
## System::Collections::Generic::operator==(const KeyValuePair\<TKey, TValue\>\&, const KeyValuePair\<TKey, TValue\>\&) funkcja

Porównuje dwie pary klucz-wartość przy użyciu semantyki 'equals'. Używa operatora == lub metody EqualsTo zarówno dla kluczy, jak i wartości, w zależności od tego, która jest zdefiniowana.

```cpp
template<typename TKey,typename TValue> bool System::Collections::Generic::operator==(const KeyValuePair<TKey, TValue> &left, const KeyValuePair<TKey, TValue> &right)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| TKey | Typ klucza. |
| TValue | Typ wartości. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| left | const [KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\& | Lewy operand. |
| right | const [KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\& | Prawy operand. |

### Wartość zwracana

Prawda, jeśli zarówno klucze, jak i wartości się zgadzają, w przeciwnym razie fałsz.

## Zobacz także

* Klasa [KeyValuePair](../keyvaluepair/)
* Przestrzeń nazw [System::Collections::Generic](../)
* Biblioteka [Aspose.Slides](../../)