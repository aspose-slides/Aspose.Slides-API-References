---
title: GetAttributeNode()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen adla XmlAttribute döndürür.
type: docs
weight: 248
url: /tr/system.xml/xmlelement/getattributenode/
---
## XmlElement::GetAttributeNode(String) yöntemi


Belirtilen adla [XmlAttribute](../../xmlattribute/) döndürür.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::GetAttributeNode(String name)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | [String](../../../system/string/) | Alınacak özniteliğin adı. Bu, nitelikli bir addır. Eşleşen düğümün **get_Name** değeriyle karşılaştırılır. |

### Dönüş Değeri

Belirtilen [XmlAttribute](../../xmlattribute/) ya da eşleşen bir öznitelik bulunamazsa **nullptr**.

## XmlElement::GetAttributeNode(String, String) yöntemi


Belirtilen yerel ad ve ad alanı URI'siyle [XmlAttribute](../../xmlattribute/) döndürür.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::GetAttributeNode(String localName, String namespaceURI)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Özniteliğin yerel adı. |
| namespaceURI | [String](../../../system/string/) | Özniteliğin ad alanı URI'si. |

### Dönüş Değeri

Belirtilen [XmlAttribute](../../xmlattribute/) ya da eşleşen bir öznitelik bulunamazsa **nullptr**.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [XmlAttribute](../../xmlattribute/)
* Sınıf [String](../../../system/string/)
* Sınıf [XmlElement](../)
* Ad alanı [System::Xml](../../)
* Library [Aspose.Slides](../../../)