---
title: TrimStart()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen öğeyi tiplenmiş bir span'ın başından kırpar.
type: docs
weight: 391
url: /tr/system.memoryextensions/trimstart/
---
## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<T\>\&, const T\&) function

Belirtilen öğeyi tiplenmiş bir span'ın başından kırpar.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimStart(const ReadOnlySpan<T> &span, const T &trimElement)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Span içindeki öğelerin tipi |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Kırpılacak span |
| trimElement | const T\& | Kırpılacak öğe |

### Dönüş Değeri

Başından belirtilen öğe kırpılmış yeni bir span

## System::MemoryExtensions::TrimStart(Span\<T\>\&, const T\&) function

Belirtilen öğeyi değiştirilebilir tiplenmiş bir span'ın başından kırpar.

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimStart(Span<T> &span, const T &trimElement)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Span içindeki öğelerin tipi |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | Kırpılacak değiştirilebilir span |
| trimElement | const T\& | Kırpılacak öğe |

### Dönüş Değeri

Başından belirtilen öğe kırpılmış yeni bir span

## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function

Belirtilen öğeleri tiplenmiş bir span'ın başından kırpar.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimStart(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &trimElements)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Span içindeki öğelerin tipi |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Kırpılacak span |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Kırpılacak öğeler |

### Dönüş Değeri

Başından belirtilen öğeler kırpılmış yeni bir span

## System::MemoryExtensions::TrimStart(Span\<T\>\&, const ReadOnlySpan\<T\>\&) function

Belirtilen öğeleri değiştirilebilir tiplenmiş bir span'ın başından kırpar.

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimStart(Span<T> &span, const ReadOnlySpan<T> &trimElements)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Span içindeki öğelerin tipi |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | Kırpılacak değiştirilebilir span |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Kırpılacak öğeler |

### Dönüş Değeri

Başından belirtilen öğeler kırpılmış yeni bir span

## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<char16_t\>\&) function

Boşluk karakterlerini bir karakter span'ının başından kırpar.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimStart(const ReadOnlySpan<char16_t> &span)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Kırpılacak karakter span'ı |

### Dönüş Değeri

Başından boşluk karakterleri kırpılmış yeni bir span

## System::MemoryExtensions::TrimStart(Span\<char16_t\>\&) function

Boşluk karakterlerini değiştirilebilir bir karakter span'ının başından kırpar.

```cpp
Span<char16_t> System::MemoryExtensions::TrimStart(Span<char16_t> &span)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | Kırpılacak değiştirilebilir karakter span'ı |

### Dönüş Değeri

Başından boşluk karakterleri kırpılmış yeni bir span

## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<char16_t\>\&, char16_t) function

Belirtilen karakteri bir karakter span'ının başından kırpar.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimStart(const ReadOnlySpan<char16_t> &span, char16_t trimchar)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Kırpılacak karakter span'ı |
| trimchar | char16_t | Kırpılacak karakter |

### Dönüş Değeri

Başından belirtilen karakter kırpılmış yeni bir span

## System::MemoryExtensions::TrimStart(Span\<char16_t\>\&, char16_t) function

Belirtilen karakteri değiştirilebilir bir karakter span'ının başından kırpar.

```cpp
Span<char16_t> System::MemoryExtensions::TrimStart(Span<char16_t> &span, char16_t trimchar)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | Kırpılacak değiştirilebilir karakter span'ı |
| trimchar | char16_t | Kırpılacak karakter |

### Dönüş Değeri

Başından belirtilen karakter kırpılmış yeni bir span

## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&) function

Belirtilen karakterleri bir karakter span'ının başından kırpar.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimStart(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &trimchars)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Kırpılacak karakter span'ı |
| trimchars | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Kırpılacak karakterler |

### Dönüş Değeri

Başından belirtilen karakterler kırpılmış yeni bir span

## System::MemoryExtensions::TrimStart(Span\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&) function

Belirtilen karakterleri değiştirilebilir bir karakter span'ının başından kırpar.

```cpp
Span<char16_t> System::MemoryExtensions::TrimStart(Span<char16_t> &span, const ReadOnlySpan<char16_t> &trimchars)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | Kırpılacak değiştirilebilir karakter span'ı |
| trimchars | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Kırpılacak karakterler |

### Dönüş Değeri

Başından belirtilen karakterler kırpılmış yeni bir span

## Ayrıca Bakınız

* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)