---
title: operator==()
second_title: Aspose.Slides för C++ API-referens
description: Jämför två nyckel-värde-par med 'equals'-semantik. Använder operator == eller EqualsTo-metoden för både nycklar och värden, beroende på vad som är definierat.
type: docs
weight: 690
url: /sv/system.collections.generic/operator_equal_equal/
---
## System::Collections::Generic::operator==(const KeyValuePair\<TKey, TValue\>\&, const KeyValuePair\<TKey, TValue\>\&) funktion

Jämför två nyckel-värde-par med 'equals'-semantik. Använder operator == eller EqualsTo-metoden för både nycklar och värden, beroende på vad som är definierat.

```cpp
template<typename TKey,typename TValue> bool System::Collections::Generic::operator==(const KeyValuePair<TKey, TValue> &left, const KeyValuePair<TKey, TValue> &right)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| TKey | Nyckeltyp. |
| TValue | Värdetyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| left | const [KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\& | Vänster operand. |
| right | const [KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\& | Höger operand. |

### Returvärde

Sant om både nycklar och värden matchar, falskt annars.

## Se också

* Klass [KeyValuePair](../keyvaluepair/)
* Namnrymd [System::Collections::Generic](../)
* Bibliotek [Aspose.Slides](../../)