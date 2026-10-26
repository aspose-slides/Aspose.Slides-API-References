---
title: TryParse()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen sayının dize temsili içeren dizeyi eşdeğer 32-bit işaretli tam sayıya dönüştürür.
type: docs
weight: 14
url: /tr/system/int32/tryparse/
---
## Int32::TryParse(const String\&, int32_t\&) method

Belirtilen sayının dize temsili içeren dizeyi eşdeğer 32-bit işaretli tam sayıya dönüştürür.

```cpp
static bool System::Int32::TryParse(const String &value, int32_t &result)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek dize. |
| result | **int32_t**\& | Dönüşüm sonucunun yerleştirileceği 32-bit işaretli tam sayı değişkenine referans. |

### Dönüş Değeri

True if the conversion succeeded, otherwise - false.

## Int32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int32_t\&) method

Belirtilen sayının dize temsili içeren dizeyi, sağlanan biçimlendirme bilgisi ve sayı stili kullanılarak eşdeğer 32-bit işaretli tam sayıya dönüştürür.

```cpp
static bool System::Int32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int32_t &result)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek dize. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Bir sayının dize temsili için izin verilen stilı belirten NumberStyles enum değerlerinin bit düzeyinde kombinasyonu. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Dize biçim bilgilerini içeren bir nesneye işaretçi. |
| result | **int32_t**\& | Dönüşüm sonucunun yerleştirileceği 32-bit işaretli tam sayı değişkenine referans. |

### Dönüş Değeri

True if the conversion succeeded, otherwise - false.

## Int32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int32_t\&) method




```cpp
static bool System::Int32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int32_t &result)
```

## Int32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int32_t\&) method




```cpp
static bool System::Int32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int32_t &result)
```

## Int32::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, int32_t\&) method




```cpp
static bool System::Int32::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int32_t &result)
```

## Bakınız

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Sınıf [String](../../string/)
* Sınıf [Int32](../)
* Sınıf [IFormatProvider](../../iformatprovider/)
* Sınıf [CultureInfo](../../../system.globalization/cultureinfo/)
* Sınıf [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* İsim Alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)