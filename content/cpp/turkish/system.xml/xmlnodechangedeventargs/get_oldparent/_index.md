---
title: get_OldParent()
second_title: Aspose.Slides for C++ API Referansı
description: "İşlem başlamadan önce XmlNode::get_ParentNode değerini döndürür."
type: docs
weight: 27
url: /tr/system.xml/xmlnodechangedeventargs/get_oldparent/
---
## XmlNodeChangedEventArgs::get_OldParent() metod


İşlem başlamadan önce [XmlNode::get_ParentNode](../../xmlnode/get_parentnode/) değerini döndürür.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNodeChangedEventArgs::get_OldParent()
```


### Dönüş Değeri

İşlem başlamadan önce **ParentNode** değeridir. Düğümün bir üst öğesi yoksa bu metod **nullptr** döndürür. Öznitelik düğümleri için bu metod [XmlAttribute::get_OwnerElement](../../xmlattribute/get_ownerelement/) değerini döndürür.

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [XmlNode](../../xmlnode/)
* Sınıf [XmlNodeChangedEventArgs](../)
* Ad alanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)