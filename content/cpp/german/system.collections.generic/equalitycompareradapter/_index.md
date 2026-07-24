---
title: EqualityComparerAdapter
second_title: Aspose.Slides für C++ API-Referenz
description: "Adapter, der die Verwendung von IEqualityComparer mit STL-ähnlichen Sammlungen und Algorithmen ermöglicht. Verwendet IEqualityComparer, falls gesetzt. Wenn nicht gesetzt, wird operator ==, Object::Equals oder T::Equals verwendet, je nachdem, was verfügbar ist."
type: docs
weight: 664
url: /de/system.collections.generic/equalitycompareradapter/
---
## EqualityComparerAdapter struct

Adapter, der die Verwendung von [IEqualityComparer](../iequalitycomparer/) mit STL-artigen Sammlungen und Algorithmen ermöglicht. Verwendet [IEqualityComparer](../iequalitycomparer/), falls gesetzt. Wenn nicht gesetzt, wird operator ==, [Object::Equals](../../system/object/equals/) oder T::Equals verwendet, je nachdem, was verfügbar ist.

```cpp
template<class T>class EqualityComparerAdapter
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Typ, der verglichen wird. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
|  [EqualityComparerAdapter](./equalitycompareradapter/)() | Erstellt einen Adapter, der keinen Comparator verwendet. |
|  [EqualityComparerAdapter](./equalitycompareradapter/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | Erstellt einen Adapter mit dem angegebenen Comparator. |
| **bool** [operator()](./operator_call/)(const T\&, const T\&) const | Vergleicht zwei Objekte. |
| void [set_EqualityComparator](./set_equalitycomparator/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | Setzt den Comparator. |

## Siehe auch

* Namensraum [System::Collections::Generic](../)
* Bibliothek [Aspose.Slides](../../)