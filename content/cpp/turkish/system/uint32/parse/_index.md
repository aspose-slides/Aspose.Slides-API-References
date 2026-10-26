---
title: Parse()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen, sayının dizge temsilini içeren dizeyi eşdeğer 32-bit işaretsiz tam sayıya dönüştürür.
type: docs
weight: 1
url: /tr/system/uint32/parse/
---
## UInt32::Parse(const String\&) metodu


Belirtilen, sayının dizge temsilini içeren dizeyi eşdeğer 32 bit işaretsiz tam sayıya dönüştürür.

```cpp
static uint32_t System::UInt32::Parse(const String &value)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek dize. |

### Dönüş Değeri

The 32-bit unsigned integer equal to the number represented by the specified string.

## UInt32::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) metodu


Belirtilen, sayının dizge temsilini içeren dizeyi sağlanan biçimlendirme bilgilerini kullanarak eşdeğer 32 bit işaretsiz tam sayıya dönüştürür.

```cpp
static uint32_t System::UInt32::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek dize. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Dize biçimlendirme bilgilerini içeren bir nesneye işaretçi. |

### Dönüş Değeri

The 32-bit unsigned integer equal to the number represented by the specified string.

## UInt32::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metodu




```cpp
static uint32_t System::UInt32::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## UInt32::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metodu




```cpp
static uint32_t System::UInt32::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## UInt32::Parse(const String\&, std::nullptr_t) metodu




```cpp
static uint32_t System::UInt32::Parse(const String &value, std::nullptr_t)
```

## UInt32::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metodu


Belirtilen, sayının dizge temsilini içeren dizeyi sağlanan biçimlendirme bilgileri ve sayı stili kullanarak eşdeğer 32 bit işaretsiz tam sayıya dönüştürür.

```cpp
static uint32_t System::UInt32::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek dize. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles enum değerlerinin bir bit düzeyi kombinasyonu; sayının dizge temsilinin izin verilen stilini belirtir. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Dize biçimlendirme bilgilerini içeren bir nesneye işaretçi. |

### Dönüş Değeri

The 32-bit unsigned integer equal to the number represented by the specified string.

## UInt32::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metodu




```cpp
static uint32_t System::UInt32::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## UInt32::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metodu




```cpp
static uint32_t System::UInt32::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## UInt32::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) metodu




```cpp
static uint32_t System::UInt32::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## İlgili

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [UInt32](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)