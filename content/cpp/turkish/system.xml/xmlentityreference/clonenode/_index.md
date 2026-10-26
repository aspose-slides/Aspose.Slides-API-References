---
title: CloneNode()
second_title: Aspose.Slides for C++ API Referansı
description: Bu düğümün bir kopyasını oluşturur.
type: docs
weight: 92
url: /tr/system.xml/xmlentityreference/clonenode/
---
## XmlEntityReference::CloneNode(bool) metodu


Bu düğümün bir kopyasını oluşturur.

```cpp
SharedPtr<XmlNode> System::Xml::XmlEntityReference::CloneNode(bool deep) override
```


### Parametreler

| Parameter | Type | Description |
| --- | --- | --- |
| deep | **bool** | **true** belirtilen düğümün alt ağaç yapısını yinelemeli olarak kopyalamak için; **false** yalnızca düğümün kendisini kopyalamak için. [XmlEntityReference](../) düğümleri için, bu yöntem her zaman çocukları olmayan bir varlık referans düğümü döndürür. Düğüm bir üst düğüme eklendiğinde yerine konulan metin ayarlanır. |

### Dönüş Değeri

Kopyalanan düğüm.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [XmlNode](../../xmlnode/)
* Sınıf [XmlEntityReference](../)
* Ad alanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)