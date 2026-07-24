---
title: XmlSchemaValidationFlags
second_title: Aspose.Slides for C++ API Referansı
description: XmlSchemaValidator ve XmlReader sınıfları tarafından kullanılan şema doğrulama seçeneklerini belirtir.
type: docs
weight: 1054
url: /tr/system.xml.schema/xmlschemavalidationflags/
---
## XmlSchemaValidationFlags enum

[XmlSchemaValidator](../xmlschemavalidator/) ve [XmlReader](../../system.xml/xmlreader/) sınıfları tarafından kullanılan şema doğrulama seçeneklerini belirtir.

```cpp
enum class XmlSchemaValidationFlags
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| None | 0 | Kimlik kısıtlamalarını, satır içi şemaları, şema konumu ipuçlarını işlemeyecek ve şema doğrulama uyarılarını raporlamayacaktır. |
| ProcessInlineSchema | 1 | Doğrulama sırasında karşılaşılan satır içi şemaları işler. |
| ProcessSchemaLocation | 2 | Doğrulama sırasında karşılaşılan şema konumu ipuçlarını (**xsi:schemaLocation**, **xsi:noNamespaceSchemaLocation**) işler. |
| ReportValidationWarnings | 4 | Doğrulama sırasında karşılaşılan şema doğrulama uyarılarını raporlar. |
| ProcessIdentityConstraints | 8 | Doğrulama sırasında karşılaşılan kimlik kısıtlamalarını (**xs:ID**, **xs:IDREF**, **xs:key**, **xs:keyref**, **xs:unique**) işler. |
| AllowXmlAttributes | 16 | Şemada tanımlı olmasa bile xml:* özniteliklerine izin verir. Öznitelikler veri türlerine göre doğrulanacaktır. |

## Ayrıca Bakınız

* Ad Alanı [System::Xml::Schema](../)
* Kütüphane [Aspose.Slides](../../)