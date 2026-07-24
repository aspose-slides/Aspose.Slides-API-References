---
title: ParseExact()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen formatları, format sağlayıcısını ve stilleri kullanarak dizeyi eşdeğer TimeSpan nesnesine dönüştürür.
type: docs
weight: 547
url: /tr/system/timespan/parseexact/
---
## TimeSpan::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::TimeSpanStyles) method

Belirtilen formatları, format sağlayıcısını ve stilleri kullanarak dizeyi eşdeğer [TimeSpan](../) nesnesine dönüştürür.

```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | const [String](../../string/)\& | Girdi dizesi. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | [Array](../../array/) format dizesi. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Kültüre özgü biçimlendirme bilgilerini sağlayan format sağlayıcı. |
| styles | [Globalization::TimeSpanStyles](../../../system.globalization/timespanstyles/) | Girdi dizesinde bulunabilecek öğeleri tanımlar. |

### Dönüş Değeri

Dizeye karşılık gelen zaman aralığı.

## TimeSpan::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::TimeSpanStyles) method

```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

## TimeSpan::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::TimeSpanStyles) method

```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

## TimeSpan::ParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::TimeSpanStyles) method

```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const ArrayPtr<String> &formats, std::nullptr_t, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

## TimeSpan::ParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::TimeSpanStyles) method

Belirtilen formatı, format sağlayıcısını ve stilleri kullanarak dizeyi eşdeğer [TimeSpan](../) nesnesine dönüştürür.

```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | const [String](../../string/)\& | Girdi dizesi. |
| format | const [String](../../string/)\& | Standart veya özel format dizesi. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Kültüre özgü biçimlendirme bilgilerini sağlayan format sağlayıcı. |
| styles | [Globalization::TimeSpanStyles](../../../system.globalization/timespanstyles/) | Girdi dizesinde bulunabilecek öğeleri tanımlar. |

### Dönüş Değeri

Dizeye karşılık gelen zaman aralığı.

## TimeSpan::ParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::TimeSpanStyles) method

```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

## TimeSpan::ParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::TimeSpanStyles) method

```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

## TimeSpan::ParseExact(const String\&, const String\&, std::nullptr_t, Globalization::TimeSpanStyles) method

```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const String &format, std::nullptr_t, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

## İlgili

* Enum [TimeSpanStyles](../../../system.globalization/timespanstyles/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Sınıf [TimeSpan](../)
* Sınıf [String](../../string/)
* Sınıf [IFormatProvider](../../iformatprovider/)
* Sınıf [CultureInfo](../../../system.globalization/cultureinfo/)
* Sınıf [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* AdAlanı [System](../../)
* Library [Aspose.Slides](../../../)