---
title: LastIndexOf()
second_title: Aspose.Slides için C++ API Referansı
description: Alt dize geriye doğru arama.
type: docs
weight: 651
url: /tr/system/string/lastindexof/
---
## String::LastIndexOf(const String&, int) const metot


Alt dize geriye doğru arama.

```cpp
int System::String::LastIndexOf(const String &str, int startIndex=INT32_MAX) const
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | const [String](../)& | Aranacak alt dize. |
| startIndex | int | Kaynak dizede aramaya başlanacak konum. |

### Dönüş Değeri

[Index](../../index/) son bulunan alt dizenin indeksi veya bulunamazsa -1. Boş arama dizesi için her zaman dize uzunluğunu döndürür.

## String::LastIndexOf(const String&, System::StringComparison) const metot


Alt dize geriye doğru arama.

```cpp
int System::String::LastIndexOf(const String &str, System::StringComparison comparison_type) const
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | const [String](../)& | Aranacak alt dize. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) modu. |

### Dönüş Değeri

[Index](../../index/) son bulunan alt dizenin indeksi veya bulunamazsa -1. Boş arama dizesi için her zaman dize uzunluğunu döndürür.

## String::LastIndexOf(const String&, int, System::StringComparison) const metot


Alt dize geriye doğru arama.

```cpp
int System::String::LastIndexOf(const String &str, int startIndex, System::StringComparison comparison_type) const
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | const [String](../)& | Aranacak alt dize. |
| startIndex | int | Kaynak dizede aramaya başlanacak konum. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) modu. |

### Dönüş Değeri

[Index](../../index/) son bulunan alt dizenin indeksi veya bulunamazsa -1. Boş arama dizesi için her zaman dize uzunluğunu döndürür.

## String::LastIndexOf(const String&, int, int, StringComparison) const metot


Alt dize geriye doğru arama.

```cpp
int System::String::LastIndexOf(const String &value, int startIndex, int count, StringComparison comparisonType) const
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../)& | Aranacak alt dize. |
| startIndex | int | Kaynak dizede aramaya başlanacak konum. |
| count | int | Aranacak karakter sayısı. |
| comparisonType | [StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) modu. |

### Dönüş Değeri

[Index](../../index/) son bulunan alt dizenin indeksi veya bulunamazsa -1. Boş arama dizesi için her zaman startIndex+count değerini döndürür.

## String::LastIndexOf(char_t) const metot


Karakter geriye doğru arama.

```cpp
int System::String::LastIndexOf(char_t value) const
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | char_t | Aranacak karakter. |

### Dönüş Değeri

[Index](../../index/) son karakterin konumu veya bulunamazsa -1.

## String::LastIndexOf(char_t, int32_t) const metot


Karakter geriye doğru arama.

```cpp
int System::String::LastIndexOf(char_t value, int32_t startIndex) const
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | char_t | Aranacak karakter. |
| startIndex | **int32_t** | [Index](../../index/) aramaya başlanacak yer. |

### Dönüş Değeri

[Index](../../index/) startIndex'ten itibaren son karakterin konumu veya bulunamazsa -1.

## String::LastIndexOf(char_t, int32_t, int32_t) const metot


Karakter geriye doğru arama.

```cpp
int System::String::LastIndexOf(char_t value, int32_t startIndex, int32_t count) const
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | char_t | Aranacak karakter. |
| startIndex | **int32_t** | [Index](../../index/) aramaya başlanacak yer. |
| count | **int32_t** | Aranacak karakter sayısı. |

### Dönüş Değeri

[Index](../../index/) startIndex'ten itibaren son karakterin konumu veya bulunamazsa -1.

## Ayrıca Bakınız

* Enum [StringComparison](../../stringcomparison/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)