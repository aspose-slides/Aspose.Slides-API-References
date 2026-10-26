---
title: operator==()
second_title: Aspose.Slides C++ API referencia
description: Összehasonlít két kulcs-érték párt az 'equals' szemantika szerint. Mindkét kulcshoz és értékhez az == operátort vagy az EqualsTo metódust használja, attól függően, hogy melyik van definiálva.
type: docs
weight: 690
url: /hu/system.collections.generic/operator_equal_equal/
---
## System::Collections::Generic::operator==(const KeyValuePair\<TKey, TValue\>\&, const KeyValuePair\<TKey, TValue\>\&) függvény


Összehasonlít két kulcs-érték párt az 'equals' szemantika szerint. Mindkét kulcshoz és értékhez az == operátort vagy az EqualsTo metódust használja, attól függően, hogy melyik van definiálva.

```cpp
template<typename TKey,typename TValue> bool System::Collections::Generic::operator==(const KeyValuePair<TKey, TValue> &left, const KeyValuePair<TKey, TValue> &right)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| TKey | Kulcs típusa. |
| TValue | Érték típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| left | const [KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\& | Bal operandus. |
| right | const [KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\& | Jobb operandus. |

### Visszatérési érték

Igaz, ha mind a kulcsok, mind az értékek egyeznek, különben hamis.

## Lásd még

* Osztály [KeyValuePair](../keyvaluepair/)
* Névtér [System::Collections::Generic](../)
* Könyvtár [Aspose.Slides](../../)