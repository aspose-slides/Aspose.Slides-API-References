---
title: EqualityComparerAdapter
second_title: Aspose.Slides for C++ API Referencia
description: "Adapter, amely lehetővé teszi az IEqualityComparer használatát STL-stílusú gyűjteményekkel és algoritmusokkal. Ha be van állítva, használja az IEqualityComparer-t. Ha nincs beállítva, az == operátort, az Object::Equals-t vagy a T::Equals-t használja, attól függően, melyik érhető el."
type: docs
weight: 664
url: /hu/system.collections.generic/equalitycompareradapter/
---
## EqualityComparerAdapter struct

Adapter lehetővé teszi a [IEqualityComparer](../iequalitycomparer/) használatát STL-stílusú gyűjteményekkel és algoritmusokkal. Használja a [IEqualityComparer](../iequalitycomparer/)-t, ha be van állítva. Ha nincs beállítva, akkor az == operátort, a [Object::Equals](../../system/object/equals/)-t vagy a T::Equals-t használja, attól függően, melyik érhető el.

```cpp
template<class T>class EqualityComparerAdapter
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Az összehasonlított típus. |

## Metódusok

| Metódus | Leírás |
| --- | --- |
|  [EqualityComparerAdapter](./equalitycompareradapter/)() | Létrehozza az adaptert, amely nem használ összehasonlítót. |
|  [EqualityComparerAdapter](./equalitycompareradapter/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | Létrehozza az adaptert a megadott összehasonlítóval. |
| **bool** [operator()](./operator_call/)(const T\&, const T\&) const | Összehasonlít két objektumot. |
| void [set_EqualityComparator](./set_equalitycomparator/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | Beállítja az összehasonlítót. |

## Lásd még

* Névtér [System::Collections::Generic](../)
* Könyvtár [Aspose.Slides](../../)