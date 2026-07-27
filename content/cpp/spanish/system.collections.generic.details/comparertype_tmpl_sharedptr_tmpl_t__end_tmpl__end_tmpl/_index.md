---
title: ComparerType< SharedPtr< T > >
second_title: Referencia de la API de Aspose.Slides para C++
description: Compara los elementos usando la semántica de 'less'.
type: docs
weight: 157
url: /es/system.collections.generic.details/comparertype_tmpl_sharedptr_tmpl_t__end_tmpl__end_tmpl/
---
## ComparerType< SharedPtr< T > > struct


Compara los elementos usando la semántica de 'less'.

```cpp
template<typename T>class ComparerType< SharedPtr< T > >
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo de los elementos comparados. |
## Métodos

| Método | Descripción |
| --- | --- |
| std::enable_if\<std::is_base_of\<[System::IComparable](../../system/icomparable/)\<[System::SharedPtr](../../system/sharedptr/)\<Q\>\>, Q\>::value||[has_method_compareto_shared_ptr](../has_method_compareto_shared_ptr/)\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&, const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&) const | Compara tipos de puntero que implementan la interfaz [IComparable](../../system/icomparable/). |
| std::enable_if<\!(std::is_base_of\<[System::IComparable](../../system/icomparable/)\<[System::SharedPtr](../../system/sharedptr/)\<Q\>\>, Q\>::value||[has_method_compareto_shared_ptr](../has_method_compareto_shared_ptr/)\<Q\>::value), **bool**\>::type [operator()](./operator_call/)(const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&, const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&) const | Compara tipos de puntero que no implementan la interfaz [IComparable](../../system/icomparable/). |

## Ver también

* Espacio de nombres [System::Collections::Generic::Details](../)
* Biblioteca [Aspose.Slides](../../)