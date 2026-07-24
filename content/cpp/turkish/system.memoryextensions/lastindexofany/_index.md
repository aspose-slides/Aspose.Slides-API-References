---
title: LastIndexOfAny()
second_title: Aspose.Slides for C++ API Referansı
description: Bir span içinde belirtilen üç değerden herhangi birinin son ortaya çıkışını bulur.
type: docs
weight: 222
url: /tr/system.memoryextensions/lastindexofany/
---
## System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) function

Belirtilen üç değerden herhangi birinin bir span içinde son ortaya çıkışını bulur.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```

### Template parameters

| Parametre | Açıklama |
| --- | --- |
| T | Span içindeki öğelerin tipi |

### Arguments

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Arama yapılacak span |
| value0 | const T\& | Aranacak ilk değer |
| value1 | const T\& | Aranacak ikinci değer |
| value2 | const T\& | Aranacak üçüncü değer |

### Return Value

Son oluşun sıfır tabanlı indeksi, bulunamazsa -1

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const T\&, const T\&, const T\&) function

Belirtilen üç değerden herhangi birinin değiştirilebilir bir span içinde son ortaya çıkışını bulur.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```

### Template parameters

| Parametre | Açıklama |
| --- | --- |
| T | Span içindeki öğelerin tipi |

### Arguments

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Arama yapılacak span |
| value0 | const T\& | Aranacak ilk değer |
| value1 | const T\& | Aranacak ikinci değer |
| value2 | const T\& | Aranacak üçüncü değer |

### Return Value

Son oluşun sıfır tabanlı indeksi, bulunamazsa -1

## System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&) function

Belirtilen iki değerden herhangi birinin bir span içinde son ortaya çıkışını bulur.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```

### Template parameters

| Parametre | Açıklama |
| --- | --- |
| T | Span içindeki öğelerin tipi |

### Arguments

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Arama yapılacak span |
| value0 | const T\& | Aranacak ilk değer |
| value1 | const T\& | Aranacak ikinci değer |

### Return Value

Son oluşun sıfır tabanlı indeksi, bulunamazsa -1

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const T\&, const T\&) function

Belirtilen iki değerden herhangi birinin değiştirilebilir bir span içinde son ortaya çıkışını bulur.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const T &value0, const T &value1)
```

### Template parameters

| Parametre | Açıklama |
| --- | --- |
| T | Span içindeki öğelerin tipi |

### Arguments

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Arama yapılacak span |
| value0 | const T\& | Aranacak ilk değer |
| value1 | const T\& | Aranacak ikinci değer |

### Return Value

Son oluşun sıfır tabanlı indeksi, bulunamazsa -1

## System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function

Bir diziden herhangi bir değerin bir span içinde son ortaya çıkışını bulur.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```

### Template parameters

| Parametre | Açıklama |
| --- | --- |
| T | Span içindeki öğelerin tipi |

### Arguments

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Arama yapılacak span |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Aranacak değer dizisi |

### Return Value

Son oluşun sıfır tabanlı indeksi, bulunamazsa -1

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function

Bir diziden herhangi bir değerin değiştirilebilir bir span içinde son ortaya çıkışını bulur.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const ReadOnlySpan<T> &values)
```

### Template parameters

| Parametre | Açıklama |
| --- | --- |
| T | Span içindeki öğelerin tipi |

### Arguments

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Arama yapılacak span |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Aranacak değer dizisi |

### Return Value

Son oluşun sıfır tabanlı indeksi, bulunamazsa -1

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const Span\<T\>\&) function

Değiştirilebilir bir diziden herhangi bir değerin değiştirilebilir bir span içinde son ortaya çıkışını bulur.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const Span<T> &values)
```

### Template parameters

| Parametre | Açıklama |
| --- | --- |
| T | Span içindeki öğelerin tipi |

### Arguments

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Arama yapılacak span |
| values | const [Span](../../system/span/)\<T\>\& | Aranacak değer dizisi |

### Return Value

Son oluşun sıfır tabanlı indeksi, bulunamazsa -1

## See Also

* Sınıf [ReadOnlySpan](../../system/readonlyspan/)
* Sınıf [Span](../../system/span/)
* Ad alanı [System::MemoryExtensions](../)
* Kütüphane [Aspose.Slides](../../)