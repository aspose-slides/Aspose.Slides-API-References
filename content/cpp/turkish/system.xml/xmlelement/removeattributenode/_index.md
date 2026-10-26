---
title: RemoveAttributeNode()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen XmlAttribute öğesini kaldırır.
type: docs
weight: 274
url: /tr/system.xml/xmlelement/removeattributenode/
---
## XmlElement::RemoveAttributeNode(SharedPtr\<XmlAttribute\>) metod


Belirtilen [XmlAttribute](../../xmlattribute/) öğesini kaldırır.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::RemoveAttributeNode(SharedPtr<XmlAttribute> oldAttr)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| oldAttr | [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\> | Kaldırılacak [XmlAttribute](../../xmlattribute/) düğümü. Kaldırılan özniteliğin varsayılan bir değeri varsa, hemen yerini alır. |

### Dönüş Değeri

Kaldırılan [XmlAttribute](../../xmlattribute/) veya **oldAttr** [XmlElement](../) içinde bir öznitelik düğümü değilse **nullptr**.

## XmlElement::RemoveAttributeNode(String, String) metod


Yerel ad ve ad alanı URI'siyle belirtilen [XmlAttribute](../../xmlattribute/) öğesini kaldırır. (Kaldırılan özniteliğin varsayılan bir değeri varsa, hemen yerini alır).

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::RemoveAttributeNode(String localName, String namespaceURI)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Özniteliğin yerel adı. |
| namespaceURI | [String](../../../system/string/) | Özniteliğin ad alanı URI'si. |

### Dönüş Değeri

Kaldırılan [XmlAttribute](../../xmlattribute/) veya **nullptr** eğer [XmlElement](../) eşleşen bir öznitelik düğümüne sahip değilse.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [XmlElement](../)
* Class [String](../../../system/string/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)