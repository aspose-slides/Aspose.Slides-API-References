---
title: LastIndexOfAny()
second_title: Aspose.Slides for C++ API Referansı
description: Geçilen karakterlerin herhangi birini tüm dize içinde geriye doğru arar. Son dize karakterini anyOf içindeki tüm karakterlerle karşılaştırır, ardından bir önceki karakteri ve bu şekilde devam eder. Bulunan ilk eşleşmenin dizinini döndürür.
type: docs
weight: 664
url: /tr/system/string/lastindexofany/
---
## String::LastIndexOfAny(const ArrayPtr\<char_t\>\&) const yöntem


Geçerli karakterlerin herhangi birini tüm dize içinde geriye doğru arar. Son dize karakterini anyOf içindeki tüm karakterlerle karşılaştırır, ardından bir önceki karakteri ve böyle devam eder. Bulunan ilk eşleşmenin dizinini döndürür.

```cpp
int System::String::LastIndexOfAny(const ArrayPtr<char_t> &anyOf) const
```


### Parametreler

| Parameter | Type | Description |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) aramak için karakterler. Sıra önemsizdir. |

### Dönüş Değeri

[Index](../../index/) son eşleşen karakterin dizini veya bulunamazsa -1.

## String::LastIndexOfAny(const ArrayPtr\<char_t\>\&, int32_t) const yöntem


Geçerli karakterlerin herhangi birini alt dize içinde geriye doğru arar. Son dize karakterini anyOf içindeki tüm karakterlerle karşılaştırır, ardından bir önceki karakteri ve böyle devam eder. Bulunan ilk eşleşmenin dizinini döndürür.

```cpp
int System::String::LastIndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex) const
```


### Parametreler

| Parameter | Type | Description |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) aramak için karakterler. Sıra önemsizdir. |
| startindex | **int32_t** | [Index](../../index/) aramaya başlanacak indeks. |

### Dönüş Değeri

[Index](../../index/) son eşleşen karakterin dizini veya bulunamazsa -1.

## String::LastIndexOfAny(const ArrayPtr\<char_t\>\&, int32_t, int32_t) const yöntem


Geçerli karakterlerin herhangi birini alt dize içinde geriye doğru arar. Son dize karakterini anyOf içindeki tüm karakterlerle karşılaştırır, ardından bir önceki karakteri ve böyle devam eder. Bulunan ilk eşleşmenin dizinini döndürür.

```cpp
int System::String::LastIndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex, int32_t count) const
```


### Parametreler

| Parameter | Type | Description |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) aramak için karakterler. Sıra önemsizdir. |
| startindex | **int32_t** | [Index](../../index/) aramaya başlanacak indeks. |
| count | **int32_t** | İçinde aranacak karakter sayısı. |

### Dönüş Değeri

[Index](../../index/) son eşleşen karakterin dizini veya bulunamazsa -1.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../arrayptr/)
* Sınıf [String](../)
* Ad alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)