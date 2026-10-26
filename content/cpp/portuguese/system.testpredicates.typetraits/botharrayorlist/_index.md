---
title: BothArrayOrList
second_title: Aspose.Slides para C++ Referência da API
description: Verifica se ambos os argumentos de tipo são arrays ou listas. Se for o caso, o membro value é definido como true, caso contrário é definido como false.
type: docs
weight: 131
url: /pt/system.testpredicates.typetraits/botharrayorlist/
---
## BothArrayOrList typedef

Verifica se ambos os argumentos de tipo são arrays ou listas. Se for o caso, o membro value é definido como true, caso contrário é definido como false.

```cpp
using System::TestPredicates::TypeTraits::BothArrayOrList = typedef std::integral_constant<bool, (IsArray<T1>::value || IsList<T1>::value) && (IsArray<T2>::value || IsList<T2>::value)>
```

## Veja Também

* Espaço de nomes [System::TestPredicates::TypeTraits](../)
* Biblioteca [Aspose.Slides](../../)