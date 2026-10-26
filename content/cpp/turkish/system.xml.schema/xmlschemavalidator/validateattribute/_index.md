---
title: ValidateAttribute()
second_title: Aspose.Slides for C++ API Referansı
description: Geçerli öğe bağlamında öznitelik adını, ad alanı URI'sını ve değerini doğrular.
type: docs
weight: 144
url: /tr/system.xml.schema/xmlschemavalidator/validateattribute/
---
## XmlSchemaValidator::ValidateAttribute(const String\&, const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\&) metot

Geçerli öğe bağlamında öznitelik adını, ad alanı URI'sını ve değerini doğrular.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateAttribute(const String &localName, const String &namespaceUri, const String &attributeValue, const SharedPtr<XmlSchemaInfo> &schemaInfo)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Doğrulanacak öznitelik için yerel ad. |
| namespaceUri | const [String](../../../system/string/)\& | Doğrulanacak özniteliğin ad alanı URI'sı. |
| attributeValue | const [String](../../../system/string/)\& | Doğrulanacak öznitelik değeri. |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | Öznitelik başarılı bir şekilde doğrulandıktan sonra özellikleri ayarlanan bir [XmlSchemaInfo](../../xmlschemainfo/) nesnesi. Bu parametre **nullptr** olabilir. |

### Dönüş Değeri

Doğrulanmış özniteliğin değeri.

## XmlSchemaValidator::ValidateAttribute(const String\&, const String\&, XmlValueGetter, const SharedPtr\<XmlSchemaInfo\>\&) metot

Geçerli öğe bağlamında öznitelik adını, ad alanı URI'sını ve değerini doğrular.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateAttribute(const String &localName, const String &namespaceUri, XmlValueGetter attributeValue, const SharedPtr<XmlSchemaInfo> &schemaInfo)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Doğrulanacak öznitelik için yerel ad. |
| namespaceUri | const [String](../../../system/string/)\& | Doğrulanacak özniteliğin ad alanı URI'sı. |
| attributeValue | [XmlValueGetter](../../xmlvaluegetter/) | Öznitelik değerini, özniteliğin XML [Schema](../../) Tanım Dili (XSD) tipiyle uyumlu bir tür olarak iletmek için kullanılan bir XmlValueGetter geri çağırma. |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | Öznitelik başarılı bir şekilde doğrulandıktan sonra özellikleri ayarlanan bir [XmlSchemaInfo](../../xmlschemainfo/) nesnesi. Bu parametre **nullptr** olabilir. |

### Dönüş Değeri

Doğrulanmış özniteliğin değeri.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [XmlValueGetter](../../xmlvaluegetter/)
* Sınıf [Object](../../../system/object/)
* Sınıf [String](../../../system/string/)
* Sınıf [XmlSchemaInfo](../../xmlschemainfo/)
* Sınıf [XmlSchemaValidator](../)
* İsim Uzayı [System::Xml::Schema](../../)
* Kütüphane [Aspose.Slides](../../../)