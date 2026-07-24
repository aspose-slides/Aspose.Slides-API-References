---
title: TryParse()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen sayının dize temsili içeren dizeyi eşdeğer 8 bit işaretsiz tam sayıya dönüştürür.
type: docs
weight: 14
url: /tr/system/byte/tryparse/
---
## Byte::TryParse(const String\&, uint8_t\&) method

Belirtilen sayının dize temsili içeren dizeyi eşdeğer 8 bit işaretsiz tam sayıya dönüştürür.

```cpp
static bool System::Byte::TryParse(const String &value, uint8_t &result)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek dize. |
| result | **uint8_t**\& | Dönüşüm sonucunun konulacağı 8 bit işaretsiz tam sayı değişkenine referans. |

### Dönüş Değeri

Dönüşüm başarılıysa true, aksi takdirde - false.

## Byte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, uint8_t\&) method

Sağlanan biçimlendirme bilgileri ve sayı stili kullanılarak, belirtilen sayının dize temsili içeren dizeyi eşdeğer 8 bit işaretsiz tam sayıya dönüştürür.

```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, uint8_t &result)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek dize. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Sayının dize temsili için izin verilen stili belirten NumberStyles enum değerlerinin bit düzeyinde birleştirilmesi. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Dize formatı bilgisini içeren nesneye gösteren bir işaretçi. |
| result | **uint8_t**\& | Dönüşüm sonucunun konulacağı 8 bit işaretsiz tam sayı değişkenine referans. |

### Dönüş Değeri

Dönüşüm başarılıysa true, aksi takdirde - false.

## Byte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, uint8_t\&) method

```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, uint8_t &result)
```

## Byte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, uint8_t\&) method

```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, uint8_t &result)
```

## Byte::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, uint8_t\&) method

```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, uint8_t &result)
```

## İlgili

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Byte](../)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)