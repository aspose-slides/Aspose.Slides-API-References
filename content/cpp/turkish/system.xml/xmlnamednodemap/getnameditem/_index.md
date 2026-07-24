---
title: GetNamedItem()
second_title: Aspose.Slides for C++ API Referansı
description: Adına göre belirtilen bir XmlNode alır.
type: docs
weight: 14
url: /tr/system.xml/xmlnamednodemap/getnameditem/
---
## XmlNamedNodeMap::GetNamedItem(String) metot

Adına göre belirtilen bir [XmlNode](../../xmlnode/) alır.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::GetNamedItem(String name)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | [String](../../../system/string/) | Alınacak düğümün nitelikli adı. Eşleşen düğümün [XmlNode::get_Name](../../xmlnode/get_name/) değeriyle karşılaştırılır. |

### Dönüş Değeri

Belirtilen ada sahip bir [XmlNode](../../xmlnode/) veya eşleşen düğüm bulunamazsa **nullptr**.

## XmlNamedNodeMap::GetNamedItem(String, String) metot

Eşleşen [XmlNode::get_LocalName](../../xmlnode/get_localname/) ve [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) değerlerine sahip bir düğüm alır.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::GetNamedItem(String localName, String namespaceURI)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Alınacak düğümün yerel adı. |
| namespaceURI | [String](../../../system/string/) | Alınacak düğümün ad alanı Evrensel Kaynak Tanımlayıcısı (URI)'si. |

### Dönüş Değeri

Eşleşen yerel adı ve ad alanı URI'sine sahip bir [XmlNode](../../xmlnode/) veya eşleşen düğüm bulunamazsa **nullptr**.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [XmlNode](../../xmlnode/)
* Sınıf [String](../../../system/string/)
* Sınıf [XmlNamedNodeMap](../)
* Ad Alanı [System::Xml](../../)
* Library [Aspose.Slides](../../../)