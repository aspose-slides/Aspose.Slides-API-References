---
title: ContainsAnyInRange()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen aralıkta herhangi bir öğenin olup olmadığını yalnızca okunabilir bir span içinde kontrol eder.
type: docs
weight: 92
url: /tr/system.memoryextensions/containsanyinrange/
---
## System::MemoryExtensions::ContainsAnyInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) fonksiyon

Belirtilen aralıkta herhangi bir öğenin olup olmadığını yalnızca okunabilir bir span içinde kontrol eder.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Span içindeki öğelerin türü (karşılaştırılabilir olmalıdır) |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Arama yapılacak span |
| lowInclusive | const T\& | Alt sınır (dahil) |
| highInclusive | const T\& | Üst sınır (dahil) |

### Dönüş Değeri

Aralık içinde herhangi bir öğe bulunursa true, aksi takdirde false

## System::MemoryExtensions::ContainsAnyInRange(const Span\<T\>\&, const T\&, const T\&) fonksiyon

Belirtilen aralıkta herhangi bir öğenin olup olmadığını değiştirilebilir bir span içinde kontrol eder.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Span içindeki öğelerin türü (karşılaştırılabilir olmalıdır) |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Arama yapılacak değiştirilebilir span |
| lowInclusive | const T\& | Alt sınır (dahil) |
| highInclusive | const T\& | Üst sınır (dahil) |

### Dönüş Değeri

Aralık içinde herhangi bir öğe bulunursa true, aksi takdirde false

## İlgili

* Sınıf [ReadOnlySpan](../../system/readonlyspan/)
* Sınıf [Span](../../system/span/)
* Ad alanı [System::MemoryExtensions](../)
* Kütüphane [Aspose.Slides](../../)