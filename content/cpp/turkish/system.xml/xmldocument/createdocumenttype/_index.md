---
title: CreateDocumentType()
second_title: Aspose.Slides for C++ API Referansı
description: Yeni bir XmlDocumentType nesnesi döndürür.
type: docs
weight: 313
url: /tr/system.xml/xmldocument/createdocumenttype/
---
## XmlDocument::CreateDocumentType(const String\&, const String\&, const String\&, const String\&) yöntemi

Yeni bir [XmlDocumentType](../../xmldocumenttype/) nesnesi döndürür.

```cpp
virtual SharedPtr<XmlDocumentType> System::Xml::XmlDocument::CreateDocumentType(const String &name, const String &publicId, const String &systemId, const String &internalSubset)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Belge türünün adı. |
| publicId | const [String](../../../system/string/)\& | Belge türünün ortak tanımlayıcısı ya da **nullptr**. Ortak bir URI ve ayrıca dış DTD alt kümesinin konumunu belirlemek için bir sistem tanımlayıcısı belirtebilirsiniz. |
| systemId | const [String](../../../system/string/)\& | Belge türünün sistem tanımlayıcısı ya da **nullptr**. Dış DTD alt kümesi için dosya konumunun URL'sini belirtir. |
| internalSubset | const [String](../../../system/string/)\& | Belge türünün DTD iç alt kümesi ya da **nullptr**. |

### Dönüş Değeri

Yeni [XmlDocumentType](../../xmldocumenttype/).

## Ayrıca Bakınız

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [XmlDocumentType](../../xmldocumenttype/)
* Sınıf [String](../../../system/string/)
* Sınıf [XmlDocument](../)
* Ad Alanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)