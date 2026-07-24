---
title: Compare()
second_title: Aspose.Slides for C++ API Referansı
description: İki akıllı işaretçiyi karşılaştırır.
type: docs
weight: 1
url: /tr/system.memoryextensions.details/compare/
---
## System::MemoryExtensions::Details::Compare(const SharedPtr\<T\>\&, const SharedPtr\<U\>\&) function


İki akıllı işaretçiyi karşılaştırır.

```cpp
template<typename T,typename U> int32_t System::MemoryExtensions::Details::Compare(const SharedPtr<T> &a, const SharedPtr<U> &b)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Type of first smart pointer |
| U | Type of second smart pointer |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | const [SharedPtr](../../system/sharedptr/)\<T\>\& | First smart pointer |
| b | const [SharedPtr](../../system/sharedptr/)\<U\>\& | Second smart pointer |

### Dönüş Değeri

[Comparison](../../system/comparison/) sonuç (eşit ise 0, a < b ise -1, a > b ise 1)

## System::MemoryExtensions::Details::Compare(const T\&, const T\&) function


İki aritmetik değeri karşılaştırır.

```cpp
template<typename T> int32_t System::MemoryExtensions::Details::Compare(const T &a, const T &b)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Arithmetic type |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | const T\& | First value |
| b | const T\& | Second value |

### Dönüş Değeri

[Comparison](../../system/comparison/) sonuç (eşit ise 0, a < b ise -1, a > b ise 1)

## System::MemoryExtensions::Details::Compare(const SharedPtr\<T\>\&, const U\&) function


Bir akıllı işaretçiyi bir değerle karşılaştırır.

```cpp
template<typename T,typename U> int32_t System::MemoryExtensions::Details::Compare(const SharedPtr<T> &a, const U &b)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Type pointed to by smart pointer |
| U | Type of value |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | const [SharedPtr](../../system/sharedptr/)\<T\>\& | Smart pointer |
| b | const U\& | Value |

### Dönüş Değeri

[Comparison](../../system/comparison/) sonuç (eşit ise 0, a < b ise -1, a > b ise 1)

## Ayrıca Bakınız

* Typedef [SharedPtr](../../system/sharedptr/)
* Namespace [System::MemoryExtensions::Details](../)
* Library [Aspose.Slides](../../)