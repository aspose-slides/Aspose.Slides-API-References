---
title: AnyOfDecimal
second_title: Referência da API Aspose.Slides para C++
description: "Verifica se ao menos um dos argumentos de tipo é System::Decimal. Se for, define o membro value como true, caso contrário é false."
type: docs
weight: 92
url: /pt/system.testpredicates.typetraits/anyofdecimal/
---
## AnyOfDecimal typedef

Verifica se ao menos um dos argumentos de tipo é [System::Decimal](../../system/decimal/). Se for, define o membro value como true, caso contrário é false.

```cpp
using System::TestPredicates::TypeTraits::AnyOfDecimal = typedef std::integral_constant<bool, std::is_same<T1, System::Decimal>::value || std::is_same<T2, System::Decimal>::value>
```

## Ver Também

* Espaço de nomes [System::TestPredicates::TypeTraits](../)
* Biblioteca [Aspose.Slides](../../)