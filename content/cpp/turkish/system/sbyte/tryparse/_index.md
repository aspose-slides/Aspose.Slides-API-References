---
title: TryParse()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen sayının dize temsili içeren dizgeyi eşdeğer 8-bit işaretli tam sayıya dönüştürür.
type: docs
weight: 14
url: /tr/system/sbyte/tryparse/
---
## SByte::TryParse(const String\&, int8_t\&) metot


Belirtilen sayının dize temsili içeren dizgeyi eşdeğer 8-bit işaretli tam sayıya dönüştürür.

```cpp
static bool System::SByte::TryParse(const String &value, int8_t &result)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek dizge. |
| result | **int8_t**\& | Dönüşüm sonucunun konulacağı 8-bit işaretli tam sayı değişkenine referans. |

### Dönüş Değeri

True if the conversion succeeded, otherwise - false.

## SByte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int8_t\&) metot


Belirtilen sayının dize temsili içeren dizgeyi, sağlanan biçimlendirme bilgileri ve NumberStyles stili kullanılarak eşdeğer 8-bit işaretli tam sayıya dönüştürür.

```cpp
static bool System::SByte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int8_t &result)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek dizge. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Sayının dize temsili için izin verilen stili belirten NumberStyles enum değerlerinin bitwise birleşimi. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Dize biçimlendirme bilgilerini içeren nesneye işaretçi. |
| result | **int8_t**\& | Dönüşüm sonucunun konulacağı 8-bit işaretli tam sayı değişkenine referans. |

### Dönüş Değeri

True if the conversion succeeded, otherwise - false.

## SByte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int8_t\&) metot




```cpp
static bool System::SByte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int8_t &result)
```

## SByte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int8_t\&) metot




```cpp
static bool System::SByte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int8_t &result)
```

## SByte::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, int8_t\&) metot




```cpp
static bool System::SByte::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int8_t &result)
```

## Ayrıca Bakınız

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [SByte](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)