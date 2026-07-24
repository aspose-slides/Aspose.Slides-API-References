---
title: GetElementsByTagName()
second_title: C++ API Referansı için Aspose.Slides
description: Belirtilen adla eşleşen tüm alt öğelerin bir listesini içeren bir XmlNodeList döndürür.
type: docs
weight: 443
url: /tr/system.xml/xmldocument/getelementsbytagname/
---
## XmlDocument::GetElementsByTagName(String) metod


Belirtilen adla eşleşen tüm alt öğelerin bir listesini içeren bir [XmlNodeList](../../xmlnodelist/) döndürür.

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlDocument::GetElementsByTagName(String name)
```


### Arguments

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | [String](../../../system/string/) | Eşleşecek nitelikli ad. Eşleşen düğümün **get_Name** değerine karşı karşılaştırılır. Özel değer **\"*\"** tüm etiketleri eşleştirir. |

### Dönüş Değeri

[XmlNodeList](../../xmlnodelist/) döndürür; bu, tüm eşleşen düğümlerin bir listesini içerir. Hiçbir düğüm **name** ile eşleşmezse, döndürülen koleksiyon boş olur.

## XmlDocument::GetElementsByTagName(String, String) metod


Belirtilen [XmlDocument::get_LocalName](../get_localname/) ve [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) ile eşleşen tüm alt öğelerin bir listesini içeren bir [XmlNodeList](../../xmlnodelist/) döndürür.

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlDocument::GetElementsByTagName(String localName, String namespaceURI)
```


### Arguments

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Eşleşecek LocalName. Özel değer **\"*\"** tüm etiketleri eşleştirir. |
| namespaceURI | [String](../../../system/string/) | Eşleşecek NamespaceURI. |

### Dönüş Değeri

[XmlNodeList](../../xmlnodelist/) döndürür; bu, tüm eşleşen düğümlerin bir listesini içerir. Belirtilen **localName** ve **namespaceURI** ile eşleşen düğüm yoksa, döndürülen koleksiyon boş olur.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [XmlNodeList](../../xmlnodelist/)
* Sınıf [String](../../../system/string/)
* Sınıf [XmlDocument](../)
* Ad Alanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)