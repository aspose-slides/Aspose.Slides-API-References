---
title: ComparerType< SharedPtr< T > >
second_title: Referensi API Aspose.Slides untuk C++
description: Membandingkan elemen menggunakan semantik 'less'.
type: docs
weight: 157
url: /id/system.collections.generic.details/comparertype_tmpl_sharedptr_tmpl_t__end_tmpl__end_tmpl/
---
## ComparerType< SharedPtr< T > > struct

Membandingkan elemen menggunakan semantik 'less'.

```cpp
template<typename T>class ComparerType< SharedPtr< T > >
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe elemen yang dibandingkan. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| std::enable_if\<std::is_base_of\<[System::IComparable](../../system/icomparable/)\<[System::SharedPtr](../../system/sharedptr/)\<Q\>\>, Q\>::value||[has_method_compareto_shared_ptr](../has_method_compareto_shared_ptr/)\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&, const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&) const | Membandingkan tipe pointer yang mengimplementasikan antarmuka [IComparable](../../system/icomparable/). |
| std::enable_if<\!(std::is_base_of\<[System::IComparable](../../system/icomparable/)\<[System::SharedPtr](../../system/sharedptr/)\<Q\>\>, Q\>::value||[has_method_compareto_shared_ptr](../has_method_compareto_shared_ptr/)\<Q\>::value), **bool**\>::type [operator()](./operator_call/)(const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&, const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&) const | Membandingkan tipe pointer yang tidak mengimplementasikan antarmuka [IComparable](../../system/icomparable/). |

## Lihat Juga

* Namespace [System::Collections::Generic::Details](../)
* Perpustakaan [Aspose.Slides](../../)