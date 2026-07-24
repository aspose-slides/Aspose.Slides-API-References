---
title: CompareOrdinal()
second_title: Aspose.Slides için C++ API Referansı
description: Less-equal-greater, iki dizeyi ordinal modda karşılaştırır.
type: docs
weight: 833
url: /tr/system/string/compareordinal/
---
## String::CompareOrdinal(const String\&, const String\&) yöntemi

Less-equal-greater, iki dizeyi ordinal modda karşılaştırır.

```cpp
static int System::String::CompareOrdinal(const String &strA, const String &strB)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| strA | const [String](../)\& | Karşılaştırılacak ilk dize. |
| strB | const [String](../)\& | Karşılaştırılacak ikinci dize. |

### Dönüş Değeri

İlk alt dize ikinci alt dizeden daha küçükse negatif değer, eşleşirse sıfır, aksi takdirde pozitif değer.

## String::CompareOrdinal(const String\&, int, const String\&, int, int) yöntemi

Less-equal-greater, iki dizeyi ordinal modda karşılaştırır.

```cpp
static int System::String::CompareOrdinal(const String &strA, int indexA, const String &strB, int indexB, int length)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| strA | const [String](../)\& | Karşılaştırılacak ilk dize. |
| indexA | int | İlk dize alt dizisinin başlangıcı. |
| strB | const [String](../)\& | Karşılaştırılacak ikinci dize. |
| indexB | int | İkinci dize alt dizisinin başlangıcı. |
| length | int | Karşılaştırılacak karakter sayısı. |

### Dönüş Değeri

İlk alt dize ikinci alt dizeden daha küçükse negatif değer, eşleşirse sıfır, aksi takdirde pozitif değer.

## İlgili

* Sınıf [String](../)
* Ad alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)