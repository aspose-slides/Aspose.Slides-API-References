---
title: Parse()
second_title: Aspose.Slides C++ için API Referansı
description: Belirtilen tarih ve saat değerinin dize gösterimini eşdeğer DateTime nesnesine dönüştürür.
type: docs
weight: 859
url: /tr/system/datetime/parse/
---
## DateTime::Parse(const String\&) metodu


Belirtilen tarih ve saat değerinin dize gösterimini eşdeğer [DateTime](../) nesnesine dönüştürür.

```cpp
static DateTime System::DateTime::Parse(const String &s)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| s | const [String](../../string/)\& | Dönüştürülecek bir tarih ve saat değerinin dize gösterimi. |

### Dönüş Değeri

Belirtilen dize tarafından temsil edilen tarih ve saat değerine eşdeğer [DateTime](../) sınıfının yeni bir örneği.

## DateTime::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) metodu


Kültüre özgü biçim bilgilerini kullanarak belirtilen tarih ve saat değerinin dize gösterimini eşdeğer [DateTime](../) nesnesine dönüştürür.

```cpp
static DateTime System::DateTime::Parse(const String &s, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| s | const [String](../../string/)\& | Dönüştürülecek bir tarih ve saat değerinin dize gösterimi. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Kültüre özgü biçim bilgilerini sağlayan [IFormatProvider](../../iformatprovider/) nesnesi. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | **s** hakkında ek bilgi, **s** içinde bulunabilecek stil öğeleri hakkında ek bilgi veya **s**'nin bir [DateTime](../) nesnesine dönüşümü hakkında ek bilgi sağlayan enum değerlerinin bitwise birleşimi. |

### Dönüş Değeri

Belirtilen dize tarafından temsil edilen tarih ve saat değerine eşdeğer [DateTime](../) sınıfının yeni bir örneği.

## DateTime::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles) metodu



```cpp
static DateTime System::DateTime::Parse(const String &s, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::Parse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles) metodu



```cpp
static DateTime System::DateTime::Parse(const String &s, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::Parse(const String\&, std::nullptr_t, Globalization::DateTimeStyles) metodu



```cpp
static DateTime System::DateTime::Parse(const String &s, std::nullptr_t, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## Diğer

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Sınıf [DateTime](../)
* Sınıf [String](../../string/)
* Sınıf [IFormatProvider](../../iformatprovider/)
* Sınıf [CultureInfo](../../../system.globalization/cultureinfo/)
* Sınıf [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Ad alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)