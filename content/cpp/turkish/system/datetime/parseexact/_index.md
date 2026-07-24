---
title: ParseExact()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen tarih ve saat değerinin dize temsili, belirtilen biçim ve kültüre özgü biçim bilgilerini kullanarak eşdeğer DateTime nesnesine dönüştürür. Dize temsili biçimi, belirtilen biçimle tam olarak eşleşmelidir. Dönüştürme başarısız olursa bir istisna fırlatılır.
type: docs
weight: 872
url: /tr/system/datetime/parseexact/
---
## DateTime::ParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) metod

Belirtilen tarih ve saat değerinin dize temsili, belirtilen biçim ve kültüre özgü biçim bilgilerini kullanarak eşdeğer [DateTime](../) nesnesine dönüştürür. Dize temsili biçimi, belirtilen biçimle tam olarak eşleşmelidir. Dönüştürme başarısız olursa bir istisna fırlatılır.

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| s | const [String](../../string/)\& | Dönüştürülecek tarih ve saat değerinin dize temsili. |
| format | const [String](../../string/)\& | Dize biçimi. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Kültüre özgü biçim bilgilerini sağlayan [IFormatProvider](../../iformatprovider/) nesnesi. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | **s** hakkında ek bilgi, **s** içinde bulunabilecek stil öğeleri hakkında veya **s**'den bir [DateTime](../) nesnesine dönüşüm hakkında sağlayan sayısal değerlerin bit düzeyinde bir kombinasyonu. |

### Dönüş Değeri

Belirtilen dize tarafından temsil edilen tarih ve saat değerine eşdeğer olan [DateTime](../) sınıfının yeni bir örneği.

## DateTime::ParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles) metod

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::ParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles) metod

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::ParseExact(const String\&, const String\&, std::nullptr_t, Globalization::DateTimeStyles) metod

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, std::nullptr_t, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) metod

Belirtilen tarih ve saat değerinin dize temsili, belirtilen biçimler, kültüre özgü biçim bilgileri ve stil kullanılarak eşdeğer [DateTime](../) nesnesine dönüştürür. Dize temsili biçimi, belirtilen biçimlerden bir veya daha fazlasıyla tam olarak eşleşmelidir. Dönüştürme başarısız olursa bir istisna fırlatılır.

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| s | const [String](../../string/)\& | Dönüştürülecek tarih ve saat değerinin dize temsili. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | Dize biçimlerinin dizisi. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Kültüre özgü biçim bilgilerini sağlayan [IFormatProvider](../../iformatprovider/) nesnesi. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | **s** hakkında ek bilgi, **s** içinde bulunabilecek stil öğeleri hakkında veya **s**'den bir [DateTime](../) nesnesine dönüşüm hakkında sağlayan sayısal değerlerin bit düzeyinde bir kombinasyonu. |

### Dönüş Değeri

Belirtilen dize tarafından temsil edilen tarih ve saat değerine eşdeğer olan [DateTime](../) sınıfının yeni bir örneği.

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles) metod

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles)
```

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles) metod

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles)
```

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::DateTimeStyles) metod

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, std::nullptr_t, Globalization::DateTimeStyles styles)
```

## Bakınız

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [DateTime](../)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)