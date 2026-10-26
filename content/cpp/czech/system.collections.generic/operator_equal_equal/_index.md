---
title: operator==()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Porovnává dva páry klíč-hodnota pomocí sémantiky 'equals'. Používá operátor == nebo metodu EqualsTo pro oba klíče i hodnoty, podle toho, která je definována.
type: docs
weight: 690
url: /cs/system.collections.generic/operator_equal_equal/
---
## System::Collections::Generic::operator==(const KeyValuePair\<TKey, TValue\>\&, const KeyValuePair\<TKey, TValue\>\&) funkce

Porovnává dva páry klíč-hodnota pomocí sémantiky 'equals'. Používá operátor == nebo metodu EqualsTo pro oba klíče i hodnoty, podle toho, která je definována.

```cpp
template<typename TKey,typename TValue> bool System::Collections::Generic::operator==(const KeyValuePair<TKey, TValue> &left, const KeyValuePair<TKey, TValue> &right)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| TKey | Typ klíče. |
| TValue | Typ hodnoty. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| left | const [KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\& | Operand vlevo. |
| right | const [KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\& | Operand vpravo. |

### Návratová hodnota

True pokud se oba klíče a hodnoty shodují, false jinak.

## Viz také

* Třída [KeyValuePair](../keyvaluepair/)
* Prostor názvů [System::Collections::Generic](../)
* Knihovna [Aspose.Slides](../../)