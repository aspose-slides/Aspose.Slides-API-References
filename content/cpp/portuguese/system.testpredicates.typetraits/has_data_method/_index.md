---
title: has_data_method
second_title: Referência da API Aspose.Slides para C++
description: "Verifica se um tipo possui o método data(). Se possuir, herda std::true_type, caso contrário herda std::false_type."
type: docs
weight: 1
url: /pt/system.testpredicates.typetraits/has_data_method/
---
## has_data_method struct


Verifica se um tipo possui o método data(). Se possuir, herda std::true_type, caso contrário herda std::false_type.

```cpp
template<typename T,typename Enable>class has_data_method : public std::false_type
```


### Parâmetros do modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo a ser verificado. |
| Enable | Argumento formal para que SFINAE funcione. |

## Veja também

* Espaço de nomes [System::TestPredicates::TypeTraits](../)
* Biblioteca [Aspose.Slides](../../)