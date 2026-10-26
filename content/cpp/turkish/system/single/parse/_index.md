---
title: Parse()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen, bir sayının dize gösterimini içeren dizeyi eşdeğer tek duyarlıklı kayan nokta değerine dönüştürür.
type: docs
weight: 1
url: /tr/system/single/parse/
---
## Single::Parse(const String\&) yöntemi


Belirtilen, bir sayının dize gösterimini içeren dizeyi eşdeğer tek duyarlıklı kayan nokta değerine dönüştürür.

```cpp
static float System::Single::Parse(const String &value)
```


### Parametreler

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek dize. |

### Dönüş Değeri

Belirtilen dize tarafından temsil edilen sayıya eşit tek duyarlıklı kayan nokta değeri.

## Single::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) yöntemi


Belirtilen, bir sayının dize gösterimini içeren dizeyi, sağlanan biçimlendirme bilgilerini kullanarak eşdeğer tek duyarlıklı kayan nokta değerine dönüştürür.

```cpp
static float System::Single::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Parametreler

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek dize. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Dize biçim bilgilerini içeren bir nesneye işaretçi. |

### Dönüş Değeri

Belirtilen dize tarafından temsil edilen sayıya eşit tek duyarlıklı kayan nokta değeri.

## Single::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) yöntemi




```cpp
static float System::Single::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Single::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) yöntemi




```cpp
static float System::Single::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Single::Parse(const String\&, std::nullptr_t) yöntemi




```cpp
static float System::Single::Parse(const String &value, std::nullptr_t)
```

## Single::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) yöntemi


Belirtilen, bir sayının dize gösterimini içeren dizeyi, sağlanan biçimlendirme bilgilerini ve sayı stilini kullanarak eşdeğer tek duyarlıklı kayan nokta değerine dönüştürür.

```cpp
static float System::Single::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Parametreler

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek dize. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Bir sayının dize gösteriminin izin verilen stilini belirten NumberStyles enum değerlerinin bit düzeyinde bir kombinasyonu. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Dize biçim bilgilerini içeren bir nesneye işaretçi. |

### Dönüş Değeri

Belirtilen dize tarafından temsil edilen sayıya eşit tek duyarlıklı kayan nokta değeri.

## Single::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) yöntemi




```cpp
static float System::Single::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Single::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) yöntemi




```cpp
static float System::Single::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Single::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) yöntemi




```cpp
static float System::Single::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Ayrıca Bakınız

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Sınıf [String](../../string/)
* Sınıf [IFormatProvider](../../iformatprovider/)
* Sınıf [CultureInfo](../../../system.globalization/cultureinfo/)
* Sınıf [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Yapı [Single](../)
* Ad Alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)