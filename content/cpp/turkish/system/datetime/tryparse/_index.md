---
title: TryParse()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen tarih ve saat değerinin dize gösterimini eşdeğer DateTime nesnesine dönüştürür.
type: docs
weight: 885
url: /tr/system/datetime/tryparse/
---
## DateTime::TryParse(const String\&, DateTime\&) yöntemi

Belirtilen tarih ve saat değerinin dize gösterimini eşdeğer [DateTime](../) nesnesine dönüştürür.

```cpp
static bool System::DateTime::TryParse(const String &s, DateTime &result)
```

### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../string/)\& | Dönüştürülecek tarih ve saat değerinin dize gösterimi. |
| result | [DateTime](../)\& | Dönüşüm başarılıysa sonucu içeren çıktı argümanı. |

### Dönüş Değeri

True eğer dönüşüm başarılıysa, aksi takdirde - false.

## DateTime::TryParse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTime\&) yöntemi

Belirtilen tarih ve saat değerinin dize gösterimini, belirtilen kültüre özgü biçim bilgisi ve stil kullanarak eşdeğer [DateTime](../) nesnesine dönüştürür.

```cpp
static bool System::DateTime::TryParse(const String &s, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTime &result)
```

### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../string/)\& | Dönüştürülecek tarih ve saat değerinin dize gösterimi. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Kültüre özgü biçim bilgisi sağlayan [IFormatProvider](../../iformatprovider/) nesnesi. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | **s** hakkında, **s** içinde bulunabilecek stil öğeleri hakkında veya **s**'den bir [DateTime](../) nesnesine dönüşüm hakkında ek bilgi sağlayan, enum değerlerinin bit düzeyinde bir kombinasyonu. |
| result | [DateTime](../)\& | Dönüşüm başarılıysa sonucu içeren çıktı argümanı. |

### Dönüş Değeri

True eğer dönüşüm başarılıysa, aksi takdirde - false.

## DateTime::TryParse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles, DateTime\&) yöntemi




```cpp
static bool System::DateTime::TryParse(const String &s, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles, DateTime\&) yöntemi




```cpp
static bool System::DateTime::TryParse(const String &s, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParse(const String\&, std::nullptr_t, Globalization::DateTimeStyles, DateTime\&) yöntemi




```cpp
static bool System::DateTime::TryParse(const String &s, std::nullptr_t, Globalization::DateTimeStyles styles, DateTime &result)
```

## Ayrıca Bakınız

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [DateTime](../)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)