---
title: CloneNode()
second_title: Aspose.Slides için C++ API Referansı
description: Bu düğümün bir kopyasını oluşturur.
type: docs
weight: 157
url: /tr/system.xml/xmldeclaration/clonenode/
---
## XmlDeclaration::CloneNode(bool) metodu

Bu düğümün bir kopyasını oluşturur.

```cpp
SharedPtr<XmlNode> System::Xml::XmlDeclaration::CloneNode(bool deep) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| deep | **bool** | **true** belirtilen düğümün alt ağaç yapısını özyinelemeli olarak kopyalamak için; **false** yalnızca düğümü kendisini kopyalamak için. [XmlDeclaration](../) düğümlerinin çocuğu olmadığından, kopyalanan düğüm her zaman veri değerini içerir, parametre ayarına bakılmaksızın. |

### Dönüş Değeri

Kopyalanan düğüm.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [XmlNode](../../xmlnode/)
* Sınıf [XmlDeclaration](../)
* İsim Alanı [System::Xml](../../)
* Library [Aspose.Slides](../../../)