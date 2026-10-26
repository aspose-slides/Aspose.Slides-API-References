---
title: AsSpan()
second_title: Aspose.Slides for C++ API Referansı
description: Bir diziden bir span oluşturur.
type: docs
weight: 1
url: /tr/system.memoryextensions/asspan/
---
## System::MemoryExtensions::AsSpan(const ArrayPtr\<T\>\&, int32_t, int32_t) fonksiyon


Bir diziden bir span oluşturur.

```cpp
template<typename T> Span<T> System::MemoryExtensions::AsSpan(const ArrayPtr<T> &array, int32_t start=0, int32_t length=-1)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Dizideki öğelerin türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| array | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | Kaynak dizi. |
| start | **int32_t** | Dizideki başlangıç indeksi. |
| length | **int32_t** | Span'in uzunluğu. |

### Dönüş Değeri

Belirtilen dizi bölümünü kapsayan Span<T>.

## System::MemoryExtensions::AsSpan(const String\&, int32_t, int32_t) fonksiyon


Bir dizgiden salt okunur bir span oluşturur.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::AsSpan(const String &text, int32_t start=0, int32_t length=-1)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| text | const [String](../../system/string/)\& | Kaynak dizgi. |
| start | **int32_t** | Dizgideki başlangıç indeksi. |
| length | **int32_t** | Span'in uzunluğu. |

### Dönüş Değeri

Belirtilen dizgi bölümünü kapsayan ReadOnlySpan<char16_t>.

## Ayrıca Bakınız

* Tip Tanımı [ArrayPtr](../../system/arrayptr/)
* Sınıf [Span](../../system/span/)
* Sınıf [ReadOnlySpan](../../system/readonlyspan/)
* Sınıf [String](../../system/string/)
* İsim alanı [System::MemoryExtensions](../)
* Kütüphane [Aspose.Slides](../../)