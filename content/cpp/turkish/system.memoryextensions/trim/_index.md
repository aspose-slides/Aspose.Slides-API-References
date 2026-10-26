---
title: Trim()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen öğeyi tiplenmiş bir span'ın her iki ucundan da kırpar.
type: docs
weight: 365
url: /tr/system.memoryextensions/trim/
---
## System::MemoryExtensions::Trim(const ReadOnlySpan\<T\>\&, T) fonksiyon


Belirtilen öğeyi tiplenmiş bir span'ın her iki ucundan da kırpar.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::Trim(const ReadOnlySpan<T> &span, T trimElement)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Span'daki öğelerin türü |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Kırpılacak span |
| trimElement | T | Kırpılacak öğe |

### Dönüş Değeri

Belirtilen öğe her iki uçtan da kırpılmış yeni bir span


## System::MemoryExtensions::Trim(Span\<T\>\&, T) fonksiyon


Belirtilen öğeyi değiştirilebilir tiplenmiş bir span'ın her iki ucundan da kırpar.

```cpp
template<typename T> Span<T> System::MemoryExtensions::Trim(Span<T> &span, T trimElement)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Span'daki öğelerin türü |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | Kırpılacak değiştirilebilir span |
| trimElement | T | Kırpılacak öğe |

### Dönüş Değeri

Belirtilen öğe her iki uçtan da kırpılmış yeni bir span


## System::MemoryExtensions::Trim(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) fonksiyon


Belirtilen öğeleri tiplenmiş bir span'ın her iki ucundan da kırpar.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::Trim(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &trimElements)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Span'daki öğelerin türü |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Kırpılacak span |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Kırpılacak öğeler |

### Dönüş Değeri

Belirtilen öğeler her iki uçtan da kırpılmış yeni bir span


## System::MemoryExtensions::Trim(Span\<T\>\&, const ReadOnlySpan\<T\>\&) fonksiyon


Belirtilen öğeleri değiştirilebilir tiplenmiş bir span'ın her iki ucundan da kırpar.

```cpp
template<typename T> Span<T> System::MemoryExtensions::Trim(Span<T> &span, const ReadOnlySpan<T> &trimElements)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Span'daki öğelerin türü |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | Kırpılacak değiştirilebilir span |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Kırpılacak öğeler |

### Dönüş Değeri

Belirtilen öğeler her iki uçtan da kırpılmış yeni bir span


## System::MemoryExtensions::Trim(const ReadOnlySpan\<char16_t\>\&) fonksiyon


Karakter spanının her iki ucundan da boşluk karakterlerini kırpar.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::Trim(const ReadOnlySpan<char16_t> &span)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Kırpılacak karakter spanı |

### Dönüş Değeri

Boşluk karakterleri her iki uçtan da kırpılmış yeni bir span


## System::MemoryExtensions::Trim(Span\<char16_t\>\&) fonksiyon


Değiştirilebilir karakter spanının her iki ucundan da boşluk karakterlerini kırpar.

```cpp
Span<char16_t> System::MemoryExtensions::Trim(Span<char16_t> &span)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | Kırpılacak değiştirilebilir karakter spanı |

### Dönüş Değeri

Boşluk karakterleri her iki uçtan da kırpılmış yeni bir span


## Ayrıca Bakınız

* Sınıf [ReadOnlySpan](../../system/readonlyspan/)
* Sınıf [Span](../../system/span/)
* İsim Uzayı [System::MemoryExtensions](../)
* Kütüphane [Aspose.Slides](../../)