---
title: operator()()
second_title: Referencia de la API de Aspose.Slides para C++
description: Compara tipos de puntero que implementan la interfaz IComparable.
type: docs
weight: 1
url: /es/system.collections.generic.details/comparertype_tmpl_sharedptr_tmpl_t__end_tmpl__end_tmpl/operator_call/
---
## ComparerType< SharedPtr< T > >::operator()(const System::SharedPtr\<Q\>\&, const System::SharedPtr\<Q\>\&) const método

Compara tipos de puntero que implementan la interfaz [IComparable](../../../system/icomparable/).

```cpp
template<typename Q> std::enable_if<std::is_base_of<System::IComparable<System::SharedPtr<Q>>, Q>::value||has_method_compareto_shared_ptr<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<SharedPtr<T>>::operator()(const System::SharedPtr<Q> &a, const System::SharedPtr<Q> &b) const
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| Q | Tipo a comparar. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | Valor LHS. |
| b | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | Valor RHS. |

### Valor devuelto

True si **a** se considera menor que **b**, false en caso contrario.

## ComparerType< SharedPtr< T > >::operator()(const System::SharedPtr\<Q\>\&, const System::SharedPtr\<Q\>\&) const método

Compara tipos de puntero que no implementan la interfaz [IComparable](../../../system/icomparable/).

```cpp
template<typename Q> std::enable_if<!(std::is_base_of<System::IComparable<System::SharedPtr<Q>>, Q>::value||has_method_compareto_shared_ptr<Q>::value), bool>::type System::Collections::Generic::Details::ComparerType<SharedPtr<T>>::operator()(const System::SharedPtr<Q> &a, const System::SharedPtr<Q> &b) const
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| Q | Tipo a comparar. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | Valor LHS. |
| b | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | Valor RHS. |

### Valor devuelto

True si **a** se considera menor que **b**, false en caso contrario.

## Véase también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IComparable](../../../system/icomparable/)
* Estructura [has_method_compareto_shared_ptr](../../has_method_compareto_shared_ptr/)
* Estructura [ComparerType< SharedPtr< T > >](../)
* Espacio de nombres [System::Collections::Generic::Details](../../)
* Biblioteca [Aspose.Slides](../../../)