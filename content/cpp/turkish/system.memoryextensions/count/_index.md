---
title: Count()
second_title: Aspose.Slides for C++ API Referansı
description: Salt okunur bir aralıkta bir değerin kaç kez göründüğünü sayar.
type: docs
weight: 118
url: /tr/system.memoryextensions/count/
---
## System::MemoryExtensions::Count(const ReadOnlySpan\<T\>\&, const T\&) fonksiyon

Salt okunur bir aralıkta bir değerin kaç kez göründüğünü sayar.

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const ReadOnlySpan<T> &span, const T &value)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Aralıktaki öğelerin türü |

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Aranacak aralık |
| value | const T\& | Sayılacak değer |

### Dönüş Değeri

Değerin aralıkta kaç kez göründüğü

## System::MemoryExtensions::Count(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) fonksiyon

Bir ReadOnlySpan içinde başka bir ReadOnlySpan'in kaç kez göründüğünü sayar.

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Aralıkların içindeki öğelerin türü |

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Aranacak aralık |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Tekrarları sayılacak aralık |

### Dönüş Değeri

Değerin aralıkta kaç kez göründüğü

## System::MemoryExtensions::Count(const Span\<T\>\&, const T\&) fonksiyon

Bir Span\<T\> içinde tek bir değerin kaç kez göründüğünü sayar.

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const Span<T> &span, const T &value)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Span içindeki öğelerin türü |

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Aranacak aralık |
| value | const T\& | Tekrarları sayılacak değer |

### Dönüş Değeri

Değerin aralık içinde kaç kez tekrar ettiği

## System::MemoryExtensions::Count(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) fonksiyon

Bir Span\<T\> içinde bir ReadOnlySpan\<T\>'nin kaç kez göründüğünü sayar.

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const Span<T> &span, const ReadOnlySpan<T> &value)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Aralıkların içindeki öğelerin türü |

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Aranacak aralık |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Tekrarları sayılacak değerleri içeren aralık |

### Dönüş Değeri

Değer aralığının hedef aralık içinde kaç kez tekrar ettiği

## Ayrıca Bakınız

* Sınıf [ReadOnlySpan](../../system/readonlyspan/)
* Sınıf [Span](../../system/span/)
* Ad alanı [System::MemoryExtensions](../)
* Kütüphane [Aspose.Slides](../../)