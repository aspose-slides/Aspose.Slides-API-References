---
title: ComparerType< SharedPtr< T > >
second_title: Справочник API Aspose.Slides для C++
description: Сравнивает элементы, используя семантику 'less'.
type: docs
weight: 157
url: /ru/system.collections.generic.details/comparertype_tmpl_sharedptr_tmpl_t__end_tmpl__end_tmpl/
---
## ComparerType< SharedPtr< T > > структура


Сравнивает элементы, используя семантику «less».

```cpp
template<typename T>class ComparerType< SharedPtr< T > >
```


### Параметры шаблона

| Parameter | Description |
| --- | --- |
| T | Тип сравниваемых элементов. |
## Методы

| Method | Description |
| --- | --- |
| std::enable_if\<std::is_base_of\<[System::IComparable](../../system/icomparable/)\<[System::SharedPtr](../../system/sharedptr/)\<Q\>\>, Q\>::value||[has_method_compareto_shared_ptr](../has_method_compareto_shared_ptr/)\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&, const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&) const | Сравнивает типы указателей, реализующие интерфейс [IComparable](../../system/icomparable/). |
| std::enable_if<\!(std::is_base_of\<[System::IComparable](../../system/icomparable/)\<[System::SharedPtr](../../system/sharedptr/)\<Q\>\>, Q\>::value||[has_method_compareto_shared_ptr](../has_method_compareto_shared_ptr/)\<Q\>::value), **bool**\>::type [operator()](./operator_call/)(const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&, const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&) const | Сравнивает типы указателей, не реализующие интерфейс [IComparable](../../system/icomparable/). |

## См. также

* Пространство имён [System::Collections::Generic::Details](../)
* Библиотека [Aspose.Slides](../../)