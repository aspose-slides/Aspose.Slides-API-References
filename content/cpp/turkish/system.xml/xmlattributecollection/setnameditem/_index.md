---
title: SetNamedItem()
second_title: Aspose.Slides için C++ API Referansı
description: "XmlNode::get_Name sonucunu kullanarak bir XmlNode ekler."
type: docs
weight: 14
url: /tr/system.xml/xmlattributecollection/setnameditem/
---
## XmlAttributeCollection::SetNamedItem(SharedPtr\<XmlNode\>) metodu

Bir [XmlNode](../../xmlnode/) ekler ve [XmlNode::get_Name](../../xmlnode/get_name/) sonucunu kullanır.

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttributeCollection::SetNamedItem(SharedPtr<XmlNode> node) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| node | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | Bu koleksiyonda saklanacak bir öznitelik düğümü. node daha sonra düğümün adıyla erişilebilir olacaktır. Bu adla bir node zaten koleksiyonda mevcutsa, yeni node ile değiştirilir; aksi takdirde, node koleksiyonun sonuna eklenir. |

### Dönüş Değeri

Eğer **node** aynı isimde mevcut bir node'ı değiştirirse, eski node döndürülür; aksi takdirde, eklenen node döndürülür.

## Ayrıca Bakınız

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [XmlNode](../../xmlnode/)
* Sınıf [XmlAttributeCollection](../)
* Ad Alanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)