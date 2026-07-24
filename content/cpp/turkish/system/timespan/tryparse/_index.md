---
title: TryParse()
second_title: Aspose.Slides for C++ API Referansı
description: Dizeyi eşdeğer TimeSpan nesnesine dönüştürür ve dönüşüm sonucunu döndürür.
type: docs
weight: 560
url: /tr/system/timespan/tryparse/
---
## TimeSpan::TryParse(const String&, TimeSpan&) metodu


Dizeyi eşdeğer [TimeSpan](../) nesnesine dönüştürür ve dönüşüm sonucunu döndürür.

```cpp
static bool System::TimeSpan::TryParse(const String &input, TimeSpan &result)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | const [String](../../string/)& | Girdi dizesi. |
| result | [TimeSpan](../)& | Dizeye karşılık gelen zaman aralığı. |

### Dönüş Değeri

True if string was converted successfully; otherwise, false.

## TimeSpan::TryParse(const String&, const SharedPtr\<IFormatProvider\>\&, TimeSpan&) metodu


Belirtilen biçim sağlayıcısını kullanarak dizeyi eşdeğer [TimeSpan](../) nesnesine dönüştürür ve dönüşüm sonucunu döndürür.

```cpp
static bool System::TimeSpan::TryParse(const String &input, const SharedPtr<IFormatProvider> &provider, TimeSpan &result)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | const [String](../../string/)& | Girdi dizesi. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)>\& | Kültüre özgü biçimlendirme bilgilerini sağlayan biçim sağlayıcı. |
| result | [TimeSpan](../)& | Dizeye karşılık gelen zaman aralığı. |

### Dönüş Değeri

True if string was converted successfully; otherwise, false.

## TimeSpan::TryParse(const String&, const SharedPtr\<Globalization::CultureInfo\>\&, TimeSpan&) metodu




```cpp
static bool System::TimeSpan::TryParse(const String &input, const SharedPtr<Globalization::CultureInfo> &culture, TimeSpan &result)
```

## TimeSpan::TryParse(const String&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, TimeSpan&) metodu




```cpp
static bool System::TimeSpan::TryParse(const String &input, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, TimeSpan &result)
```

## TimeSpan::TryParse(const String&, std::nullptr_t, TimeSpan&) metodu




```cpp
static bool System::TimeSpan::TryParse(const String &input, std::nullptr_t, TimeSpan &result)
```

## İlgili

* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [TimeSpan](../)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)