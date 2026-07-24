---
title: EqualityComparerHashAdapter
second_title: Aspose.Slides für C++ API-Referenz
description: Adapter zur Verwendung von IEqualityComparer zum Hashen. Verwendet das Comparator-Objekt, falls gesetzt; andernfalls wird die verfügbare Hash-Methode verwendet, die über die DictionaryHashSelector Struktur ausgewählt wird.
type: docs
weight: 677
url: /de/system.collections.generic/equalitycomparerhashadapter/
---
## EqualityComparerHashAdapter Struktur

Adapter zur Verwendung von [IEqualityComparer](../iequalitycomparer/) zum Hashen. Verwendet das Comparator-Objekt, falls gesetzt; andernfalls wird die verfügbare Hash-Methode verwendet, die über die [DictionaryHashSelector](../dictionaryhashselector/) Struktur ausgewählt wird.

```cpp
template<typename T>class EqualityComparerHashAdapter
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Hashed | Typ. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
|  [EqualityComparerHashAdapter](./equalitycomparerhashadapter/)() | Erstellt einen Adapter ohne zu verwendenden Comparator. |
|  [EqualityComparerHashAdapter](./equalitycomparerhashadapter/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | Erstellt einen Adapter mit dem angegebenen Comparator. |
| std::size_t [operator()](./operator_call/)(const T\&) const | Berechnet den Hash-Wert. |
| void [set_EqualityComparator](./set_equalitycomparator/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | Setzt den zu verwendenden Comparator. |

## Siehe auch

* Namensraum [System::Collections::Generic](../)
* Bibliothek [Aspose.Slides](../../)