---
title: operator!=()
second_title: Aspose.Slides för C++ API-referens
description: Jämför två nyckel-värdepar med omvänd 'equals'-semantik.
type: docs
weight: 703
url: /sv/system.collections.generic/operator_not_equal/
---
## System::Collections::Generic::operator!=(const KeyValuePair\<TKey, TValue\>\&, const KeyValuePair\<TKey, TValue\>\&) function

Jämför två nyckel-värdepar med omvänd 'equals'-semantik.

```cpp
template<typename TKey,typename TValue> bool System::Collections::Generic::operator!=(const KeyValuePair<TKey, TValue> &left, const KeyValuePair<TKey, TValue> &right)
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

Sant om både nycklar och värden inte matchar, falskt annars.

## Se även

* Klass [KeyValuePair](../keyvaluepair/)
* Namnrymd [System::Collections::Generic](../)
* Bibliotek [Aspose.Slides](../../)