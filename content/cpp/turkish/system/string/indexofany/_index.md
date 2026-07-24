---
title: IndexOfAny()
second_title: Aspose.Slides for C++ API Referansı
description: Karakter ileri arama.
type: docs
weight: 638
url: /tr/system/string/indexofany/
---
## String::IndexOfAny(char_t, int) const metod

Karakter ileri arama.

```cpp
int System::String::IndexOfAny(char_t c, int startIndex=0) const
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| c | char_t | Aranacak karakter. |
| startIndex | int | [Index](../../index/) aramaya başlanacak indeks. |

### Dönüş Değeri

[Index](../../index/) ilk karakter pozisyonu startIndex'ten itibaren veya bulunamazsa -1.

## String::IndexOfAny(const String\&, int) const metod

Dolayısıyla bu nesnedeki str'in tüm karakterlerini arar. İlk karakter bulunursa konumu döndürülür, aksi takdirde ikinci karakter ve devamı aranır.

```cpp
int System::String::IndexOfAny(const String &str, int startIndex=0) const
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) aranan karakterler. Karakterlerin sırası önemlidir. |
| startIndex | int | Aramaya başlanacak konum. |

### Dönüş Değeri

[Index](../../index/) bulunan ilk karakterin konumu veya hiç bulunamazsa -1.

## String::IndexOfAny(const ArrayPtr\<char_t\>\&) const metod

Geçilen karakterlerden herhangi birini tüm dizede arar. İlk dize karakterini anyOf içindeki tüm karakterlerle karşılaştırır, ardından ikinciyi vb. Hedef karakterlerden herhangi birine ilk eşleşen karakterin indeksini döndürür.

```cpp
int System::String::IndexOfAny(const ArrayPtr<char_t> &anyOf) const
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) aranan karakterler. Sıra önemsizdir. |

### Dönüş Değeri

[Index](../../index/) ilk eşleşen karakterin indeksi veya bulunamazsa -1.

## String::IndexOfAny(const ArrayPtr\<char_t\>\&, int32_t) const metod

Geçilen karakterlerden herhangi birini alt dizede arar. İlk dize karakterini anyOf içindeki tüm karakterlerle karşılaştırır, ardından ikinciyi vb. Hedef karakterlerden herhangi birine ilk eşleşen karakterin indeksini döndürür.

```cpp
int System::String::IndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex) const
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) aranan karakterler. Sıra önemsizdir. |
| startindex | **int32_t** | [Index](../../index/) aramaya başlanacak indeks. |

### Dönüş Değeri

[Index](../../index/) ilk eşleşen karakterin indeksi veya bulunamazsa -1.

## String::IndexOfAny(const ArrayPtr\<char_t\>\&, int32_t, int32_t) const metod

Geçilen karakterlerden herhangi birini alt dizede arar. İlk dize karakterini anyOf içindeki tüm karakterlerle karşılaştırır, ardından ikinciyi vb. Hedef karakterlerden herhangi birine ilk eşleşen karakterin indeksini döndürür.

```cpp
int System::String::IndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex, int32_t count) const
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) aranan karakterler. Sıra önemsizdir. |
| startindex | **int32_t** | [Index](../../index/) aramaya başlanacak indeks. |
| count | **int32_t** | Aranacak karakter sayısı. |

### Dönüş Değeri

[Index](../../index/) ilk eşleşen karakterin indeksi veya bulunamazsa -1.

## İlgili

* Typedef [ArrayPtr](../../arrayptr/)
* Sınıf [String](../)
* Ad alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)