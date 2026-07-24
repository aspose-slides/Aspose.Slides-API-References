---
title: Parse()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen sayının dize temsilini içeren dizeyi eşdeğer 8 bit işaretli tam sayıya dönüştürür.
type: docs
weight: 1
url: /tr/system/sbyte/parse/
---
## SByte::Parse(const String\&) metot


Belirtilen sayının dize temsilini içeren belirtilen dizeyi eşdeğer 8 bit işaretli tam sayıya dönüştürür.

```cpp
static int8_t System::SByte::Parse(const String &value)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek dize. |

### Dönüş Değeri

Belirtilen dize tarafından temsil edilen sayıya eşit 8 bit işaretli tam sayı.


## SByte::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) metot


Belirtilen sayının dize temsilini içeren belirtilen dizeyi sağlanan biçimlendirme bilgilerini kullanarak eşdeğer 8 bit işaretli tam sayıya dönüştürür.

```cpp
static int8_t System::SByte::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek dize. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Dize biçim bilgilerini içeren bir nesneye işaretçi. |

### Dönüş Değeri

Belirtilen dize tarafından temsil edilen sayıya eşit 8 bit işaretli tam sayı.

## SByte::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metot




```cpp
static int8_t System::SByte::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## SByte::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metot




```cpp
static int8_t System::SByte::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## SByte::Parse(const String\&, std::nullptr_t) metot




```cpp
static int8_t System::SByte::Parse(const String &value, std::nullptr_t)
```

## SByte::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metot


Belirtilen sayının dize temsilini içeren belirtilen dizeyi sağlanan biçimlendirme bilgileri ve sayı biçemi kullanarak eşdeğer 8 bit işaretli tam sayıya dönüştürür.

```cpp
static int8_t System::SByte::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek dize. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Bir sayının dize temsilinin izin verilen biçimini belirten NumberStyles enum değerlerinin bit düzeyinde birleşimi. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Dize biçim bilgilerini içeren bir nesneye işaretçi. |

### Dönüş Değeri

Belirtilen dize tarafından temsil edilen sayıya eşit 8 bit işaretli tam sayı.

## SByte::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metot




```cpp
static int8_t System::SByte::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## SByte::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metot




```cpp
static int8_t System::SByte::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## SByte::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) metot




```cpp
static int8_t System::SByte::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## İlgili

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [SByte](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)