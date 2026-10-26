---
title: ToString()
second_title: Aspose.Slides for C++ API Referansı
description: Geçerli nesne tarafından temsil edilen GUID'i dize temsiline dönüştürür.
type: docs
weight: 79
url: /tr/system/guid/tostring/
---
## Guid::ToString() const metot

Geçerli nesne tarafından temsil edilen GUID'i dize temsiline dönüştürür.

```cpp
String System::Guid::ToString() const
```

## Guid::ToString(const String\&) const metot

Geçerli nesne tarafından temsil edilen GUID'i belirtilen dize biçimini kullanarak dize temsiline dönüştürür.

```cpp
String System::Guid::ToString(const String &format) const
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| format | const [String](../../string/)\& | Kullanılacak biçim |

### Dönüş Değeri

Geçerli nesne tarafından temsil edilen GUID değerinin dize temsili.

## Guid::ToString(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const metot

Geçerli nesne tarafından temsil edilen GUID'i belirtilen dize biçimini ve Kültürü kullanarak dize temsiline dönüştürür.

```cpp
String System::Guid::ToString(const String &format, const SharedPtr<Globalization::CultureInfo> &culture) const
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| format | const [String](../../string/)\& | Kullanılacak biçim |
| culture | const [SharedPtr](../../sharedptr/)\<[Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Kullanılacak kültür |

### Dönüş Değeri

Geçerli nesne tarafından temsil edilen GUID değerinin dize temsili.

## İlgili

* Typedef [SharedPtr](../../sharedptr/)
* Sınıf [String](../../string/)
* Sınıf [Guid](../)
* Sınıf [CultureInfo](../../../system.globalization/cultureinfo/)
* Ad alanı [System](../../)
* Library [Aspose.Slides](../../../)