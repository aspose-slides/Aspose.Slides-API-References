---
title: Parse()
second_title: Aspose.Slides C++ API Referansı
description: Belirtilen, bir sayının dize temsilini içeren dizeyi eşdeğer 8 bit işaretsiz tam sayıya dönüştürür.
type: docs
weight: 1
url: /tr/system/byte/parse/
---
## Byte::Parse(const String\&) metodu

Belirtilen, bir sayının dize temsilini içeren dizeyi eşdeğer 8 bit işaretsiz tam sayıya dönüştürür.

```cpp
static uint8_t System::Byte::Parse(const String &value)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek dize. |

### Dönüş Değeri

Belirtilen dize tarafından temsil edilen sayıya eşit 8 bit işaretsiz tam sayı.

## Byte::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) metodu

Belirtilen, bir sayının dize temsilini içeren dizeyi sağlanan biçimlendirme bilgilerini kullanarak eşdeğer 8 bit işaretsiz tam sayıya dönüştürür.

```cpp
static uint8_t System::Byte::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek dize. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Dize formatı bilgisini içeren bir nesneye işaretçi. |

### Dönüş Değeri

Belirtilen dize tarafından temsil edilen sayıya eşit 8 bit işaretsiz tam sayı.

## Byte::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metodu




```cpp
static uint8_t System::Byte::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Byte::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metodu




```cpp
static uint8_t System::Byte::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Byte::Parse(const String\&, std::nullptr_t) metodu




```cpp
static uint8_t System::Byte::Parse(const String &value, std::nullptr_t)
```

## Byte::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metodu

Sağlanan biçimlendirme bilgileri ve sayı stili kullanılarak, belirtilen dizeyi eşdeğer 8 bit işaretsiz tam sayıya dönüştürür.

```cpp
static uint8_t System::Byte::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek dize. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles enum değerlerinin bit düzeyinde birleşimi; sayının dize temsili için izin verilen stili belirtir. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Dize formatı bilgisini içeren bir nesneye işaretçi. |

### Dönüş Değeri

Belirtilen dize tarafından temsil edilen sayıya eşit 8 bit işaretsiz tam sayı.

## Byte::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metodu




```cpp
static uint8_t System::Byte::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Byte::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metodu




```cpp
static uint8_t System::Byte::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Byte::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) metodu




```cpp
static uint8_t System::Byte::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Ayrıca Bakınız

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Byte](../)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)