---
title: Parse()
second_title: Aspose.Slides C++ için API Referansı
description: Belirtilen sayının dize temsilini içeren dizeyi eşdeğer 16 bit işaretsiz tam sayıya dönüştürür.
type: docs
weight: 1
url: /tr/system/uint16/parse/
---
## UInt16::Parse(const String\&) yöntemi

Belirtilen sayı temsilini içeren dizeyi eşdeğer 16 bit işaretsiz tam sayıya dönüştürür.

```cpp
static uint16_t System::UInt16::Parse(const String &value)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek dize. |

### Dönüş Değeri

Belirtilen dize tarafından temsil edilen sayıya eşit 16 bit işaretsiz tam sayı.

## UInt16::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) yöntemi

Belirtilen sayı temsilini içeren dizeyi, sağlanan biçimlendirme bilgisi kullanılarak eşdeğer 16 bit işaretsiz tam sayıya dönüştürür.

```cpp
static uint16_t System::UInt16::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek dize. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Dize biçim bilgilerini içeren nesneye bir işaretçi. |

### Dönüş Değeri

Belirtilen dize tarafından temsil edilen sayıya eşit 16 bit işaretsiz tam sayı.

## UInt16::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) yöntemi




```cpp
static uint16_t System::UInt16::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## UInt16::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) yöntemi




```cpp
static uint16_t System::UInt16::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## UInt16::Parse(const String\&, std::nullptr_t) yöntemi




```cpp
static uint16_t System::UInt16::Parse(const String &value, std::nullptr_t)
```

## UInt16::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) yöntemi

Belirtilen sayı temsilini içeren dizeyi, sağlanan biçimlendirme bilgisi ve sayı stili kullanılarak eşdeğer 16 bit işaretsiz tam sayıya dönüştürür.

```cpp
static uint16_t System::UInt16::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek dize. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles enum değerlerinin bit düzeyinde bir birleşimi; sayının dize temsili için izin verilen stili belirtir. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Dize biçim bilgilerini içeren nesneye bir işaretçi. |

### Dönüş Değeri

Belirtilen dize tarafından temsil edilen sayıya eşit 16 bit işaretsiz tam sayı.

## UInt16::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) yöntemi




```cpp
static uint16_t System::UInt16::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## UInt16::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) yöntemi




```cpp
static uint16_t System::UInt16::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## UInt16::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) yöntemi




```cpp
static uint16_t System::UInt16::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Ayrıca Bakınız

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Sınıf [String](../../string/)
* Sınıf [IFormatProvider](../../iformatprovider/)
* Sınıf [CultureInfo](../../../system.globalization/cultureinfo/)
* Sınıf [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Yapı [UInt16](../)
* Ad alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)