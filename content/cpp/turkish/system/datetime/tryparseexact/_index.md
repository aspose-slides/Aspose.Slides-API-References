---
title: TryParseExact()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen tarih ve saat değerinin dize temsilini, belirtilen biçim, kültüre özgü biçim bilgileri ve stil kullanarak eşdeğer DateTime nesnesine dönüştürür. Dize temsilinin biçimi belirtilen biçimle tam olarak eşleşmelidir.
type: docs
weight: 898
url: /tr/system/datetime/tryparseexact/
---
## DateTime::TryParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTime\&) metod


Belirtilen tarih ve saat değerinin dize temsilini, belirtilen biçim, kültüre özgü biçim bilgileri ve stil kullanarak eşdeğer [DateTime](../) nesnesine dönüştürür. Dize temsilinin biçimi belirtilen biçimle tam olarak eşleşmelidir.

```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTime &result)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| s | const [String](../../string/)\& | Dönüştürülecek tarih ve saat değerinin dize temsili. |
| format | const [String](../../string/)\& | Dize biçimi. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Kültüre özgü biçim bilgilerini sağlayan [IFormatProvider](../../iformatprovider/) nesnesi. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | **s** hakkında, **s** içinde bulunabilecek stil öğeleri hakkında veya **s**'den bir [DateTime](../) nesnesine dönüşüm hakkında ek bilgi sağlayan enume değerlerinin bit düzeyinde birleşimi. |
| result | [DateTime](../)\& | Dönüşüm başarılı olursa dönüşüm sonucunu içeren çıktı parametresi. |

### Dönüş Değeri

Dönüş başarılıysa true, aksi takdirde false.

## DateTime::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles, DateTime\&) metod




```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles, DateTime\&) metod




```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const String\&, std::nullptr_t, Globalization::DateTimeStyles, DateTime\&) metod




```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, std::nullptr_t, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTime\&) metod


Belirtilen tarih ve saat değerinin dize temsilini, belirtilen biçimler, kültüre özgü biçim bilgileri ve stil kullanarak eşdeğer [DateTime](../) nesnesine dönüştürür. Dize temsilinin biçimi belirtilen biçimlerden bir veya daha fazlasıyla tam olarak eşleşmelidir.

```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTime &result)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| s | const [String](../../string/)\& | Dönüştürülecek tarih ve saat değerinin dize temsili. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | Dize biçimlerinin dizisi. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Kültüre özgü biçim bilgilerini sağlayan [IFormatProvider](../../iformatprovider/) nesnesi. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | **s** hakkında, **s** içinde bulunabilecek stil öğeleri hakkında veya **s**'den bir [DateTime](../) nesnesine dönüşüm hakkında ek bilgi sağlayan enume değerlerinin bit düzeyinde birleşimi. |
| result | [DateTime](../)\& | Dönüşüm başarılı olursa dönüşüm sonucunu içeren çıktı parametresi. |

### Dönüş Değeri

Dönüş başarılıysa true, aksi takdirde false.

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles, DateTime\&) metod




```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles, DateTime\&) metod




```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::DateTimeStyles, DateTime\&) metod




```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, std::nullptr_t, Globalization::DateTimeStyles styles, DateTime &result)
```

## Ayrıca Bakınız

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [DateTime](../)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)