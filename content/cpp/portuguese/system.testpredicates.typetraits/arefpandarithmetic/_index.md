---
title: AreFPandArithmetic
second_title: Referência da API Aspose.Slides para C++
description: Verifica se T1 é aritmético e T2 é ponto flutuante, ou vice-versa. Se for o caso, define o membro value como true, caso contrário é false.
type: docs
weight: 79
url: /pt/system.testpredicates.typetraits/arefpandarithmetic/
---
## AreFPandArithmetic typedef


Verifica se **T1** é aritmético e **T2** é ponto flutuante, ou vice-versa. Se for o caso, define o membro value como true, caso contrário é false.

```cpp
using System::TestPredicates::TypeTraits::AreFPandArithmetic = typedef std::integral_constant<bool, (std::is_floating_point<T1>::value && std::is_arithmetic<T2>::value) || (std::is_arithmetic<T1>::value && std::is_floating_point<T2>::value) >
```


## Veja Também

* Espaço de nomes [System::TestPredicates::TypeTraits](../)
* Biblioteca [Aspose.Slides](../../)