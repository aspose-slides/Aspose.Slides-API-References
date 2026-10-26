---
title: TrimEnd()
second_title: Aspose.Slides for C++ API Referansı
description: Tipli bir aralığın sonundan belirtilen öğeyi kırpar.
type: docs
weight: 378
url: /tr/system.memoryextensions/trimend/
---
## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<T\>\&, const T\&) fonksiyon

Belirtilen öğeyi tipli bir aralığın sonundan kırpar.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<T> &span, const T &trimElement)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Aralıktaki öğelerin tipi |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Kırpılacak aralık |
| trimElement | const T\& | Kırpılacak öğe |

### Dönüş Değeri

Sonundan belirtilen öğe kırpılmış yeni bir aralık

## System::MemoryExtensions::TrimEnd(Span\<T\>\&, const T\&) fonksiyon

Belirtilen öğeyi değiştirilebilir tipli bir aralığın sonundan kırpar.

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimEnd(Span<T> &span, const T &trimElement)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Aralıktaki öğelerin tipi |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | Kırpılacak değiştirilebilir aralık |
| trimElement | const T\& | Kırpılacak öğe |

### Dönüş Değeri

Sonundan belirtilen öğe kırpılmış yeni bir aralık

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) fonksiyon

Belirtilen öğeleri tipli bir aralığın sonundan kırpar.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &trimElements)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Aralıktaki öğelerin tipi |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Kırpılacak aralık |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Kırpılacak öğeler |

### Dönüş Değeri

Sonundan belirtilen öğeler kırpılmış yeni bir aralık

## System::MemoryExtensions::TrimEnd(Span\<T\>\&, const ReadOnlySpan\<T\>\&) fonksiyon

Belirtilen öğeleri değiştirilebilir tipli bir aralığın sonundan kırpar.

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimEnd(Span<T> &span, const ReadOnlySpan<T> &trimElements)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Aralıktaki öğelerin tipi |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | Kırpılacak değiştirilebilir aralık |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Kırpılacak öğeler |

### Dönüş Değeri

Sonundan belirtilen öğeler kırpılmış yeni bir aralık

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<char16_t\>\&) fonksiyon

Beyaz boşluk karakterlerini karakter aralığının sonundan kırpar.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<char16_t> &span)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Kırpılacak karakter aralığı |

### Dönüş Değeri

Sonundan boşluk karakterleri kaldırılmış yeni bir aralık

## System::MemoryExtensions::TrimEnd(Span\<char16_t\>\&) fonksiyon

Beyaz boşluk karakterlerini değiştirilebilir karakter aralığının sonundan kırpar.

```cpp
Span<char16_t> System::MemoryExtensions::TrimEnd(Span<char16_t> &span)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | Kırpılacak değiştirilebilir karakter aralığı |

### Dönüş Değeri

Sonundan boşluk karakterleri kaldırılmış yeni bir aralık

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<char16_t\>\&, char16_t) fonksiyon

Belirtilen karakteri karakter aralığının sonundan kırpar.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<char16_t> &span, char16_t trimchar)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Kırpılacak karakter aralığı |
| trimchar | char16_t | Kırpılacak karakter |

### Dönüş Değeri

Sonundan belirtilen karakter kırpılmış yeni bir aralık

## System::MemoryExtensions::TrimEnd(Span\<char16_t\>\&, char16_t) fonksiyon

Belirtilen karakteri değiştirilebilir karakter aralığının sonundan kırpar.

```cpp
Span<char16_t> System::MemoryExtensions::TrimEnd(Span<char16_t> &span, char16_t trimchar)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | Kırpılacak değiştirilebilir karakter aralığı |
| trimchar | char16_t | Kırpılacak karakter |

### Dönüş Değeri

Sonundan belirtilen karakter kırpılmış yeni bir aralık

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&) fonksiyon

Belirtilen karakterleri karakter aralığının sonundan kırpar.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &trimChars)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Kırpılacak karakter aralığı |
| trimChars | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Kırpılacak karakterler |

### Dönüş Değeri

Sonundan belirtilen karakterler kırpılmış yeni bir aralık

## System::MemoryExtensions::TrimEnd(Span\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&) fonksiyon

Belirtilen karakterleri değiştirilebilir karakter aralığının sonundan kırpar.

```cpp
Span<char16_t> System::MemoryExtensions::TrimEnd(Span<char16_t> &span, const ReadOnlySpan<char16_t> &trimchars)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | Kırpılacak değiştirilebilir karakter aralığı |
| trimchars | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Kırpılacak karakterler |

### Dönüş Değeri

Sonundan belirtilen karakterler kırpılmış yeni bir aralık

## İlgili

* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)