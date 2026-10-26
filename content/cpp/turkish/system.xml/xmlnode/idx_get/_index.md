---
title: idx_get()
second_title: Aspose.Slides for C++ API Referansı
description: "Belirtilen XmlNode::get_Name ile ilk alt öğeyi döndürür."
type: docs
weight: 586
url: /tr/system.xml/xmlnode/idx_get/
---
## XmlNode::idx_get(String) yöntemi


Belirtilen [XmlNode::get_Name](../get_name/) ile ilk alt öğeyi döndürür.

```cpp
virtual SharedPtr<XmlElement> System::Xml::XmlNode::idx_get(String name)
```


### Parametreler

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Alınacak öğenin nitelikli adı. |

### Dönüş Değeri

Belirtilen adla eşleşen ilk [XmlElement](../../xmlelement/). Eşleşme bulunamazsa **nullptr** döner.

## XmlNode::idx_get(String, String) yöntemi


Belirtilen [XmlNode::get_LocalName](../get_localname/) ve [XmlNode::get_NamespaceURI](../get_namespaceuri/) değerleriyle ilk alt öğeyi döndürür.

```cpp
virtual SharedPtr<XmlElement> System::Xml::XmlNode::idx_get(String localname, String ns)
```


### Parametreler

| Parameter | Type | Description |
| --- | --- | --- |
| localname | [String](../../../system/string/) | Öğenin yerel adı. |
| ns | [String](../../../system/string/) | Öğenin ad alanı URI'si. |

### Dönüş Değeri

Eşleşen **localname** ve **ns**'ye sahip ilk [XmlElement](../../xmlelement/). Eşleşme bulunamazsa **nullptr** döner.

## Diğer Bölümler

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [XmlElement](../../xmlelement/)
* Sınıf [String](../../../system/string/)
* Sınıf [XmlNode](../)
* Ad alanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)