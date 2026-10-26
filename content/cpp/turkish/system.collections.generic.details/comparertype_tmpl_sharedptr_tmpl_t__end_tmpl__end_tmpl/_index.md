---
title: ComparerType< SharedPtr< T > >
second_title: Aspose.Slides için C++ API Referansı
description: 'less' semantiği kullanarak elemanları karşılaştırır.
type: docs
weight: 157
url: /tr/system.collections.generic.details/comparertype_tmpl_sharedptr_tmpl_t__end_tmpl__end_tmpl/
---
## ComparerType< SharedPtr< T > > struct

Elemanları 'less' semantiği kullanarak karşılaştırır.

```cpp
template<typename T>class ComparerType< SharedPtr< T > >
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Karşılaştırılan elemanların tipi. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| std::enable_if\<std::is_base_of\<[System::IComparable](../../system/icomparable/)\<[System::SharedPtr](../../system/sharedptr/)\<Q\>\>, Q\>::value||[has_method_compareto_shared_ptr](../has_method_compareto_shared_ptr/)\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&, const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&) const | [IComparable](../../system/icomparable/) arayüzünü uygulayan işaretçi tiplerini karşılaştırır. |
| std::enable_if<\!(std::is_base_of\<[System::IComparable](../../system/icomparable/)\<[System::SharedPtr](../../system/sharedptr/)\<Q\>\>, Q\>::value||[has_method_compareto_shared_ptr](../has_method_compareto_shared_ptr/)\<Q\>::value), **bool**\>::type [operator()](./operator_call/)(const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&, const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&) const | [IComparable](../../system/icomparable/) arayüzünü uygulamayan işaretçi tiplerini karşılaştırır. |

## Ayrıca Bakınız

* Ad alanı [System::Collections::Generic::Details](../)
* Kütüphane [Aspose.Slides](../../)