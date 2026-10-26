---
title: get_NewParent()
second_title: Aspose.Slides for C++ API Referansı
description: "İşlem tamamlandıktan sonra XmlNode::get_ParentNode değerini döndürür."
type: docs
weight: 40
url: /tr/system.xml/xmlnodechangedeventargs/get_newparent/
---
## XmlNodeChangedEventArgs::get_NewParent() yöntem

İşlem tamamlandıktan sonra [XmlNode::get_ParentNode](../../xmlnode/get_parentnode/) değerini döndürür.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNodeChangedEventArgs::get_NewParent()
```

### Dönüş Değeri

İşlem tamamlandıktan sonra **ParentNode** değeridir. Düğüm kaldırılıyorsa bu yöntem **nullptr** döndürür. Öznitel düğümleri için bu yöntem [XmlAttribute::get_OwnerElement](../../xmlattribute/get_ownerelement/) değerini döndürür.

## Ayrıca Bak

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [XmlNode](../../xmlnode/)
* Sınıf [XmlNodeChangedEventArgs](../)
* İsim Uzayı [System::Xml](../../)
* Library [Aspose.Slides](../../../)