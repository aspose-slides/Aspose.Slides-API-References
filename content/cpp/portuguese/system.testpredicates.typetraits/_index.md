---
title: "System::TestPredicates::TypeTraits"
second_title: Referência da API Aspose.Slides para C++
description: 
type: docs
weight: 963
url: /pt/system.testpredicates.typetraits/
---
## Estruturas

| Struct | Description |
| --- | --- |
| [has_data_method](./has_data_method/) | Verifica se um tipo possui o método data(). Se possuir, herda std::true_type, caso contrário herda std::false_type. |
| [has_data_method< System::Collections::BitArray, void >](./has_data_method_tmpl_system_collections_bitarray__void__end_tmpl/) | Especialização para o tipo BitArray que fornece o tipo boost que é inacessível lá. |
| [has_print_to_method](./has_print_to_method/) | Verifica se existe sobrecarga da função PrintTo que aceita o tipo fornecido como primeiro argumento. Se existir uma sobrecarga, herda std::true_type, caso contrário herda std::false_type. |
| [IsCppContainer](./iscppcontainer/) | Verifica se um tipo específico é um contêiner no estilo STL. Para isso, verifica a existência dos tipos membro iterator e const_iterator. Se ambos existirem, herda std::true_type, caso contrário herda std::false_type. |
| [IsEnumerable](./isenumerable/) | Verifica se o tipo tem a especialização [System::Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/) como tipo base. Se sim, o membro value é definido como true, caso contrário é definido como false. |
| [LargestFPType](./largestfptype/) | Fornece um alias para o tipo de ponto flutuante mais longo disponível. Ignora tipos que não são de ponto flutuante. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [AreFPandArithmetic](./arefpandarithmetic/) | Verifica se **T1** é aritmético e **T2** é ponto flutuante, ou vice-versa. Se for, define o membro value como true, caso contrário é false. |
| [AnyOfDecimal](./anyofdecimal/) | Verifica se ao menos um dos argumentos de tipo é [System::Decimal](../system/decimal/). Se for, define o membro value como true, caso contrário é false. |
| [IsArray](./isarray/) | Verifica se o tipo é uma especialização [System::Array](../system/array/). Se for, o membro value é definido como true, caso contrário é definido como false. |
| [IsList](./islist/) | Verifica se o tipo é uma especialização [System::Collections::Generic::List](../system.collections.generic/list/). Se for, o membro value é definido como true, caso contrário é definido como false. |
| [BothArrayOrList](./botharrayorlist/) | Verifica se ambos os argumentos de tipo são arrays ou listas. Se for, o membro value é definido como true, caso contrário é definido como false. |
| [BothEnumerable](./bothenumerable/) | Verifica se ambos os argumentos de tipo são IEnumerable. Se for, o membro value é definido como true, caso contrário é definido como false. |