---
title: IsCppContainer
second_title: Referência da API Aspose.Slides para C++
description: "Verifica se um tipo específico é um contêiner no estilo STL. Para isso, verifica a existência dos tipos membro iterator e const_iterator. Se ambos existirem, herda std::true_type, caso contrário herda std::false_type."
type: docs
weight: 40
url: /pt/system.testpredicates.typetraits/iscppcontainer/
---
## IsCppContainer struct

Verifica se um tipo específico é um contêiner no estilo STL. Para isso, verifica a existência dos tipos membro iterator e const_iterator. Se ambos existirem, herda std::true_type, caso contrário herda std::false_type.

```cpp
template<typename T,typename Enable>class IsCppContainer : public std::false_type
```

### Parâmetros de Modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo a ser verificado. |
| Enable | Argumento formal para que o SFINAE funcione. |

## Veja Também

* Namespace [System::TestPredicates::TypeTraits](../)
* Biblioteca [Aspose.Slides](../../)