---
title: Equals()
second_title: C++ için Aspose.Slides API Referansı
description: Dize eşitlik karşılaştırması. StringComparison sayımında sağlanan birkaç kip desteklenir.
type: docs
weight: 391
url: /tr/system/string/equals/
---
## String::Equals(const String\&, System::StringComparison) const metod

[String](../) eşitlik karşılaştırması. StringComparison sayımında sağlanan birkaç kip desteklenir.

```cpp
bool System::String::Equals(const String &str, System::StringComparison comparison_type) const
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) geçerli olanla karşılaştırmak için. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) kipi (detaylar için [System::StringComparison](../../stringcomparison/) bakın). |

### Dönüş Değeri

Seçilen karşılaştırma tipi kullanılarak dizgiler eşleşirse doğru, aksi takdirde yanlış.

## String::Equals(const String\&) const metod

[String](../) eşitlik karşılaştırması. [System::StringComparison::Ordinal](../../stringcomparison/) karşılaştırma kipini kullanır.

```cpp
bool System::String::Equals(const String &str) const
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) geçerli olanla karşılaştırmak için. |

### Dönüş Değeri

Seçilen karşılaştırma tipi kullanılarak dizgiler eşleşirse doğru, aksi takdirde yanlış.

## String::Equals(const String\&, const String\&) metod

İki dizeyi Ordial karşılaştırma kipini kullanarak eşit karşılaştırır.

```cpp
static bool System::String::Equals(const String &strA, const String &strB)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| strA | const [String](../)\& | Karşılaştırılacak ilk dize. |
| strB | const [String](../)\& | Karşılaştırılacak ikinci dize. |

### Dönüş Değeri

Seçilen karşılaştırma tipi kullanılarak dizgiler eşleşirse doğru, aksi takdirde yanlış.

## String::Equals(const String\&, const String\&, System::StringComparison) metod

İki dizeyi eşit karşılaştırır.

```cpp
static bool System::String::Equals(const String &strA, const String &strB, System::StringComparison comparison_type)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| strA | const [String](../)\& | Karşılaştırılacak ilk dize. |
| strB | const [String](../)\& | Karşılaştırılacak ikinci dize. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) kipi. |

### Dönüş Değeri

Seçilen karşılaştırma tipi kullanılarak dizgiler eşleşirse doğru, aksi takdirde yanlış.

## Ayrıca Bakınız

* Enum [StringComparison](../../stringcomparison/)
* Sınıf [String](../)
* Ad Alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)