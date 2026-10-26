---
title: ReadNode()
second_title: Aspose.Slides için C++ API Referansı
description: XmlReader'daki bilgiler temel alınarak bir XmlNode nesnesi oluşturur. Okuyucu bir düğüm veya öznitelik üzerinde konumlandırılmalıdır.
type: docs
weight: 495
url: /tr/system.xml/xmldocument/readnode/
---
## XmlDocument::ReadNode(SharedPtr\<XmlReader\>) metod


Belirtilen [XmlReader](../../xmlreader/)'deki bilgilere dayanarak bir [XmlNode](../../xmlnode/) nesnesi oluşturur. Okuyucu bir düğüm veya öznitelik üzerinde konumlandırılmalıdır.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::ReadNode(SharedPtr<XmlReader> reader)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| reader | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\> | XML kaynağı. |

### Dönüş Değeri

Daha fazla düğüm kalmadığında yeni [XmlNode](../../xmlnode/) veya **nullptr**.

## Ayrıca

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [XmlNode](../../xmlnode/)
* Sınıf [XmlReader](../../xmlreader/)
* Sınıf [XmlDocument](../)
* Ad alanı [System::Xml](../../)
* Library [Aspose.Slides](../../../)