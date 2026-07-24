---
title: InsertAfter()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen düğümü, belirtilen referans düğümünün hemen sonrasına ekler.
type: docs
weight: 222
url: /tr/system.xml/xmlattribute/insertafter/
---
## XmlAttribute::InsertAfter(SharedPtr\<XmlNode\>, SharedPtr\<XmlNode\>) metot


Belirtilen düğümü, belirtilen referans düğümünün hemen sonuna ekler.

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttribute::InsertAfter(SharedPtr<XmlNode> newChild, SharedPtr<XmlNode> refChild) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | Eklenecek [XmlNode](../../xmlnode/). |
| refChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | [XmlNode](../../xmlnode/) referans düğümdür. **newChild**, **refChild**'ın sonrasına yerleştirilir. |

### Dönüş Değeri

Eklenen [XmlNode](../../xmlnode/).

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [XmlNode](../../xmlnode/)
* Sınıf [XmlAttribute](../)
* Ad alanı [System::Xml](../../)
* Library [Aspose.Slides](../../../)