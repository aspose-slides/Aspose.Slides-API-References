---
title: ToString()
second_title: Aspose.Slides için C++ API Referansı
description: Nesne tarafından temsil edilen değerin dize temsili döndürülür.
type: docs
weight: 352
url: /tr/system/decimal/tostring/
---
## Decimal::ToString() const metot


Nesne tarafından temsil edilen değerin dize temsili döndürülür.

```cpp
String System::Decimal::ToString() const
```

## Decimal::ToString(const SharedPtr\<IFormatProvider\>\&) const metot


Geçerli nesneyi, kültüre özgü biçim bilgilerini kullanarak dizeye dönüştürür.

```cpp
String System::Decimal::ToString(const SharedPtr<IFormatProvider> &provider) const
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | [IFormatProvider](../../iformatprovider/) nesnesi, kültüre özgü biçim bilgilerini sağlar. |

### Dönüş Değeri

Geçerli nesnenin dize temsili.

## Decimal::ToString(const SharedPtr\<Globalization::CultureInfo\>\&) const metot




```cpp
String System::Decimal::ToString(const SharedPtr<Globalization::CultureInfo> &culture) const
```

## Decimal::ToString(const SharedPtr\<Globalization::NumberFormatInfo\>\&) const metot




```cpp
String System::Decimal::ToString(const SharedPtr<Globalization::NumberFormatInfo> &nfi) const
```

## Decimal::ToString(const Decimal\&, std::nullptr_t) const metot




```cpp
String System::Decimal::ToString(const Decimal &value, std::nullptr_t) const
```

## Decimal::ToString(const String\&, const SharedPtr\<IFormatProvider\>\&) const metot


Geçerli nesneyi, belirtilen dize biçimini ve belirtilen [IFormatProvider](../../iformatprovider/) nesnesi tarafından sağlanan kültüre özgü biçim bilgilerini kullanarak dize temsiline dönüştürür.

```cpp
String System::Decimal::ToString(const String &format, const SharedPtr<IFormatProvider> &provider) const
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| format | const [String](../../string/)\& | Dize biçimi. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | [IFormatProvider](../../iformatprovider/) nesnesi, kültüre özgü biçim bilgilerini sağlar. |

### Dönüş Değeri

Geçerli nesnenin dize temsili.

## Decimal::ToString(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const metot




```cpp
String System::Decimal::ToString(const String &format, const SharedPtr<Globalization::CultureInfo> &culture) const
```

## Decimal::ToString(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) const metot




```cpp
String System::Decimal::ToString(const String &format, const SharedPtr<Globalization::NumberFormatInfo> &nfi) const
```

## Decimal::ToString(const String\&, std::nullptr_t) const metot




```cpp
String System::Decimal::ToString(const String &format, std::nullptr_t=nullptr) const
```

## İlgili

* Typedef [SharedPtr](../../sharedptr/)
* Sınıf [String](../../string/)
* Sınıf [Decimal](../)
* Sınıf [IFormatProvider](../../iformatprovider/)
* Sınıf [CultureInfo](../../../system.globalization/cultureinfo/)
* Sınıf [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Ad alanı [System](../../)
* Library [Aspose.Slides](../../../)