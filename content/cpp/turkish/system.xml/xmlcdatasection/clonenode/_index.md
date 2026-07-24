---
title: CloneNode()
second_title: Aspose.Slides için C++ API Referansı
description: Bu düğümün bir kopyasını oluşturur.
type: docs
weight: 53
url: /tr/system.xml/xmlcdatasection/clonenode/
---
## XmlCDataSection::CloneNode(bool) metodu


Bu düğümün bir kopyasını oluşturur.

```cpp
SharedPtr<XmlNode> System::Xml::XmlCDataSection::CloneNode(bool deep) override
```


### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| deep | **bool** | **true** belirtilen düğümün alt ağacını özyinelemeli olarak kopyalamak için; **false** yalnızca düğümü kopyalamak için. CDATA düğümlerinin çocuğu olmadığından, parametre ayarından bağımsız olarak, kopyalanan düğüm her zaman veri içeriğini içerecektir. |

### Dönüş Değeri

Kopyalanan düğüm.

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [XmlNode](../../xmlnode/)
* Sınıf [XmlCDataSection](../)
* Ad alanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)