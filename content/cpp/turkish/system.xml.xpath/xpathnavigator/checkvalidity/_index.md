---
title: CheckValidity()
second_title: Aspose.Slides for C++ API Referansı
description: XPathNavigator içindeki XML verisinin, sağlanan XML Schema tanım dili (XSD) şemasına uygun olduğunu doğrular.
type: docs
weight: 755
url: /tr/system.xml.xpath/xpathnavigator/checkvalidity/
---
## XPathNavigator::CheckValidity(SharedPtr\<System::Xml::Schema::XmlSchemaSet\>, System::Xml::Schema::ValidationEventHandler) method

[XPathNavigator](../) içindeki XML verisinin, sağlanan XML [Schema](../../../system.xml.schema/) tanım dili (XSD) şemasına uygun olduğunu doğrular.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::CheckValidity(SharedPtr<System::Xml::Schema::XmlSchemaSet> schemas, System::Xml::Schema::ValidationEventHandler validationEventHandler)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| schemas | [SharedPtr](../../../system/sharedptr/)\<[System::Xml::Schema::XmlSchemaSet](../../../system.xml.schema/xmlschemaset/)\> | [XPathNavigator](../) içinde bulunan XML verisini doğrulamak için kullanılan şemaları içeren XmlSchemaSet. |
| validationEventHandler | [System::Xml::Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) | Şema doğrulama uyarıları ve hataları hakkında bilgi alan ValidationEventHandler. |

### Dönüş Değeri

**true** if no schema validation errors occurred; otherwise, **false**.

## Başvurular

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ValidationEventHandler](../../../system.xml.schema/validationeventhandler/)
* Sınıf [XmlSchemaSet](../../../system.xml.schema/xmlschemaset/)
* Sınıf [XPathNavigator](../)
* Ad alanı [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)