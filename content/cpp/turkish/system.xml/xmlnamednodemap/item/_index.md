---
title: Item()
second_title: Aspose.Slides for C++ API Referansı
description: XmlNamedNodeMap içinde belirtilen indeksdeki düğümü alır.
type: docs
weight: 53
url: /tr/system.xml/xmlnamednodemap/item/
---
## XmlNamedNodeMap::Item(int32_t) yöntemi

[XmlNamedNodeMap](../) içinde belirtilen dizindeki düğümü alır.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::Item(int32_t index)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | Düğümü [XmlNamedNodeMap](../)'den almak için kullanılan dizin konumu. Dizin sıfır tabanlıdır; bu nedenle ilk düğümün dizini 0 ve son düğümün dizini [XmlNamedNodeMap::get_Count](../get_count/) - 1'dir. |

### Dönüş Değeri

Belirtilen dizindeki [XmlNode](../../xmlnode/). **index** 0'dan küçük veya [XmlNamedNodeMap::get_Count](../get_count/) değerine eşit ya da büyük olduğunda, **nullptr** döndürülür.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [XmlNode](../../xmlnode/)
* Sınıf [XmlNamedNodeMap](../)
* AdAlanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)