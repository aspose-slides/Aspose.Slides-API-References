---
title: operator==()
second_title: Aspose.Slides voor C++ API Referentie
description: Vergelijkt twee sleutel-waarde-paren met behulp van 'equals' semantiek. Gebruikt operator == of de EqualsTo-methode voor zowel sleutels als waarden, afhankelijk van welke is gedefinieerd.
type: docs
weight: 690
url: /nl/system.collections.generic/operator_equal_equal/
---
## System::Collections::Generic::operator==(const KeyValuePair\<TKey, TValue\>\&, const KeyValuePair\<TKey, TValue\>\&) function


Vergelijkt twee sleutel-waarde-paren met behulp van 'equals' semantiek. Gebruikt operator == of EqualsTo-methode voor zowel sleutels als waarden, afhankelijk van welke is gedefinieerd.

```cpp
template<typename TKey,typename TValue> bool System::Collections::Generic::operator==(const KeyValuePair<TKey, TValue> &left, const KeyValuePair<TKey, TValue> &right)
```


### Sjabloonparameters

| Parameter | Description |
| --- | --- |
| TKey | Key type. |
| TValue | Value type. |

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| left | const [KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\& | LHS operand. |
| right | const [KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\& | RHS operand. |

### Retourwaarde

True als zowel de sleutels als de waarden overeenkomen, false anders.

## Zie ook

* Klasse [KeyValuePair](../keyvaluepair/)
* Naamruimte [System::Collections::Generic](../)
* Bibliotheek [Aspose.Slides](../../)