---
title: TryParse()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen sayının dize temsili içeren dizeyi eşdeğer 32-bit işaretsiz tamsayıya dönüştürür.
type: docs
weight: 14
url: /tr/system/uint32/tryparse/
---
## UInt32::TryParse(const String\&, uint32_t\&) metot


Belirtilen sayının dize temsili içeren dizeyi eşdeğer 32-bit işaretsiz tamsayıya dönüştürür.

```cpp
static bool System::UInt32::TryParse(const String &value, uint32_t &result)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek dize. |
| result | **uint32_t**\& | Dönüştürmenin sonucu konulacak 32-bit işaretsiz tamsayı değişkenine referans. |

### Dönüş Değeri

True if the conversion succeeded, otherwise - false.

## UInt32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, uint32_t\&) metot


Belirtilen sayının dize temsili içeren dizeyi, sağlanan biçimlendirme bilgileri ve sayı stili kullanarak eşdeğer 32-bit işaretsiz tamsayıya dönüştürür.

```cpp
static bool System::UInt32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, uint32_t &result)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek dize. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Sayının dize temsili için izin verilen stili belirten NumberStyles enum değerlerinin bit düzeyi kombinasyonu. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Dize biçim bilgilerini içeren nesneye işaretçi. |
| result | **uint32_t**\& | Dönüştürmenin sonucu konulacak 32-bit işaretsiz tamsayı değişkenine referans. |

### Dönüş Değeri

True if the conversion succeeded, otherwise - false.

## UInt32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, uint32_t\&) metot




```cpp
static bool System::UInt32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, uint32_t &result)
```

## UInt32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, uint32_t\&) metot




```cpp
static bool System::UInt32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, uint32_t &result)
```

## UInt32::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, uint32_t\&) metot




```cpp
static bool System::UInt32::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, uint32_t &result)
```

## See Also

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Sınıf [String](../../string/)
* Sınıf [IFormatProvider](../../iformatprovider/)
* Sınıf [CultureInfo](../../../system.globalization/cultureinfo/)
* Sınıf [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Yapı [UInt32](../)
* Ad Alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)