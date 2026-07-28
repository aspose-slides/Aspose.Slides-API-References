---
title: EqualityComparerHashAdapter
second_title: Aspose.Slides C++ API referenciája
description: Adaptáló az IEqualityComparer használatához a hash-eléshez. Ha be van állítva, a comparator objektumot használja; egyébként az elérhető hash-módszert alkalmazza, amelyet a DictionaryHashSelector struct választ ki.
type: docs
weight: 677
url: /hu/system.collections.generic/equalitycomparerhashadapter/
---
## EqualityComparerHashAdapter struct

Az [IEqualityComparer](../iequalitycomparer/) használatához szolgáló adapter a hash-eléshez. Ha be van állítva, a comparator objektumot használja; egyébként a [DictionaryHashSelector](../dictionaryhashselector/) struct által kiválasztott elérhető hash módszert használja.

```cpp
template<typename T>class EqualityComparerHashAdapter
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| Hashed | típus. |

## Metódusok

| Metóda | Leírás |
| --- | --- |
|  [EqualityComparerHashAdapter](./equalitycomparerhashadapter/)() | Létrehozza az adaptert comparator nélkül. |
|  [EqualityComparerHashAdapter](./equalitycomparerhashadapter/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | Létrehozza az adaptert a megadott comparator használatával. |
| std::size_t [operator()](./operator_call/)(const T\&) const | Kiszámítja a hash értéket. |
| void [set_EqualityComparator](./set_equalitycomparator/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | Beállítja a comparator használatát. |

## Lásd még

* Névtér [System::Collections::Generic](../)
* Könyvtár [Aspose.Slides](../../)