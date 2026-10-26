---
title: ComparerType< SharedPtr< T > >
second_title: Referência da API Aspose.Slides para C++
description: Compara elementos usando a semântica 'less'.
type: docs
weight: 157
url: /pt/system.collections.generic.details/comparertype_tmpl_sharedptr_tmpl_t__end_tmpl__end_tmpl/
---
## ComparerType< SharedPtr< T > > struct

Compara elementos usando a semântica 'less'.

```cpp
template<typename T>class ComparerType< SharedPtr< T > >
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo dos elementos comparados. |
## Métodos

| Método | Descrição |
| --- | --- |
| std::enable_if\<std::is_base_of\<[System::IComparable](../../system/icomparable/)\<[System::SharedPtr](../../system/sharedptr/)\<Q\>\>, Q\>::value||[has_method_compareto_shared_ptr](../has_method_compareto_shared_ptr/)\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&, const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&) const | Compara tipos de ponteiro que implementam a interface [IComparable](../../system/icomparable/). |
| std::enable_if<\!(std::is_base_of\<[System::IComparable](../../system/icomparable/)\<[System::SharedPtr](../../system/sharedptr/)\<Q\>\>, Q\>::value||[has_method_compareto_shared_ptr](../has_method_compareto_shared_ptr/)\<Q\>::value), **bool**\>::type [operator()](./operator_call/)(const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&, const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&) const | Compara tipos de ponteiro que não implementam a interface [IComparable](../../system/icomparable/). |

## Veja Também

* Namespace [System::Collections::Generic::Details](../)
* Biblioteca [Aspose.Slides](../../)