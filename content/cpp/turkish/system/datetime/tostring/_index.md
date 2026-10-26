---
title: ToString()
second_title: Aspose.Slides C++ API Referansı
description: Geçerli nesnenin temsil ettiği tarih ve saat değerinin, geçerli kültür tarafından tanımlanan biçimlendirme kuralları kullanılarak dizge temsiliğini döndürür.
type: docs
weight: 482
url: /tr/system/datetime/tostring/
---
## DateTime::ToString() const metot


Geçerli nesnenin temsil ettiği tarih ve saat değerinin, geçerli kültür tarafından tanımlanan biçimlendirme kuralları kullanılarak dizge temsiliğini döndürür.

```cpp
String System::DateTime::ToString() const
```


### Dönüş Değeri

Geçerli nesne tarafından temsil edilen değerin dizge temsili.

## DateTime::ToString(const String\&) const metot


Geçerli nesnenin temsil ettiği tarih ve saat değerinin, belirtilen biçim ve geçerli kültür tarafından tanımlanan biçimlendirme kuralları kullanılarak dizge temsiliğini döndürür.

```cpp
String System::DateTime::ToString(const String &format) const
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| format | const [String](../../string/)\& | Biçim dizesi |

### Dönüş Değeri

Geçerli nesne tarafından temsil edilen değerin, **format** tarafından tanımlanan biçime ve geçerli kültüre göre biçimlendirilmiş dizge temsili.

## DateTime::ToString(const SharedPtr\<IFormatProvider\>\&) const metot


Geçerli nesnenin temsil ettiği tarih ve saat değerinin, belirtilen biçim bilgilerini kullanarak dizge temsiliğini döndürür.

```cpp
String System::DateTime::ToString(const SharedPtr<IFormatProvider> &provider) const
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Biçim bilgilerini temsil eden bir nesne |

### Dönüş Değeri

Geçerli nesne tarafından temsil edilen değerin, **formatProvider** tarafından sağlanan biçim bilgilerine göre biçimlendirilmiş dizge temsili.

## DateTime::ToString(const SharedPtr\<Globalization::CultureInfo\>\&) const metot




```cpp
String System::DateTime::ToString(const SharedPtr<Globalization::CultureInfo> &culture) const
```

## DateTime::ToString(const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) const metot




```cpp
String System::DateTime::ToString(const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi) const
```

## DateTime::ToString(std::nullptr_t) const metot




```cpp
String System::DateTime::ToString(std::nullptr_t) const
```

## DateTime::ToString(const String\&, const SharedPtr\<IFormatProvider\>\&) const metot


Geçerli nesnenin temsil ettiği tarih ve saat değerinin, belirtilen biçim bilgilerini kullanarak dizge temsiliğini döndürür.

```cpp
String System::DateTime::ToString(const String &format, const SharedPtr<IFormatProvider> &provider) const
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| format | const [String](../../string/)\& | Biçim dizesi |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Biçim bilgilerini temsil eden bir nesne |

### Dönüş Değeri

Geçerli nesne tarafından temsil edilen değerin, **provider** tarafından sağlanan biçim bilgileri ve **format** biçim dizesi kullanılarak biçimlendirilmiş dizge temsili.

## DateTime::ToString(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const metot




```cpp
String System::DateTime::ToString(const String &format, const SharedPtr<Globalization::CultureInfo> &culture) const
```

## DateTime::ToString(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) const metot




```cpp
String System::DateTime::ToString(const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi) const
```

## DateTime::ToString(const String\&, std::nullptr_t) const metot




```cpp
String System::DateTime::ToString(const String &format, std::nullptr_t) const
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../sharedptr/)
* Sınıf [String](../../string/)
* Sınıf [DateTime](../)
* Sınıf [IFormatProvider](../../iformatprovider/)
* Sınıf [CultureInfo](../../../system.globalization/cultureinfo/)
* Sınıf [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* İsim Uzayı [System](../../)
* Kütüphane [Aspose.Slides](../../../)