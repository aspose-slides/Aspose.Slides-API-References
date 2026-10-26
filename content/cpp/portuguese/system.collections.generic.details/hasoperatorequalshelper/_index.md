---
title: HasOperatorEqualsHelper()
second_title: Aspose.Slides para C++ Referência da API
description: Função auxiliar para determinar se uma classe específica possui o operador ==.
type: docs
weight: 235
url: /pt/system.collections.generic.details/hasoperatorequalshelper/
---
## System::Collections::Generic::Details::HasOperatorEqualsHelper(T *, T *) função

Função auxiliar para determinar se uma classe específica possui o operador ==.

```cpp
template<class T,typename Dummy> std::true_type System::Collections::Generic::Details::HasOperatorEqualsHelper(T *, T *)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo a ser verificado. |
| Dummy | Argumento fictício para magia SFINAE. |

### Valor de retorno

Valor de std::true_type se o operador == estiver presente e false caso contrário.

## System::Collections::Generic::Details::HasOperatorEqualsHelper(void *, void *) função

Função auxiliar para determinar se uma classe específica possui o operador ==.

```cpp
std::false_type System::Collections::Generic::Details::HasOperatorEqualsHelper(void *, void *)
```

### Valor de retorno

Valor de std::true_type se o operador == estiver presente e false caso contrário.

## Ver também

* Espaço de nomes [System::Collections::Generic::Details](../)
* Biblioteca [Aspose.Slides](../../)