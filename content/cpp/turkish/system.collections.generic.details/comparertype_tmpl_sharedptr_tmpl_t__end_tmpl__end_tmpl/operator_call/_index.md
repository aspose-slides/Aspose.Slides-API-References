---
title: operator()()
second_title: Aspose.Slides for C++ API Referansı
description: IComparable arayüzünü uygulayan işaretçi türlerini karşılaştırır.
type: docs
weight: 1
url: /tr/system.collections.generic.details/comparertype_tmpl_sharedptr_tmpl_t__end_tmpl__end_tmpl/operator_call/
---
## ComparerType< SharedPtr< T > >::operator()(const System::SharedPtr\<Q\>\&, const System::SharedPtr\<Q\>\&) const method

[IComparable](../../../system/icomparable/) arayüzünü uygulayan işaretçi türlerini karşılaştırır.

```cpp
template<typename Q> std::enable_if<std::is_base_of<System::IComparable<System::SharedPtr<Q>>, Q>::value||has_method_compareto_shared_ptr<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<SharedPtr<T>>::operator()(const System::SharedPtr<Q> &a, const System::SharedPtr<Q> &b) const
```

### Template parameters

| Parametre | Açıklama |
| --- | --- |
| Q | Karşılaştırılacak tip. |

### Arguments

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | Sol taraf değeri. |
| b | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | Sağ taraf değeri. |

### Return Value

**a**, **b**'den küçük kabul edilirse doğru, aksi takdirde yanlış.

## ComparerType< SharedPtr< T > >::operator()(const System::SharedPtr\<Q\>\&, const System::SharedPtr\<Q\>\&) const method

[IComparable](../../../system/icomparable/) arayüzünü uygulamayan işaretçi türlerini karşılaştırır.

```cpp
template<typename Q> std::enable_if<!(std::is_base_of<System::IComparable<System::SharedPtr<Q>>, Q>::value||has_method_compareto_shared_ptr<Q>::value), bool>::type System::Collections::Generic::Details::ComparerType<SharedPtr<T>>::operator()(const System::SharedPtr<Q> &a, const System::SharedPtr<Q> &b) const
```

### Template parameters

| Parametre | Açıklama |
| --- | --- |
| Q | Karşılaştırılacak tip. |

### Arguments

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | Sol taraf değeri. |
| b | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | Sağ taraf değeri. |

### Return Value

**a**, **b**'den küçük kabul edilirse doğru, aksi takdirde yanlış.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IComparable](../../../system/icomparable/)
* Struct [has_method_compareto_shared_ptr](../../has_method_compareto_shared_ptr/)
* Struct [ComparerType< SharedPtr< T > >](../)
* Ad alanı [System::Collections::Generic::Details](../../)
* Library [Aspose.Slides](../../../)