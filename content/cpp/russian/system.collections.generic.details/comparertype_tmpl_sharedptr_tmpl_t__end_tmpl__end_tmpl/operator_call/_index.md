---
title: operator()()
second_title: Aspose.Slides для C++ справочник API
description: Сравнивает типы указателей, реализующие интерфейс IComparable.
type: docs
weight: 1
url: /ru/system.collections.generic.details/comparertype_tmpl_sharedptr_tmpl_t__end_tmpl__end_tmpl/operator_call/
---
## ComparerType< SharedPtr< T > >::operator()(const System::SharedPtr\<Q\>\&, const System::SharedPtr\<Q\>\&) const method

Сравнивает типы указателей, реализующие [IComparable](../../../system/icomparable/) интерфейс.

```cpp
template<typename Q> std::enable_if<std::is_base_of<System::IComparable<System::SharedPtr<Q>>, Q>::value||has_method_compareto_shared_ptr<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<SharedPtr<T>>::operator()(const System::SharedPtr<Q> &a, const System::SharedPtr<Q> &b) const
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Q | Тип для сравнения. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| a | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | Левое значение. |
| b | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | Правое значение. |

### Возвращаемое значение

True если **a** считается меньше **b**, false в противном случае.

## ComparerType< SharedPtr< T > >::operator()(const System::SharedPtr\<Q\>\&, const System::SharedPtr\<Q\>\&) const method

Сравнивает типы указателей, не реализующие [IComparable](../../../system/icomparable/) интерфейс.

```cpp
template<typename Q> std::enable_if<!(std::is_base_of<System::IComparable<System::SharedPtr<Q>>, Q>::value||has_method_compareto_shared_ptr<Q>::value), bool>::type System::Collections::Generic::Details::ComparerType<SharedPtr<T>>::operator()(const System::SharedPtr<Q> &a, const System::SharedPtr<Q> &b) const
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Q | Тип для сравнения. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| a | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | Левое значение. |
| b | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | Правое значение. |

### Возвращаемое значение

True если **a** считается меньше **b**, false в противном случае.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IComparable](../../../system/icomparable/)
* Struct [has_method_compareto_shared_ptr](../../has_method_compareto_shared_ptr/)
* Struct [ComparerType< SharedPtr< T > >](../)
* Namespace [System::Collections::Generic::Details](../../)
* Library [Aspose.Slides](../../../)