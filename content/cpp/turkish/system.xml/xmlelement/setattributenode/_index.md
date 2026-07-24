---
title: SetAttributeNode()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen XmlAttribute öğesini ekler.
type: docs
weight: 261
url: /tr/system.xml/xmlelement/setattributenode/
---
## XmlElement::SetAttributeNode(SharedPtr\<XmlAttribute\>) yöntemi


Belirtilen [XmlAttribute](../../xmlattribute/) ekler.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::SetAttributeNode(SharedPtr<XmlAttribute> newAttr)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newAttr | [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\> | Bu öğe için nitelik koleksiyonuna eklemek üzere [XmlAttribute](../../xmlattribute/) düğümü. |

### Dönüş Değeri

Eğer nitelik aynı ada sahip mevcut bir niteliği değiştiriyorsa, eski [XmlAttribute](../../xmlattribute/) döndürülür; aksi takdirde **nullptr** döndürülür.

## XmlElement::SetAttributeNode(String, String) yöntemi


Belirtilen [XmlAttribute](../../xmlattribute/) ekler.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::SetAttributeNode(String localName, String namespaceURI)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Niteliğin yerel adı. |
| namespaceURI | [String](../../../system/string/) | Niteliğin ad alanı URI'si. |

### Dönüş Değeri

Eklemek için [XmlAttribute](../../xmlattribute/).

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [XmlAttribute](../../xmlattribute/)
* Sınıf [XmlElement](../)
* Sınıf [String](../../../system/string/)
* Ad alanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)