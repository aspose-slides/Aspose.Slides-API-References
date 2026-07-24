---
title: Overlaps()
second_title: Aspose.Slides for C++ API Referansı
description: İki ReadOnlySpan'in bellekte offset hesaplamadan çakışıp çakışmadığını belirler.
type: docs
weight: 274
url: /tr/system.memoryextensions/overlaps/
---
## System::MemoryExtensions::Overlaps(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) fonksiyon


İki ReadOnlySpan'in bellek içinde çakışıp çakışmadığını, ofset hesaplamadan belirler.

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Spans içindeki elemanların türü |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Çakışmayı kontrol etmek için ilk span |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Çakışmayı kontrol etmek için ikinci span |

### Dönüş Değeri

spans ortak bir bellek konumu paylaşıyorsa true, aksi takdirde false

## System::MemoryExtensions::Overlaps(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) fonksiyon


Bir [Span](../../system/span/) ve [ReadOnlySpan](../../system/readonlyspan/)'nin bellek içinde çakışıp çakışmadığını, ofset hesaplamadan belirler.

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const Span<T> &span, const ReadOnlySpan<T> &other)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Spans içindeki elemanların türü |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Çakışmayı kontrol etmek için [Span](../../system/span/) |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Çakışmayı kontrol etmek için [ReadOnlySpan](../../system/readonlyspan/) |

### Dönüş Değeri

spans ortak bir bellek konumu paylaşıyorsa true, aksi takdirde false

## System::MemoryExtensions::Overlaps(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&, int32_t\&) fonksiyon


İki ReadOnlySpan'in bellek içinde çakışıp çakışmadığını belirler ve ofseti hesaplar.

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other, int32_t &elementOffset)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Spans içindeki elemanların türü |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Çakışmayı kontrol etmek için ilk span |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Çakışmayı kontrol etmek için ikinci span |
| elementOffset | **int32_t**\& | Spans çakıştığında aralarındaki ofseti alan çıktı parametresi |

### Dönüş Değeri

spans ortak bir bellek konumu paylaşıyorsa true, aksi takdirde false

## System::MemoryExtensions::Overlaps(const Span\<T\>\&, const ReadOnlySpan\<T\>\&, int32_t\&) fonksiyon


Bir [Span](../../system/span/) ve [ReadOnlySpan](../../system/readonlyspan/)'nin bellek içinde çakışıp çakışmadığını belirler ve ofseti hesaplar.

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const Span<T> &span, const ReadOnlySpan<T> &other, int32_t &elementOffset)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Spans içindeki elemanların türü |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Çakışmayı kontrol etmek için [Span](../../system/span/) |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Çakışmayı kontrol etmek için [ReadOnlySpan](../../system/readonlyspan/) |
| elementOffset | **int32_t**\& | Spans çakıştığında aralarındaki ofseti alan çıktı parametresi |

### Dönüş Değeri

spans ortak bir bellek konumu paylaşıyorsa true, aksi takdirde false

## Ayrıca Bakınız

* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)