---
title: CloneNode()
second_title: Aspose.Slides for C++ API Referansı
description: Bu düğümün bir kopyasını oluşturur.
type: docs
weight: 79
url: /tr/system.xml/xmlsignificantwhitespace/clonenode/
---
## XmlSignificantWhitespace::CloneNode(bool) metodu


Bu düğümün bir kopyasını oluşturur.

```cpp
SharedPtr<XmlNode> System::Xml::XmlSignificantWhitespace::CloneNode(bool deep) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| deep | **bool** | **true** belirtilen düğüm altındaki alt ağacı özyinelemeli olarak klonlamak için; **false** yalnızca düğümü kendisini klonlamak için. Önemli beyaz boşluk düğümleri için, klonlanan düğüm her zaman veri değerini içerir, parametre ayarına bakılmaksızın. |

### Dönüş Değeri

Klonlanmış düğüm.

## Ayrıca Bakınız

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [XmlNode](../../xmlnode/)
* Sınıf [XmlSignificantWhitespace](../)
* Ad alanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)