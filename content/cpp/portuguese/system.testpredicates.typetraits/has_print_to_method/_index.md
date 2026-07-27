---
title: has_print_to_method
second_title: Referência da API Aspose.Slides para C++
description: "Verifica a sobrecarga da função PrintTo que aceita o tipo fornecido como primeiro argumento. Se existir uma sobrecarga, herda std::true_type, caso contrário herda std::false_type."
type: docs
weight: 27
url: /pt/system.testpredicates.typetraits/has_print_to_method/
---
## has_print_to_method struct

Verifica a sobrecarga da função PrintTo que aceita o tipo fornecido como primeiro argumento. Se existir uma sobrecarga, herda std::true_type, caso contrário herda std::false_type.

```cpp
template<typename T,typename Enable>class has_print_to_method : public std::false_type
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo a ser verificado. |
| Enable | Argumento formal para o SFINAE funcionar. |

## Ver também

* Espaço de nomes [System::TestPredicates::TypeTraits](../)
* Biblioteca [Aspose.Slides](../../)