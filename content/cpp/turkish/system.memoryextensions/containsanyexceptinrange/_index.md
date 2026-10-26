---
title: ContainsAnyExceptInRange()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen aralık dışındaki herhangi bir öğeyi içerip içermediğini kontrol eder.
type: docs
weight: 79
url: /tr/system.memoryextensions/containsanyexceptinrange/
---
## System::MemoryExtensions::ContainsAnyExceptInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) fonksiyon

Belirtilen aralık dışındaki herhangi bir öğeyi içerip içermediğini kontrol eder.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExceptInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Span içindeki öğelerin türü (karşılaştırılabilir olmalıdır) |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Aranacak span |
| lowInclusive | const T\& | Alt sınır (dâhil) |
| highInclusive | const T\& | Üst sınır (dâhil) |

### Dönüş Değeri

Aralık dışındaki herhangi bir öğe bulunursa doğru, aksi takdirde yanlış

## System::MemoryExtensions::ContainsAnyExceptInRange(const Span\<T\>\&, const T\&, const T\&) fonksiyon

Değiştirilebilir bir span'ın belirtilen aralık dışındaki herhangi bir öğeyi içerip içermediğini kontrol eder.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExceptInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Span içindeki öğelerin türü (karşılaştırılabilir olmalıdır) |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Aranacak değiştirilebilir span |
| lowInclusive | const T\& | Alt sınır (dâhil) |
| highInclusive | const T\& | Üst sınır (dâhil) |

### Dönüş Değeri

Aralık dışındaki herhangi bir öğe bulunursa doğru, aksi takdirde yanlış

## Ayrıca Bakınız

* Sınıf [ReadOnlySpan](../../system/readonlyspan/)
* Sınıf [Span](../../system/span/)
* Ad alanı [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)