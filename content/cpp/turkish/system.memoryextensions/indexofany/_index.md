---
title: IndexOfAny()
second_title: Aspose.Slides for C++ API Referansı
description: ReadOnlySpan<T> içinde belirtilen iki değerden herhangi birinin ilk oluşumunun dizinini bulur
type: docs
weight: 157
url: /tr/system.memoryextensions/indexofany/
---
## System::MemoryExtensions::IndexOfAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&) function

ReadOnlySpan<T> içinde iki belirtilen değerden herhangi birinin ilk oluşumunun dizinini bulur

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Span içindeki öğelerin tipi |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Arama yapılacak span |
| value0 | const T\& | Aranacak ilk değer |
| value1 | const T\& | Aranacak ikinci değer |

### Dönüş Değeri

Bulunamazsa -1 dönen, sıfır tabanlı ilk oluşumun dizini

## System::MemoryExtensions::IndexOfAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) function

ReadOnlySpan<T> içinde üç belirtilen değerden herhangi birinin ilk oluşumunun dizinini bulur

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Span içindeki öğelerin tipi |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Arama yapılacak span |
| value0 | const T\& | Aranacak ilk değer |
| value1 | const T\& | Aranacak ikinci değer |
| value2 | const T\& | Aranacak üçüncü değer |

### Dönüş Değeri

Bulunamazsa -1 dönen, sıfır tabanlı ilk oluşumun dizini

## System::MemoryExtensions::IndexOfAny(const Span\<T\>\&, const T\&, const T\&) function

Span<T> içinde iki belirtilen değerden herhangi birinin ilk oluşumunun dizinini bulur

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAny(const Span<T> &span, const T &value0, const T &value1)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Span içindeki öğelerin tipi |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Arama yapılacak span |
| value0 | const T\& | Aranacak ilk değer |
| value1 | const T\& | Aranacak ikinci değer |

### Dönüş Değeri

Bulunamazsa -1 dönen, sıfır tabanlı ilk oluşumun dizini

## System::MemoryExtensions::IndexOfAny(const Span\<T\>\&, const T\&, const T\&, const T\&) function

Span<T> içinde üç belirtilen değerden herhangi birinin ilk oluşumunun dizinini bulur

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAny(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Span içindeki öğelerin tipi |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Arama yapılacak span |
| value0 | const T\& | Aranacak ilk değer |
| value1 | const T\& | Aranacak ikinci değer |
| value2 | const T\& | Aranacak üçüncü değer |

### Dönüş Değeri

Bulunamazsa -1 dönen, sıfır tabanlı ilk oluşumun dizini

## System::MemoryExtensions::IndexOfAny(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function

Bir span içindeki herhangi bir değerin başka bir ReadOnlySpan<T> içindeki ilk oluşumunun dizinini bulur

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAny(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Span'lerdeki öğelerin tipi |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Arama yapılacak span |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Aranacak değerleri içeren span |

### Dönüş Değeri

Bulunamazsa -1 dönen, sıfır tabanlı ilk oluşumun dizini

## System::MemoryExtensions::IndexOfAny(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function

Bir span içindeki herhangi bir değerin Span<T> içinde ilk oluşumunun dizinini bulur

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAny(const Span<T> &span, const ReadOnlySpan<T> &values)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Span'lerdeki öğelerin tipi |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Arama yapılacak span |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Aranacak değerleri içeren span |

### Dönüş Değeri

Bulunamazsa -1 dönen, sıfır tabanlı ilk oluşumun dizini

## Ayrıca Bakınız

* Sınıf [ReadOnlySpan](../../system/readonlyspan/)
* Sınıf [Span](../../system/span/)
* Ad Alanı [System::MemoryExtensions](../)
* Kütüphane [Aspose.Slides](../../)