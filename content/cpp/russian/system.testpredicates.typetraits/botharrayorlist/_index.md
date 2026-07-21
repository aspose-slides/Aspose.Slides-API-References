---
title: BothArrayOrList
second_title: Справочник API Aspose.Slides для C++
description: Проверяет, являются ли оба аргумента типа массивами или списками. Если да, член value устанавливается в true, иначе — в false.
type: docs
weight: 131
url: /ru/system.testpredicates.typetraits/botharrayorlist/
---
## BothArrayOrList typedef

Проверяет, являются ли оба аргумента типа массивами или списками. Если да, член value устанавливается в true, иначе — в false.

```cpp
using System::TestPredicates::TypeTraits::BothArrayOrList = typedef std::integral_constant<bool, (IsArray<T1>::value || IsList<T1>::value) && (IsArray<T2>::value || IsList<T2>::value)>
```

## См. также

* Пространство имён [System::TestPredicates::TypeTraits](../)
* Библиотека [Aspose.Slides](../../)