---
title: TryParse()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen sayının dize temsilini içeren dizeyi eşdeğer 64-bit işaretsiz tamsayıya dönüştürür.
type: docs
weight: 14
url: /tr/system/uint64/tryparse/
---
## UInt64::TryParse(const String\&, uint64_t\&) yöntemi


Belirtilen sayının dize temsilini içeren dizeyi eşdeğer 64 bit işaretsiz tamsayıya dönüştürür.

```cpp
static bool System::UInt64::TryParse(const String &value, uint64_t &result)
```


### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek dize. |
| result | **uint64_t**\& | Dönüşüm sonucunun konulacağı 64 bit işaretsiz tamsayı değişkenine referans. |

### Dönüş Değeri

True if the conversion succeeded, otherwise - false.

## UInt64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, uint64_t\&) yöntemi


Belirtilen sayının dize temsilini içeren dizeyi, sağlanan biçimlendirme bilgileri ve sayı stili kullanarak eşdeğer 64 bit işaretsiz tamsayıya dönüştürür.

```cpp
static bool System::UInt64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, uint64_t &result)
```


### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek dize. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Sayı temsilinin izin verilen stilini belirten NumberStyles enum değerlerinin bit düzeyinde birleşimi. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Dize biçim bilgilerini içeren nesneye bir işaretçi. |
| result | **uint64_t**\& | Dönüşüm sonucunun konulacağı 64 bit işaretsiz tamsayı değişkenine referans. |

### Dönüş Değeri

True if the conversion succeeded, otherwise - false.

## UInt64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, uint64_t\&) yöntemi




```cpp
static bool System::UInt64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, uint64_t &result)
```

## UInt64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, uint64_t\&) yöntemi




```cpp
static bool System::UInt64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, uint64_t &result)
```

## UInt64::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, uint64_t\&) yöntemi




```cpp
static bool System::UInt64::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, uint64_t &result)
```

## İlgili

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Sınıf [String](../../string/)
* Sınıf [IFormatProvider](../../iformatprovider/)
* Sınıf [CultureInfo](../../../system.globalization/cultureinfo/)
* Sınıf [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Yapı [UInt64](../)
* Ad alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)