---
title: ComparerType< SharedPtr< T > >
second_title: Aspose.Slides C++ API referencia
description: Az elemeket a 'less' szemantika szerint hasonlítja össze.
type: docs
weight: 157
url: /hu/system.collections.generic.details/comparertype_tmpl_sharedptr_tmpl_t__end_tmpl__end_tmpl/
---
## ComparerType< SharedPtr< T > > struct


Az elemeket a 'less' szemantika szerint hasonlítja össze.

```cpp
template<typename T>class ComparerType< SharedPtr< T > >
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Az összehasonlított elemek típusa. |
## Módszerek

| Módszer | Leírás |
| --- | --- |
| std::enable_if\<std::is_base_of\<[System::IComparable](../../system/icomparable/)\<[System::SharedPtr](../../system/sharedptr/)\<Q\>\>, Q\>::value||[has_method_compareto_shared_ptr](../has_method_compareto_shared_ptr/)\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&, const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&) const | Összehasonlítja a [IComparable](../../system/icomparable/) interfészt megvalósító mutatótípusokat. |
| std::enable_if<\!(std::is_base_of\<[System::IComparable](../../system/icomparable/)\<[System::SharedPtr](../../system/sharedptr/)\<Q\>\>, Q\>::value||[has_method_compareto_shared_ptr](../has_method_compareto_shared_ptr/)\<Q\>::value), **bool**\>::type [operator()](./operator_call/)(const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&, const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&) const | Összehasonlítja a [IComparable](../../system/icomparable/) interfészt nem megvalósító mutatótípusokat. |

## Lásd még

* Névtér [System::Collections::Generic::Details](../)
* Könyvtár [Aspose.Slides](../../)