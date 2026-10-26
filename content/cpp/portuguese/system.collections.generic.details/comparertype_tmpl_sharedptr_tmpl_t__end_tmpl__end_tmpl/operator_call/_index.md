---
title: operator()()
second_title: Referência da API Aspose.Slides para C++
description: Compara tipos de ponteiro que implementam a interface IComparable.
type: docs
weight: 1
url: /pt/system.collections.generic.details/comparertype_tmpl_sharedptr_tmpl_t__end_tmpl__end_tmpl/operator_call/
---
## ComparerType< SharedPtr< T > >::operator()(const System::SharedPtr\<Q\>\&, const System::SharedPtr\<Q\>\&) const método

Compara tipos de ponteiro que implementam [IComparable](../../../system/icomparable/) interface.

```cpp
template<typename Q> std::enable_if<std::is_base_of<System::IComparable<System::SharedPtr<Q>>, Q>::value||has_method_compareto_shared_ptr<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<SharedPtr<T>>::operator()(const System::SharedPtr<Q> &a, const System::SharedPtr<Q> &b) const
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| Q | Tipo a comparar. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| a | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | Valor do LHS. |
| b | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | Valor do RHS. |

### Valor de retorno

Verdadeiro se **a** for considerado menor que **b**, falso caso contrário.

## ComparerType< SharedPtr< T > >::operator()(const System::SharedPtr\<Q\>\&, const System::SharedPtr\<Q\>\&) const método

Compara tipos de ponteiro que não implementam [IComparable](../../../system/icomparable/) interface.

```cpp
template<typename Q> std::enable_if<!(std::is_base_of<System::IComparable<System::SharedPtr<Q>>, Q>::value||has_method_compareto_shared_ptr<Q>::value), bool>::type System::Collections::Generic::Details::ComparerType<SharedPtr<T>>::operator()(const System::SharedPtr<Q> &a, const System::SharedPtr<Q> &b) const
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| Q | Tipo a comparar. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| a | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | Valor do LHS. |
| b | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | Valor do RHS. |

### Valor de retorno

Verdadeiro se **a** for considerado menor que **b**, falso caso contrário.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IComparable](../../../system/icomparable/)
* Estrutura [has_method_compareto_shared_ptr](../../has_method_compareto_shared_ptr/)
* Estrutura [ComparerType< SharedPtr< T > >](../)
* Espaço de nomes [System::Collections::Generic::Details](../../)
* Biblioteca [Aspose.Slides](../../../)