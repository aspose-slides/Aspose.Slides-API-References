---
title: Interlocked
second_title: Aspose.Slides için C++ API Referansı
description: İş parçacığı güvenli işlemler için API sağlar. Bu, örnek hizmetleri olmayan statik bir türdür. Hiçbir şekilde onun örneklerini oluşturmayın.
type: docs
weight: 131
url: /tr/system.threading/interlocked/
---
## Interlocked sınıfı


İş parçacığı güvenli işlemler için API sağlar. Bu, örnek hizmetleri olmayan statik bir türdür. Hiçbir şekilde onun örneklerini oluşturmayın.

```cpp
class Interlocked
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| static **int32_t** [Add](./add/)(**int32_t**\&, **int32_t**) | Değeri atomik olarak artırır. |
| static **int64_t** [Add](./add/)(**int64_t**\&, **int64_t**) | Değeri atomik olarak artırır. |
| static std::enable_if\<IsSupportedInt\<T\>, T\>::type [CompareExchange](./compareexchange/)(T\&, T, T) | Değişken üzerindeki değeri karşılaştırmalı takas eder: değişkenin belirli bir değere eşit olup olmadığını kontrol eder ve sadece saklanan değer beklenenle eşleşiyorsa yeni değeri saklar. |
| static std::enable_if<\!IsSupportedInt\<T\>, T\>::type [CompareExchange](./compareexchange/)(T\&, T, T) | Değişken üzerindeki değeri karşılaştırmalı takas eder: değişkenin belirli bir değere eşit olup olmadığını kontrol eder ve sadece saklanan değer beklenenle eşleşiyorsa yeni değeri saklar. Uygulanmadı. |
| static **int32_t** [CompareExchange](./compareexchange/)(**int32_t**\&, **int32_t**, **int32_t**, **bool**\&) | Değişken üzerindeki değeri karşılaştırmalı takas eder: değişkenin belirli bir değere eşit olup olmadığını kontrol eder ve sadece saklanan değer beklenenle eşleşiyorsa yeni değeri saklar. |
| static **int32_t** [Decrement](./decrement/)(**int32_t**\&) | Değeri atomik olarak azaltır. |
| static **int64_t** [Decrement](./decrement/)(**int64_t**\&) | Değeri atomik olarak azaltır. |
| static std::enable_if\<IsSupportedInt\<T\>, T\>::type [Exchange](./exchange/)(T\&, T) | Değişken üzerindeki değeri takas eder: yeni değeri saklar ve saklamadan hemen önce değişkenin sahip olduğu değeri döndürür. |
| static std::enable_if<\!IsSupportedInt\<T\>, T\>::type [Exchange](./exchange/)(T\&, T) | Değişken üzerindeki değeri takas eder: yeni değeri saklar ve saklamadan hemen önce değişkenin sahip olduğu değeri döndürür. Uygulanmadı. |
| static **int32_t** [ExchangeAdd](./exchangeadd/)(**int32_t**\&, **int32_t**) | Değeri atomik olarak takas-ekleme prosedürüyle artırır. |
| static **int64_t** [ExchangeAdd](./exchangeadd/)(**int64_t**\&, **int64_t**) | Değeri atomik olarak takas-ekleme prosedürüyle artırır. |
| static **int32_t** [Increment](./increment/)(**int32_t**\&) | Değeri atomik olarak artırır. |
| static **int64_t** [Increment](./increment/)(**int64_t**\&) | Değeri atomik olarak artırır. |
| static **int64_t** [Read](./read/)(**int64_t**\&) | Atomik bir işlem olarak yüklenen 64-bit bir değer döndürür. |
## Ayrıca Bakınız

* Ad alanı [System::Threading](../)
* Kütüphane [Aspose.Slides](../../)