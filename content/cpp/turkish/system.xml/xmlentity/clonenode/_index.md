---
title: CloneNode()
second_title: Aspose.Slides için C++ API Referansı
description: Bu düğümün bir kopyasını oluşturur. Entity düğümleri kopyalanamaz. Bu yöntemi bir XmlEntity nesnesi üzerinde çağırmak bir istisna fırlatır.
type: docs
weight: 170
url: /tr/system.xml/xmlentity/clonenode/
---
## XmlEntity::CloneNode(bool) metodu


Bu düğümün bir kopyasını oluşturur. Entity düğümleri kopyalanamaz. Bu yöntemi bir [XmlEntity](../) nesnesi üzerinde çağırmak bir istisna fırlatır.

```cpp
SharedPtr<XmlNode> System::Xml::XmlEntity::CloneNode(bool deep) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| deep | **bool** | **true** belirttiğiniz düğümün alt ağacını yinelemeli olarak kopyalamak için; **false** sadece düğümü kopyalamak için. |

### Dönüş Değeri

Metodun çağrıldığı [XmlNode](../../xmlnode/)'nin bir kopyası.

## Ayrıca Bakınız

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [XmlNode](../../xmlnode/)
* Sınıf [XmlEntity](../)
* Ad Alanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)