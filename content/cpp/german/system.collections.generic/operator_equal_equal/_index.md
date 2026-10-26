---
title: operator==()
second_title: Aspose.Slides für C++ API-Referenz
description: Vergleicht zwei Schlüssel-Wert-Paare mittels 'equals'-Semantik. Verwendet den Operator == oder die Methode EqualsTo für sowohl Schlüssel als auch Werte, je nachdem, was definiert ist.
type: docs
weight: 690
url: /de/system.collections.generic/operator_equal_equal/
---
## System::Collections::Generic::operator==(const KeyValuePair\<TKey, TValue\>\&, const KeyValuePair\<TKey, TValue\>\&) Funktion

Vergleicht zwei Schlüssel-Wert-Paare mittels 'equals'-Semantik. Verwendet den Operator == oder die Methode EqualsTo für sowohl Schlüssel als auch Werte, je nachdem, was definiert ist.

```cpp
template<typename TKey,typename TValue> bool System::Collections::Generic::operator==(const KeyValuePair<TKey, TValue> &left, const KeyValuePair<TKey, TValue> &right)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| TKey | Schlüsseltyp. |
| TValue | Werttyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| left | const [KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\& | Linker Operand. |
| right | const [KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\& | Rechter Operand. |

### Rückgabewert

True, wenn sowohl Schlüssel als auch Werte übereinstimmen, sonst false.

## Siehe auch

* Klasse [KeyValuePair](../keyvaluepair/)
* Namensraum [System::Collections::Generic](../)
* Bibliothek [Aspose.Slides](../../)