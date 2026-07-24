---
title: IndexOf()
second_title: C++ için Aspose.Slides API Referansı
description: Alt dize ileri arama.
type: docs
weight: 625
url: /tr/system/string/indexof/
---
## String::IndexOf(const String\&, System::StringComparison) const metodu

Alt dize ileri arama.

```cpp
int System::String::IndexOf(const String &str, System::StringComparison comparison_type) const
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | const [String](../)\& | Aranacak alt dize. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) modu. |

### Dönüş Değeri

[Index](../../index/) ilk bulunan alt dizenin konumu veya bulunamazsa -1. Boş arama dizesi için her zaman 0 döner.

## String::IndexOf(char_t, int) const metodu

Karakter ileri arama.

```cpp
int System::String::IndexOf(char_t c, int startIndex=0) const
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| c | char_t | Aranacak karakter. |
| startIndex | int | [Index](../../index/) aramanın başlanacağı yer. |

### Dönüş Değeri

[Index](../../index/) startIndex'ten itibaren ilk karakter konumu veya bulunamazsa -1.

## String::IndexOf(char_t, int, int) const metodu

Alt dizede karakter ileri arama.

```cpp
int System::String::IndexOf(char_t c, int startIndex, int count) const
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| c | char_t | Aranacak karakter. |
| startIndex | int | [Index](../../index/) aramanın başlanacağı yer. |
| count | int | İncelenecek karakter sayısı. |

### Dönüş Değeri

[Index](../../index/) startIndex'ten itibaren ilk karakter konumu veya bulunamazsa -1.

## String::IndexOf(const String\&, int) const metodu

Alt dize ileri arama.

```cpp
int System::String::IndexOf(const String &str, int startIndex=0) const
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | const [String](../)\& | Aranacak alt dize. |
| startIndex | int | Kaynak dizede aramaya başlanacak konum. |

### Dönüş Değeri

[Index](../../index/) ilk bulunan alt dizenin konumu veya bulunamazsa -1. Boş arama dizesi için her zaman startIndex döner.

## String::IndexOf(const String\&, int, System::StringComparison) const metodu

Alt dize ileri arama.

```cpp
int System::String::IndexOf(const String &str, int startIndex, System::StringComparison comparison_type) const
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | const [String](../)\& | Aranacak alt dize. |
| startIndex | int | Kaynak dizede aramaya başlanacak konum. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) modu. |

### Dönüş Değeri

[Index](../../index/) ilk bulunan alt dizenin konumu veya bulunamazsa -1. Boş arama dizesi için her zaman startIndex döner.

## String::IndexOf(const String\&, int, int, System::StringComparison) const metodu

Alt dize ileri arama.

```cpp
int System::String::IndexOf(const String &value, int startIndex, int count, System::StringComparison comparisonType) const
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../)\& | Aranacak alt dize. |
| startIndex | int | Kaynak dizede aramaya başlanacak konum. |
| count | int | İncelenecek karakter sayısı. |
| comparisonType | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) modu. |

### Dönüş Değeri

[Index](../../index/) ilk bulunan alt dizenin konumu veya bulunamazsa -1. Boş arama dizesi için her zaman startIndex döner.

## String::IndexOf(const String\&, int, int) const metodu

Alt dize ileri arama.

```cpp
int System::String::IndexOf(const String &str, int startIndex, int count) const
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | const [String](../)\& | Aranacak alt dize. |
| startIndex | int | Kaynak dizede aramaya başlanacak konum. |
| count | int | İncelenecek karakter sayısı. |

### Dönüş Değeri

[Index](../../index/) ilk bulunan alt dizenin konumu veya bulunamazsa -1. Boş arama dizesi için her zaman startIndex döner.

## İlgili

* Enum [StringComparison](../../stringcomparison/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)