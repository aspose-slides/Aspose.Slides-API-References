---
title: Enum
second_title: Aspose.Slides for C++ API Referencia
description: Metódusokat biztosít, amelyek bizonyos műveleteket hajtanak végre az enum típusú értékeken. Ez egy statikus típus, amelynek nincs példányszolgáltatása. Soha ne hozzon létre példányt ebből semmilyen módon.
type: docs
weight: 1587
url: /hu/system/enum/
---
## Enum struktúra

Metódusokat biztosít, amelyek bizonyos műveleteket hajtanak végre az enum típusú értékeken. Ez egy statikus típus, amelynek nincs példányszolgáltatása. Soha ne hozzon létre példányt ebből semmilyen módon.

```cpp
template<class E,class Guard>class Enum
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| E | Az enum típusa, amelynek értékeit a osztály kezeli |
| Guard | Szolgáltatástípus argumentum, amelynek célja, hogy biztosítsa, hogy **E** felsorolható típus legyen |

## Metódusok

| Metódus | Leírás |
| --- | --- |
| static int [Compare](./compare/)(E, T) | A megadott enumerációs állandók értékeinek aritmetikai összehasonlítását végzi. |
| static std::enable_if\<std::is_same\<T, E\>::value||std::is_convertible\<T, [UnderlyingType](./underlyingtype/)\>::value, [String](../string/)\>::type [GetDescription](./getdescription/)(T) | Visszaadja a megadott értékkel rendelkező enumerációs állandó nevét. |
| static std::enable_if\<std::is_same\<T, E\>::value||std::is_convertible\<T, [UnderlyingType](./underlyingtype/)\>::value, [String](../string/)\>::type [GetName](./getname/)(T) | Visszaadja a megadott értékkel rendelkező enumerációs állandó nevét. |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](./getnames/)() | **E** enumeráció összes elemének nevét tartalmazó tömböt ad vissza. |
| static const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](./getunderlyingtype/)() | Visszaadja az enumeráció alapvető típusát. |
| static [ArrayPtr](../arrayptr/)\<E\> [GetValues](./getvalues/)() | **E** enumeráció összes elemét tartalmazó tömböt ad vissza. |
| static **bool** [HasFlag](./hasflag/)(E, E) | Megállapítja, hogy a megadott bitek be vannak-e állítva a megadott enum érték bitábrázolásában. |
| static **bool** [IsDefined](./isdefined/)(E) | Megállapítja, hogy a megadott érték az **E** enumeráció típusának tagja-e. |
| static std::enable_if\<std::is_convertible\<T, [UnderlyingType](./underlyingtype/)\>::value, **bool**\>::type [IsDefined](./isdefined/)(T) | Megállapítja, hogy a megadott érték a **T** enumeráció típusának tagja-e. |
| static **bool** [IsDefined](./isdefined/)(const [String](../string/)\&) | Megállapítja, hogy a megadott névvel rendelkező érték az **E** enum tagjai között van-e. |
| static E [Parse](./parse/)(const [String](../string/)\&, **bool**) | Átalakítja a megadott szöveget az ekvivalens enum állandóvá. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, E\&) | Megpróbálja a megadott szöveget az ekvivalens enum állandóvá konvertálni. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **bool**, E\&) | Megpróbálja a megadott szöveget az ekvivalens enum állandóvá konvertálni. |

## Típusdefiníciók

| Típusdefiníció | Leírás |
| --- | --- |
| [UnderlyingType](./underlyingtype/) | Az enum alapvető típusának álneve. |

## Lásd még

* Névtér [System](../)
* Könyvtár [Aspose.Slides](../../)