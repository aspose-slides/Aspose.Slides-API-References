---
title: AbstractEqual()
second_title: Referência da API Aspose.Slides para C++
description: Compara duas coleções de tipo desconhecido.
type: docs
weight: 14
url: /pt/system/testcompare/abstractequal/
---
## TestCompare::AbstractEqual(SCG::ICollection\<T\> *const, SCG::ICollection\<T\> *const) método

Compara duas coleções de tipo desconhecido.

```cpp
template<typename T> static bool System::TestCompare::AbstractEqual(SCG::ICollection<T> *const collA, SCG::ICollection<T> *const collB)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo de elemento da coleção. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| collA | [SCG::ICollection](../../../system.collections.generic/icollection/)\<T\> *const | Coleção LHS. |
| collB | [SCG::ICollection](../../../system.collections.generic/icollection/)\<T\> *const | Coleção RHS. |

### Valor de retorno

true se as coleções coincidirem (por exemplo, ambas são nulas), ou se os tamanhos coincidirem e os elementos coincidirem, false caso contrário.

## Veja também

* Classe [ICollection](../../../system.collections.generic/icollection/)
* Estrutura [TestCompare](../)
* Namespace [System](../../)
* Biblioteca [Aspose.Slides](../../../)