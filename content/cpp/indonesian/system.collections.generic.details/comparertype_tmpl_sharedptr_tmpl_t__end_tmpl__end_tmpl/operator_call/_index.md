---
title: operator()()
second_title: Aspose.Slides untuk C++ Referensi API
description: Membandingkan tipe pointer yang mengimplementasikan antarmuka IComparable.
type: docs
weight: 1
url: /id/system.collections.generic.details/comparertype_tmpl_sharedptr_tmpl_t__end_tmpl__end_tmpl/operator_call/
---
## ComparerType< SharedPtr< T > >::operator()(const System::SharedPtr\<Q\>\&, const System::SharedPtr\<Q\>\&) const metode

Membandingkan tipe pointer yang mengimplementasikan antarmuka [IComparable](../../../system/icomparable/).

```cpp
template<typename Q> std::enable_if<std::is_base_of<System::IComparable<System::SharedPtr<Q>>, Q>::value||has_method_compareto_shared_ptr<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<SharedPtr<T>>::operator()(const System::SharedPtr<Q> &a, const System::SharedPtr<Q> &b) const
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| Q | Tipe untuk dibandingkan. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| a | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | Nilai LHS. |
| b | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | Nilai RHS. |

### Nilai Kembali

True jika **a** dianggap lebih kecil daripada **b**, false sebaliknya.

## ComparerType< SharedPtr< T > >::operator()(const System::SharedPtr\<Q\>\&, const System::SharedPtr\<Q\>\&) const metode

Membandingkan tipe pointer yang tidak mengimplementasikan antarmuka [IComparable](../../../system/icomparable/).

```cpp
template<typename Q> std::enable_if<!(std::is_base_of<System::IComparable<System::SharedPtr<Q>>, Q>::value||has_method_compareto_shared_ptr<Q>::value), bool>::type System::Collections::Generic::Details::ComparerType<SharedPtr<T>>::operator()(const System::SharedPtr<Q> &a, const System::SharedPtr<Q> &b) const
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| Q | Tipe untuk dibandingkan. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| a | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | Nilai LHS. |
| b | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | Nilai RHS. |

### Nilai Kembali

True jika **a** dianggap lebih kecil daripada **b**, false sebaliknya.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IComparable](../../../system/icomparable/)
* Struct [has_method_compareto_shared_ptr](../../has_method_compareto_shared_ptr/)
* Struct [ComparerType< SharedPtr< T > >](../)
* Namespace [System::Collections::Generic::Details](../../)
* Library [Aspose.Slides](../../../)