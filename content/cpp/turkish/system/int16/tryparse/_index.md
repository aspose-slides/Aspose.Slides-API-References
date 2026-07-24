---
title: TryParse()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen sayının dize temsili içeren dizeyi eşdeğer 16 bit işaretli tam sayıya dönüştürür.
type: docs
weight: 14
url: /tr/system/int16/tryparse/
---
## Int16::TryParse(const String\&, int16_t\&) metot


Belirtilen sayının dize temsili içeren dizeyi eşdeğer 16 bit işaretli tam sayıya dönüştürür.

```cpp
static bool System::Int16::TryParse(const String &value, int16_t &result)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek dize. |
| result | **int16_t**\& | Dönüşüm sonucunun konulduğu 16 bit işaretli tam sayı değişkenine referans. |

### Dönüş Değeri

Dönüşüm başarılıysa True, aksi takdirde - false.

## Int16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int16_t\&) metot


Belirtilen sayının dize temsili içeren dizeyi, sağlanan biçimlendirme bilgileri ve sayı stili kullanılarak eşdeğer 16 bit işaretli tam sayıya dönüştürür.

```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int16_t &result)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek dize. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles enum değerlerinin bit düzeyinde birleşimi, sayı temsili dizesinin izin verilen stilini belirtir. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Dize biçim bilgilerini içeren bir nesneye işaretçi. |
| result | **int16_t**\& | Dönüşüm sonucunun konulduğu 16 bit işaretli tam sayı değişkenine referans. |

### Dönüş Değeri

Dönüşüm başarılıysa True, aksi takdirde - false.

## Int16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int16_t\&) metot




```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int16_t &result)
```

## Int16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int16_t\&) metot




```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int16_t &result)
```

## Int16::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, int16_t\&) metot




```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int16_t &result)
```

## Bakınız

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Sınıf [String](../../string/)
* Sınıf [Int16](../)
* Sınıf [IFormatProvider](../../iformatprovider/)
* Sınıf [CultureInfo](../../../system.globalization/cultureinfo/)
* Sınıf [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Ad alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)