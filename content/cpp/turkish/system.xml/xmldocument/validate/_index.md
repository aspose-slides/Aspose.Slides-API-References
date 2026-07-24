---
title: Validate()
second_title: Aspose.Slides for C++ API Referansı
description: "XmlDocument nesnesini XmlDocument::get_Schemas listesinde bulunan XML Şema Tanım Dili (XSD) şemalarına karşı doğrular."
type: docs
weight: 573
url: /tr/system.xml/xmldocument/validate/
---
## XmlDocument::Validate(Schema::ValidationEventHandler) metodu

[XmlDocument](../) nesnesini [XmlDocument::get_Schemas](../get_schemas/) listesinde bulunan XML [Schema](../../../system.xml.schema/) Definition Language (XSD) şemalarına karşı doğrular.

```cpp
void System::Xml::XmlDocument::Validate(Schema::ValidationEventHandler validationEventHandler)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| validationEventHandler | [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) | [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) nesnesi, şema doğrulama uyarıları ve hataları hakkında bilgi alır. |

## XmlDocument::Validate(Schema::ValidationEventHandler, const SharedPtr\<XmlNode\>\&) metodu

[XmlNode](../../xmlnode/) nesnesini [XmlDocument::get_Schemas](../get_schemas/) listesinde bulunan XML [Schema](../../../system.xml.schema/) Definition Language (XSD) şemalarına karşı doğrular.

```cpp
void System::Xml::XmlDocument::Validate(Schema::ValidationEventHandler validationEventHandler, const SharedPtr<XmlNode> &nodeToValidate)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| validationEventHandler | [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) | [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) nesnesi, şema doğrulama uyarıları ve hataları hakkında bilgi alır. |
| nodeToValidate | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | [XmlNode](../../xmlnode/) nesnesi, doğrulamak için bir [XmlDocument](../) üzerinden oluşturulur. |

## Ayrıca Bakınız

* Typedef [ValidationEventHandler](../../../system.xml.schema/validationeventhandler/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [XmlDocument](../)
* Sınıf [XmlNode](../../xmlnode/)
* Ad alanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)