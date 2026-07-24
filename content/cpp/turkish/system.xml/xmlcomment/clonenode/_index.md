---
title: CloneNode()
second_title: Aspose.Slides için C++ API Referansı
description: Bu düğümün bir kopyasını oluşturur.
type: docs
weight: 40
url: /tr/system.xml/xmlcomment/clonenode/
---
## XmlComment::CloneNode(bool) metodu

Bu düğümün bir kopyasını oluşturur.

```cpp
SharedPtr<XmlNode> System::Xml::XmlComment::CloneNode(bool deep) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| deep | **bool** | **true** belirtilen düğümün alt ağacını yinelemeli olarak kopyalamak için; **false** yalnızca düğümü kopyalamak için. Yorum düğümlerinin çocuğu olmadığından, kopyalanan düğüm her zaman metin içeriğini içerir, parametre ayarına bakılmaksızın. |

### Dönüş Değeri

Klonlanan düğüm.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [XmlNode](../../xmlnode/)
* Sınıf [XmlComment](../)
* İsim Uzayı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)