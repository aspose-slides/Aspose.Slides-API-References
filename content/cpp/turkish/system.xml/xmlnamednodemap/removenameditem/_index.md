---
title: RemoveNamedItem()
second_title: Aspose.Slides for C++ API Referansı
description: XmlNamedNodeMap'ten düğümü kaldırır.
type: docs
weight: 40
url: /tr/system.xml/xmlnamednodemap/removenameditem/
---
## XmlNamedNodeMap::RemoveNamedItem(String) method


Düğümü [XmlNamedNodeMap](../)'den kaldırır.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::RemoveNamedItem(String name)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | [String](../../../system/string/) | Kaldırılacak düğümün nitelikli adı. Ad, eşleşen düğümün [XmlNode::get_Name](../../xmlnode/get_name/) değeriyle karşılaştırılır. |

### Dönüş Değeri

[XmlNode](../../xmlnode/) bu [XmlNamedNodeMap](../)'den kaldırıldı veya eşleşen bir düğüm bulunamazsa **nullptr** döndürülür.

## XmlNamedNodeMap::RemoveNamedItem(String, String) method


[XmlNode::get_LocalName](../../xmlnode/get_localname/) ve [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) değerleriyle eşleşen bir düğümü kaldırır.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::RemoveNamedItem(String localName, String namespaceURI)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Kaldırılacak düğümün yerel adı. |
| namespaceURI | [String](../../../system/string/) | Kaldırılacak düğümün ad alanı URI'si. |

### Dönüş Değeri

[XmlNode](../../xmlnode/) kaldırıldı veya eşleşen bir düğüm bulunamazsa **nullptr** döndürülür.

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [XmlNode](../../xmlnode/)
* Sınıf [String](../../../system/string/)
* Sınıf [XmlNamedNodeMap](../)
* Ad Alanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)