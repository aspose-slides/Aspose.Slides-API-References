---
title: ComparerAdapter
second_title: Aspose.Slides C++ API referencia
description: Adapter IComparer használatához STL környezetben. Ha be van állítva, a IComparer-t használja; egyébként a < operátort használja (ha elérhető), vagy hamis értéket ad vissza (ha nem).
type: docs
weight: 638
url: /hu/system.collections.generic/compareradapter/
---
## ComparerAdapter struct

Adapter a [IComparer](../icomparer/) használatához az STL környezetben. Ha be van állítva, a [IComparer](../icomparer/)-t használja; egyébként az < operátort (ha elérhető) vagy hamis értéket ad vissza (ha nem).

```cpp
template<class T>class ComparerAdapter
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Az összehasonlítandó típus. |

## Metódusok

| Metódus | Leírás |
| --- | --- |
|  [ComparerAdapter](./compareradapter/)() | Adaptert hoz létre, amikor nincs elérhető összehasonlító. |
|  [ComparerAdapter](./compareradapter/)(const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) | Adaptert hoz létre. |
| std::enable_if\<detail::has_operator_less\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | [Comparison](../../system/comparison/) függvény a < operátorral rendelkező típusokhoz. |
| std::enable_if<\!detail::has_operator_less\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | [Comparison](../../system/comparison/) függvény a < operátorral nem rendelkező típusokhoz. |
| void [set_Comparator](./set_comparator/)(const [SharedPtr](../../system/sharedptr/)\<[IComparer](../icomparer/)\<T\>\>\&) | Beállítja az összehasonlító objektumot. |

## Lásd még

* Névtér [System::Collections::Generic](../)
* Könyvtár [Aspose.Slides](../../)