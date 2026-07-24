---
title: ContainsAny()
second_title: Aspose.Slides C++ API Referansı
description: Okunabilir bir span iki değerden herhangi birini içerip içermediğini kontrol eder.
type: docs
weight: 53
url: /tr/system.memoryextensions/containsany/
---
## System::MemoryExtensions::ContainsAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&) fonksiyon


Okunabilir bir span iki değerden herhangi birini içerip içermediğini kontrol eder.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Span içindeki elemanların tipi |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | İçinde aranacak span |
| value0 | const T\& | Aranacak ilk değer |
| value1 | const T\& | Aranacak ikinci değer |

### Dönüş Değeri

true eğer değerlerden biri span içinde bulunursa, aksi takdirde false

## System::MemoryExtensions::ContainsAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) fonksiyon


Okunabilir bir span üç değerden herhangi birini içerip içermediğini kontrol eder.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Span içindeki elemanların tipi |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | İçinde aranacak span |
| value0 | const T\& | Aranacak ilk değer |
| value1 | const T\& | Aranacak ikinci değer |
| value2 | const T\& | Aranacak üçüncü değer |

### Dönüş Değeri

true eğer değerlerden biri span içinde bulunursa, aksi takdirde false

## System::MemoryExtensions::ContainsAny(const Span\<T\>\&, const T\&, const T\&) fonksiyon


Değiştirilebilir bir span iki değerden herhangi birini içerip içermediğini kontrol eder.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const Span<T> &span, const T &value0, const T &value1)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Span içindeki elemanların tipi |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | İçinde aranacak değiştirilebilir span |
| value0 | const T\& | Aranacak ilk değer |
| value1 | const T\& | Aranacak ikinci değer |

### Dönüş Değeri

true eğer değerlerden biri span içinde bulunursa, aksi takdirde false

## System::MemoryExtensions::ContainsAny(const Span\<T\>\&, const T\&, const T\&, const T\&) fonksiyon


Değiştirilebilir bir span üç değerden herhangi birini içerip içermediğini kontrol eder.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Span içindeki elemanların tipi |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | İçinde aranacak değiştirilebilir span |
| value0 | const T\& | Aranacak ilk değer |
| value1 | const T\& | Aranacak ikinci değer |
| value2 | const T\& | Aranacak üçüncü değer |

### Dönüş Değeri

true eğer değerlerden biri span içinde bulunursa, aksi takdirde false

## System::MemoryExtensions::ContainsAny(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) fonksiyon


Okunabilir bir span, başka bir span’dan herhangi bir değeri içerip içermediğini kontrol eder.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Span’ların eleman tipi |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | İçinde aranacak span |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Aranacak değerlerin span’i |

### Dönüş Değeri

true eğer values içindeki herhangi bir değer span içinde bulunursa, aksi takdirde false

## System::MemoryExtensions::ContainsAny(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) fonksiyon


Değiştirilebilir bir span, okunabilir bir span’dan herhangi bir değeri içerip içermediğini kontrol eder.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const Span<T> &span, const ReadOnlySpan<T> &values)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Span’ların eleman tipi |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | İçinde aranacak değiştirilebilir span |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Aranacak değerlerin okunabilir span’i |

### Dönüş Değeri

true eğer values içindeki herhangi bir değer span içinde bulunursa, aksi takdirde false

## İlgili

* Sınıf [ReadOnlySpan](../../system/readonlyspan/)
* Sınıf [Span](../../system/span/)
* Ad Alanı [System::MemoryExtensions](../)
* Kütüphane [Aspose.Slides](../../)