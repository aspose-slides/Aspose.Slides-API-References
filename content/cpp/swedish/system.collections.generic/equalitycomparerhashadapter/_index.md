---
title: EqualityComparerHashAdapter
second_title: Aspose.Slides för C++ API-referens
description: Adapter för att använda IEqualityComparer för hashning. Använder jämförelseobjekt, om det är satt; annars används tillgänglig hashmetod som valts med DictionaryHashSelector struct.
type: docs
weight: 677
url: /sv/system.collections.generic/equalitycomparerhashadapter/
---
## EqualityComparerHashAdapter struct

Adapter för att använda [IEqualityComparer](../iequalitycomparer/) för hashning. Använder jämförelseobjekt, om det är satt; annars används tillgänglig hashmetod som valts med [DictionaryHashSelector](../dictionaryhashselector/) struct.

```cpp
template<typename T>class EqualityComparerHashAdapter
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Hashed | typ. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  [EqualityComparerHashAdapter](./equalitycomparerhashadapter/)() | Skapar en adapter utan komparator att använda. |
|  [EqualityComparerHashAdapter](./equalitycomparerhashadapter/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | Skapar en adapter med angiven komparator att använda. |
| std::size_t [operator()](./operator_call/)(const T\&) const | Beräknar hashvärde. |
| void [set_EqualityComparator](./set_equalitycomparator/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | Ställer in komparator att använda. |

## Se även

* Namnrymd [System::Collections::Generic](../)
* Library [Aspose.Slides](../../)