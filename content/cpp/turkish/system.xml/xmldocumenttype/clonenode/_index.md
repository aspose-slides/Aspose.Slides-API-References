---
title: CloneNode()
second_title: Aspose.Slides C++ API Referansı
description: Bu düğümün bir kopyasını oluşturur.
type: docs
weight: 118
url: /tr/system.xml/xmldocumenttype/clonenode/
---
## XmlDocumentType::CloneNode(bool) method

Bu düğümün bir kopyasını oluşturur.

```cpp
SharedPtr<XmlNode> System::Xml::XmlDocumentType::CloneNode(bool deep) override
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| deep | **bool** | **true** belirtilen düğümün altındaki alt ağacı yinelemeli olarak klonlamak için; **false** yalnızca düğümü klonlamak için. Belge tipi düğümler için, klonlanan düğüm her zaman alt ağacı içerir, parametre ayarına bakılmaksızın. |

### Dönüş Değeri

Klonlanan düğüm.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlDocumentType](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)