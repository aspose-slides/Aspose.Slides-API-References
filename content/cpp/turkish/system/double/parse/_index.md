---
title: Parse()
second_title: Aspose.Slides C++ API Referansı
description: Belirtilen sayının dize temsilini içeren dizeyi eşdeğer çift duyarlıklı kayan nokta değerine dönüştürür.
type: docs
weight: 1
url: /tr/system/double/parse/
---
## Double::Parse(const String\&) metot

Belirtilen sayının dize temsilini içeren belirtilen dizeyi eşdeğer çift duyarlıklı kayan nokta değerine dönüştürür.

```cpp
static double System::Double::Parse(const String &value)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek dize. |

### Dönüş Değeri

Belirtilen dize tarafından temsil edilen sayıya eşit çift duyarlıklı kayan nokta değeri.

## Double::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) metot

Sağlanan biçimlendirme bilgilerini kullanarak sayının dize temsilini içeren belirtilen dizeyi eşdeğer çift duyarlıklı kayan nokta değerine dönüştürür.

```cpp
static double System::Double::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek dize. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Dize biçim bilgilerini içeren bir nesneye gösteren işaretçi. |

### Dönüş Değeri

Belirtilen dize tarafından temsil edilen sayıya eşit çift duyarlıklı kayan nokta değeri.

## Double::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metot

```cpp
static double System::Double::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Double::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metot

```cpp
static double System::Double::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Double::Parse(const String\&, std::nullptr_t) metot

```cpp
static double System::Double::Parse(const String &value, std::nullptr_t)
```

## Double::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metot

Sağlanan biçimlendirme bilgileri ve sayı stili kullanılarak sayının dize temsilini içeren belirtilen dizeyi eşdeğer çift duyarlıklı kayan nokta değerine dönüştürür.

```cpp
static double System::Double::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek dize. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Bir sayının dize temsilinin izin verilen stilini belirten NumberStyles enum değerlerinin bit düzeyinde birleştirilmesi. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Dize biçim bilgilerini içeren bir nesneye gösteren işaretçi. |

### Dönüş Değeri

Belirtilen dize tarafından temsil edilen sayıya eşit çift duyarlıklı kayan nokta değeri.

## Double::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metot

```cpp
static double System::Double::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Double::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metot

```cpp
static double System::Double::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Double::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) metot

```cpp
static double System::Double::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## İlgili

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Sınıf [String](../../string/)
* Sınıf [IFormatProvider](../../iformatprovider/)
* Sınıf [CultureInfo](../../../system.globalization/cultureinfo/)
* Sınıf [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Yapı [Double](../)
* Ad alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)