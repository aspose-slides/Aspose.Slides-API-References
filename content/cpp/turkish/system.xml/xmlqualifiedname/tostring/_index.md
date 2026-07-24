---
title: ToString()
second_title: Aspose.Slides için C++ API Referansı
description: XmlQualifiedName'in dize değerini döndürür.
type: docs
weight: 79
url: /tr/system.xml/xmlqualifiedname/tostring/
---
## XmlQualifiedName::ToString() const metot


Belirtilen [XmlQualifiedName](../)'nin dize değerini döndürür.

```cpp
String System::Xml::XmlQualifiedName::ToString() const override
```


### Dönüş Değeri

[XmlQualifiedName](../)'nin **namespace:localname** biçimindeki dize değeri. Nesnenin bir ad alanı tanımlı değilse, bu metot yalnızca yerel adı döndürür.

## XmlQualifiedName::ToString(const String\&, const String\&) metot


Belirtilen [XmlQualifiedName](../)'nin dize değerini döndürür.

```cpp
static String System::Xml::XmlQualifiedName::ToString(const String &name, const String &ns)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Nesnenin adı. |
| ns | const [String](../../../system/string/)\& | Nesnenin ad alanı. |

### Dönüş Değeri

[XmlQualifiedName](../)'nin **namespace:localname** biçimindeki dize değeri. Nesnenin bir ad alanı tanımlı değilse, bu metot yalnızca yerel adı döndürür.

## Ayrıca Bakınız

* Sınıf [String](../../../system/string/)
* Sınıf [XmlQualifiedName](../)
* AdAlanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)