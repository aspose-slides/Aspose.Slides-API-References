---
title: EqualityComparerAdapter
second_title: Aspose.Slides för C++ API-referens
description: "Adapter som gör det möjligt att använda IEqualityComparer med STL-stilade samlingar och algoritmer. Använder IEqualityComparer, om den är satt. Om den inte är satt, använder operator ==, Object::Equals eller T::Equals, beroende på vad som är tillgängligt."
type: docs
weight: 664
url: /sv/system.collections.generic/equalitycompareradapter/
---
## EqualityComparerAdapter struct

Adapter som gör det möjligt att använda [IEqualityComparer](../iequalitycomparer/) med STL-stilade samlingar och algoritmer. Använder [IEqualityComparer](../iequalitycomparer/) om den är satt. Om den inte är satt, används operator ==, [Object::Equals](../../system/object/equals/) eller T::Equals, beroende på vad som är tillgängligt.

```cpp
template<class T>class EqualityComparerAdapter
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typ som jämförs. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  [EqualityComparerAdapter](./equalitycompareradapter/)() | Skapar adapter som inte använder någon komparator. |
|  [EqualityComparerAdapter](./equalitycompareradapter/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | Skapar adapter med angiven komparator. |
| **bool** [operator()](./operator_call/)(const T\&, const T\&) const | Jämför två objekt. |
| void [set_EqualityComparator](./set_equalitycomparator/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | Ställer in komparator. |

## Se även

* Namnrymd [System::Collections::Generic](../)
* Bibliotek [Aspose.Slides](../../)