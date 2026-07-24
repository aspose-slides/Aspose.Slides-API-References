---
title: SetNamedItem()
second_title: Aspose.Slides için C++ API Referansı
description: "XmlNode::get_Name değerini kullanarak bir XmlNode ekler."
type: docs
weight: 27
url: /tr/system.xml/xmlnamednodemap/setnameditem/
---
## XmlNamedNodeMap::SetNamedItem(SharedPtr\<XmlNode\>) metodu


Kendi [XmlNode::get_Name](../../xmlnode/get_name/) değerini kullanarak bir [XmlNode](../../xmlnode/) ekler.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::SetNamedItem(SharedPtr<XmlNode> node)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| node | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | Bir [XmlNode](../../xmlnode/) [XmlNamedNodeMap](../) içinde saklanacak. Aynı isimde bir düğüm zaten haritada mevcutsa, yeni olanla değiştirilir. |

### Dönüş Değeri

**node** aynı isimde mevcut bir düğümü değiştirirse, eski düğüm geri döndürülür; aksi takdirde, **nullptr** döndürülür.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [XmlNode](../../xmlnode/)
* Sınıf [XmlNamedNodeMap](../)
* Ad alanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)