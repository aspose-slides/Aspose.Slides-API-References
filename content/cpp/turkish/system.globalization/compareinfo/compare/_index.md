---
title: Compare()
second_title: Aspose.Slides for C++ API Referansı
description: Dizeleri karşılaştırır. Henüz uygulanmadı.
type: docs
weight: 66
url: /tr/system.globalization/compareinfo/compare/
---
## CompareInfo::Compare(const String\&, const String\&) const metot

Dizeleri karşılaştırır. Henüz uygulanmadı.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, const String &string2) const
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | Sol taraf dizesi. |
| string2 | const [String](../../../system/string/)\& | Sağ taraf dizesi. |

### Dönüş Değeri

LHS dizesi RHS dizesinden önce geliyorsa negatif değer, eşleşiyorlarsa sıfır, aksi takdirde pozitif değer.

## CompareInfo::Compare(const String\&, const String\&, CompareOptions) const metot

Dizeleri karşılaştırır. Yalnızca Ordinal ve OrdinalIgnoreCase modları desteklenir.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &a, const String &b, CompareOptions options) const
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | const [String](../../../system/string/)\& | Sol taraf dizesi. |
| b | const [String](../../../system/string/)\& | Sağ taraf dizesi. |
| options | [CompareOptions](../../compareoptions/) | [String](../../../system/string/) karşılaştırma türü. |

### Dönüş Değeri

LHS dizesi RHS dizesinden önce geliyorsa negatif değer, eşleşiyorlarsa sıfır, aksi takdirde pozitif değer.

## CompareInfo::Compare(const String\&, int, int, const String\&, int, int) const metot

Bir dize bölümünü ikinci dize bölümünde karşılaştırır. Henüz uygulanmadı.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, int length1, const String &string2, int offset2, int length2) const
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | İlk dize. |
| offset1 | int | **string1** içindeki karakterlerin başlangıç dizini. |
| length1 | int | **string1** içindeki karşılaştırılacak karakter sayısı. |
| string2 | const [String](../../../system/string/)\& | İkinci dize. |
| offset2 | int | **string2** içindeki karakterlerin başlangıç dizini. |
| length2 | int | **string2** içindeki karşılaştırılacak karakter sayısı. |

### Dönüş Değeri

LHS dizesi RHS dizesinden önce geliyorsa negatif değer, eşleşiyorlarsa sıfır, aksi takdirde pozitif değer.

## CompareInfo::Compare(const String\&, int, const String\&, int, CompareOptions) const metot

Bir dize son bölümünü ikinci dize son bölümüyle dize karşılaştırma yöntemlerini kullanarak karşılaştırır. Henüz uygulanmadı.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, const String &string2, int offset2, CompareOptions options) const
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | İlk dize. |
| offset1 | int | **string1** içindeki karakterlerin başlangıç dizini. |
| string2 | const [String](../../../system/string/)\& | İkinci dize. |
| offset2 | int | **string2** içindeki karakterlerin başlangıç dizini. |
| options | [CompareOptions](../../compareoptions/) | [String](../../../system/string/) karşılaştırma seçenekleri. |

### Dönüş Değeri

LHS dizesi RHS dizesinden önce geliyorsa negatif değer, eşleşiyorlarsa sıfır, aksi takdirde pozitif değer.

## CompareInfo::Compare(const String\&, int, const String\&, int) const metot

Bir dize son bölümünü ikinci dize son bölümüyle karşılaştırır. Henüz uygulanmadı.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, const String &string2, int offset2) const
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | İlk dize. |
| offset1 | int | **string1** içindeki karakterlerin başlangıç dizini. |
| string2 | const [String](../../../system/string/)\& | İkinci dize. |
| offset2 | int | **string2** içindeki karakterlerin başlangıç dizini. |

### Dönüş Değeri

LHS dizesi RHS dizesinden önce geliyorsa negatif değer, eşleşiyorlarsa sıfır, aksi takdirde pozitif değer.

## CompareInfo::Compare(const String\&, int, int, const String\&, int, int, CompareOptions) const metot

Bir dize bölümünü ikinci dize bölümünde dize karşılaştırma yöntemlerini kullanarak karşılaştırır. Henüz uygulanmadı.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, int length1, const String &string2, int offset2, int length2, CompareOptions options) const
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | İlk dize. |
| offset1 | int | **string1** içindeki karakterlerin başlangıç dizini. |
| length1 | int | **string1** içindeki karşılaştırılacak karakter sayısı. |
| string2 | const [String](../../../system/string/)\& | İkinci dize. |
| offset2 | int | **string2** içindeki karakterlerin başlangıç dizini. |
| length2 | int | **string2** içindeki karşılaştırılacak karakter sayısı. |
| options | [CompareOptions](../../compareoptions/) | [String](../../../system/string/) karşılaştırma seçenekleri. |

### Dönüş Değeri

LHS dizesi RHS dizesinden önce geliyorsa negatif değer, eşleşiyorlarsa sıfır, aksi takdirde pozitif değer.

## İlgili

* Enum [CompareOptions](../../compareoptions/)
* Sınıf [String](../../../system/string/)
* Sınıf [CompareInfo](../)
* Ad alanı [System::Globalization](../../)
* Kütüphane [Aspose.Slides](../../../)