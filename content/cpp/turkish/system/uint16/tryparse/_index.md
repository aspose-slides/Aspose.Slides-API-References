---
title: TryParse()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen sayının dize temsili içeren dizeyi eşdeğer 16-bit işaretsiz tam sayıya dönüştürür.
type: docs
weight: 14
url: /tr/system/uint16/tryparse/
---
## UInt16::TryParse(const String\&, uint16_t\&) metodu


Belirtilen sayının dize temsili içeren dizgeyi eşdeğer 16-bit işaretsiz tam sayıya dönüştürür.

```cpp
static bool System::UInt16::TryParse(const String &value, uint16_t &result)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek dize. |
| result | **uint16_t**\& | Dönüşüm sonucunun yerleştirileceği 16-bit işaretsiz tam sayı değişkenine referans. |

### Dönüş Değeri

True if the conversion succeeded, otherwise - false.

## UInt16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, uint16_t\&) metodu


Belirtilen sayının dize temsili içeren dizgeyi, sağlanan biçimlendirme bilgileri ve NumberStyles stilini kullanarak eşdeğer 16-bit işaretsiz tam sayıya dönüştürür.

```cpp
static bool System::UInt16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, uint16_t &result)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek dize. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles enum değerlerinin bit düzeyinde birleşimi; sayının dize temsili için izin verilen stili belirtir. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Dize biçimlendirme bilgilerini içeren nesneye işaretçi. |
| result | **uint16_t**\& | Dönüşüm sonucunun yerleştirileceği 16-bit işaretsiz tam sayı değişkenine referans. |

### Dönüş Değeri

True if the conversion succeeded, otherwise - false.

## UInt16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, uint16_t\&) metodu




```cpp
static bool System::UInt16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, uint16_t &result)
```

## UInt16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, uint16_t\&) metodu




```cpp
static bool System::UInt16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, uint16_t &result)
```

## UInt16::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, uint16_t\&) metodu




```cpp
static bool System::UInt16::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, uint16_t &result)
```

## Diğer

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [UInt16](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)