---
title: Compare()
second_title: Aspose.Slides için C++ API Referansı
description: Less-equal-greater iki alt dizeyi karşılaştırır.
type: docs
weight: 820
url: /tr/system/string/compare/
---
## String::Compare(const String&, int, const String&, int, int, bool) metodu

Less-equal-greater iki alt dizeyi karşılaştırır.

```cpp
static int System::String::Compare(const String &strA, int indexA, const String &strB, int indexB, int length, bool ignoreCase=false)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| strA | const [String](../)\& | Karşılaştırılacak ilk dize. |
| indexA | int | İlk dize alt dizisinin başlangıcı. |
| strB | const [String](../)\& | Karşılaştırılacak ikinci dize. |
| indexB | int | İkinci dize alt dizisinin başlangıcı. |
| length | int | Karşılaştırılacak karakter sayısı. |
| ignoreCase | **bool** | Karşılaştırmanın büyük/küçük harf duyarsız olup olmadığını belirler. |

### Dönüş Değeri

İlk alt dize ikinci alt dizeden daha az ise negatif değer, eşleşiyorlarsa sıfır, aksi takdirde pozitif değer.

## String::Compare(const String&, int, const String&, int, int, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) metodu

Less-equal-greater iki alt dizeyi karşılaştırır.

```cpp
static int System::String::Compare(const String &strA, int indexA, const String &strB, int indexB, int length, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &ci)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| strA | const [String](../)\& | Karşılaştırılacak ilk dize. |
| indexA | int | İlk dize alt dizisinin başlangıcı. |
| strB | const [String](../)\& | Karşılaştırılacak ikinci dize. |
| indexB | int | İkinci dize alt dizisinin başlangıcı. |
| length | int | Karşılaştırılacak karakter sayısı. |
| ignoreCase | **bool** | Karşılaştırmanın büyük/küçük harf duyarsız olup olmadığını belirler. |
| ci | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Karşılaştırma için kullanılacak kültür. |

### Dönüş Değeri

İlk alt dize ikinci alt dizeden daha az ise negatif değer, eşleşiyorlarsa sıfır, aksi takdirde pozitif değer.

## String::Compare(const String&, const String&, System::StringComparison) metodu

Less-equal-greater iki dizeyi karşılaştırır.

```cpp
static int System::String::Compare(const String &strA, const String &strB, System::StringComparison comparison_type)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| strA | const [String](../)\& | Karşılaştırılacak ilk dize. |
| strB | const [String](../)\& | Karşılaştırılacak ikinci dize. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) modu. |

### Dönüş Değeri

İlk alt dize ikinci alt dizeden daha az ise negatif değer, eşleşiyorlarsa sıfır, aksi takdirde pozitif değer.

## String::Compare(const String&, int, const String&, int, int, System::StringComparison) metodu

Less-equal-greater iki dizeyi karşılaştırır.

```cpp
static int System::String::Compare(const String &strA, int indexA, const String &strB, int indexB, int length, System::StringComparison comparison_type)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| strA | const [String](../)\& | Karşılaştırılacak ilk dize. |
| indexA | int | İlk dize alt dizisinin başlangıcı. |
| strB | const [String](../)\& | Karşılaştırılacak ikinci dize. |
| indexB | int | İkinci dize alt dizisinin başlangıcı. |
| length | int | Karşılaştırılacak karakter sayısı. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) modu. |

### Dönüş Değeri

İlk alt dize ikinci alt dizeden daha az ise negatif değer, eşleşiyorlarsa sıfır, aksi takdirde pozitif değer.

## String::Compare(const String&, const String&, bool) metodu

Less-equal-greater iki dizeyi karşılaştırır.

```cpp
static int System::String::Compare(const String &strA, const String &strB, bool ignoreCase=false)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| strA | const [String](../)\& | Karşılaştırılacak ilk dize. |
| strB | const [String](../)\& | Karşılaştırılacak ikinci dize. |
| ignoreCase | **bool** | Karşılaştırmanın büyük/küçük harf duyarsız olup olmadığını belirler. |

### Dönüş Değeri

İlk alt dize ikinci alt dizeden daha az ise negatif değer, eşleşiyorlarsa sıfır, aksi takdirde pozitif değer.

## String::Compare(const String&, const String&, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) metodu

Less-equal-greater iki dizeyi karşılaştırır.

```cpp
static int System::String::Compare(const String &strA, const String &strB, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &ci)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| strA | const [String](../)\& | Karşılaştırılacak ilk dize. |
| strB | const [String](../)\& | Karşılaştırılacak ikinci dize. |
| ignoreCase | **bool** | Karşılaştırmanın büyük/küçük harf duyarsız olup olmadığını belirler. |
| ci | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Karşılaştırma için kullanılacak kültür. |

### Dönüş Değeri

İlk alt dize ikinci alt dizeden daha az ise negatif değer, eşleşiyorlarsa sıfır, aksi takdirde pozitif değer.

## İlgili

* Enum [StringComparison](../../stringcomparison/)
* Typedef [SharedPtr](../../sharedptr/)
* Sınıf [String](../)
* Sınıf [CultureInfo](../../../system.globalization/cultureinfo/)
* Ad Uzayı [System](../../)
* Library [Aspose.Slides](../../../)