---
title: PrependChild()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen düğümü bu düğümün çocuk düğüm listesine baştan ekler.
type: docs
weight: 261
url: /tr/system.xml/xmlattribute/prependchild/
---
## XmlAttribute::PrependChild(SharedPtr\<XmlNode\>) metodu

Belirtilen düğümü bu düğümün çocuk düğüm listesine baştan ekler.

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttribute::PrependChild(SharedPtr<XmlNode> newChild) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | Eklenecek [XmlNode](../../xmlnode/). Eğer bir [XmlDocumentFragment](../../xmldocumentfragment/) ise, belge parçacığının tüm içeriği bu düğümün çocuk listesine taşınır. |

### Dönüş Değeri

Eklenen [XmlNode](../../xmlnode/).

## Ayrıca bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [XmlNode](../../xmlnode/)
* Sınıf [XmlAttribute](../)
* Ad alanı [System::Xml](../../)
* Library [Aspose.Slides](../../../)