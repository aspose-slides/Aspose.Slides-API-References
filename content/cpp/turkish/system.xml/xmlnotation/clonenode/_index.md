---
title: CloneNode()
second_title: Aspose.Slides for C++ API Referansı
description: Bu düğümün bir kopyasını oluşturur. Notation düğümleri kopyalanamaz. Bu yöntemi bir XmlNotation nesnesi üzerinde çağırmak bir istisna fırlatır.
type: docs
weight: 118
url: /tr/system.xml/xmlnotation/clonenode/
---
## XmlNotation::CloneNode(bool) metodu

Bu düğümün bir kopyasını oluşturur. Notation düğümleri kopyalanamaz. Bu metodu bir [XmlNotation](../) nesnesi üzerinde çağırmak bir istisna fırlatır.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNotation::CloneNode(bool deep) override
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| deep | **bool** | **true** belirtilen düğümün alt ağacını yinelemeli olarak kopyalamak için; **false** sadece düğümü kopyalamak için. |

### Dönüş Değeri

Metodun çağrıldığı düğümün bir [XmlNode](../../xmlnode/) kopyası.

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [XmlNode](../../xmlnode/)
* Sınıf [XmlNotation](../)
* AdAlanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)