---
title: BothArrayOrList
second_title: Riferimento API Aspose.Slides per C++
description: Verifica se entrambi gli argomenti di tipo sono array o liste. In tal caso, il membro value è impostato a true, altrimenti è impostato a false.
type: docs
weight: 131
url: /it/system.testpredicates.typetraits/botharrayorlist/
---
## BothArrayOrList typedef

Verifica se entrambi gli argomenti di tipo sono array o liste. In tal caso, il membro value è impostato a true, altrimenti è impostato a false.

```cpp
using System::TestPredicates::TypeTraits::BothArrayOrList = typedef std::integral_constant<bool, (IsArray<T1>::value || IsList<T1>::value) && (IsArray<T2>::value || IsList<T2>::value)>
```

## Vedi anche

* Spazio dei nomi [System::TestPredicates::TypeTraits](../)
* Libreria [Aspose.Slides](../../)