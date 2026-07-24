---
title: XmlSchemaValidator()
second_title: Aspose.Slides for C++ API Referansı
description: XmlSchemaValidator sınıfının yeni bir örneğini başlatır.
type: docs
weight: 92
url: /tr/system.xml.schema/xmlschemavalidator/xmlschemavalidator/
---
## XmlSchemaValidator::XmlSchemaValidator(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlSchemaSet\>\&, const SharedPtr\<IXmlNamespaceResolver\>\&, XmlSchemaValidationFlags) constructor

Yeni bir [XmlSchemaValidator](../) sınıfının örneğini başlatır.

```cpp
System::Xml::Schema::XmlSchemaValidator::XmlSchemaValidator(const SharedPtr<XmlNameTable> &nameTable, const SharedPtr<XmlSchemaSet> &schemas, const SharedPtr<IXmlNamespaceResolver> &namespaceResolver, XmlSchemaValidationFlags validationFlags)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| nameTable | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../../system.xml/xmlnametable/)\>\& | Element ve öznitelik adlarını atomize edilmiş dizgeler olarak içeren bir [XmlNameTable](../../../system.xml/xmlnametable/) nesnesi. |
| schemas | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaSet](../../xmlschemaset/)\>\& | Doğrulama için kullanılan XML [Schema](../../) Tanım Dili (XSD) şemalarını içeren bir [XmlSchemaSet](../../xmlschemaset/) nesnesi. |
| namespaceResolver | const [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\>\& | Doğrulama sırasında karşılaşılan ad alanlarını çözmek için kullanılan bir [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) nesnesi. |
| validationFlags | [XmlSchemaValidationFlags](../../xmlschemavalidationflags/) | Şema doğrulama seçeneklerini belirten bir XmlSchemaValidationFlags değeri. |

## Ayrıca Bakınız

* Enum [XmlSchemaValidationFlags](../../xmlschemavalidationflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [XmlNameTable](../../../system.xml/xmlnametable/)
* Sınıf [XmlSchemaSet](../../xmlschemaset/)
* Sınıf [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Sınıf [XmlSchemaValidator](../)
* Ad Alanı [System::Xml::Schema](../../)
* Kütüphane [Aspose.Slides](../../../)