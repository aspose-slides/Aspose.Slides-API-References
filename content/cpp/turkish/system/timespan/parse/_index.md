---
title: Parse()
second_title: Aspose.Slides for C++ API Referansı
description: Dizeyi eşdeğer TimeSpan nesnesine dönüştürür.
type: docs
weight: 534
url: /tr/system/timespan/parse/
---
## TimeSpan::Parse(const String\&) yöntemi

Dizeyi eşdeğer [TimeSpan](../) nesnesine dönüştürür.

```cpp
static TimeSpan System::TimeSpan::Parse(const String &input)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | const [String](../../string/)\& | Girdi string. |

### Dönüş Değeri

Dizeye karşılık gelen zaman aralığı.

## TimeSpan::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) yöntemi

Belirtilen biçim sağlayıcısını kullanarak dizeyi eşdeğer [TimeSpan](../) nesnesine dönüştürür.

```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, const SharedPtr<IFormatProvider> &provider)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | const [String](../../string/)\& | Girdi string. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Kültüre özgü biçimlendirme bilgilerini sağlayan format sağlayıcı. |

### Dönüş Değeri

Dizeye karşılık gelen zaman aralığı.

## TimeSpan::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) yöntemi




```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, const SharedPtr<Globalization::CultureInfo> &culture)
```

## TimeSpan::Parse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) yöntemi




```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi)
```

## TimeSpan::Parse(const String\&, std::nullptr_t) yöntemi




```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, std::nullptr_t)
```

## İlgili

* typedef [SharedPtr](../../sharedptr/)
* Sınıf [TimeSpan](../)
* Sınıf [String](../../string/)
* Sınıf [IFormatProvider](../../iformatprovider/)
* Sınıf [CultureInfo](../../../system.globalization/cultureinfo/)
* Sınıf [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Ad alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)