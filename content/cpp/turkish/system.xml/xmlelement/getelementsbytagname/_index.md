---
title: GetElementsByTagName()
second_title: Aspose.Slides için C++ API Referansı
description: "Belirtilen XmlElement::get_Name ile eşleşen tüm alt öğelerin bir listesini içeren bir XmlNodeList döndürür."
type: docs
weight: 287
url: /tr/system.xml/xmlelement/getelementsbytagname/
---
## XmlElement::GetElementsByTagName(String) metodu

Belirtilen [XmlElement::get_Name](../get_name/) ile eşleşen tüm alt öğelerin bir listesini içeren bir [XmlNodeList](../../xmlnodelist/) döndürür.

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlElement::GetElementsByTagName(String name)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | [String](../../../system/string/) | Eşleşecek ad etiketi. Bu nitelikli bir isimdir. Eşleşen düğümün **get_Name** değeriyle karşılaştırılır. Yıldız işareti (*) tüm etiketlerle eşleşen özel bir değerdir. |

### Dönüş Değeri

Eşleşen tüm düğümlerin bir listesini içeren bir [XmlNodeList](../../xmlnodelist/). Eşleşen düğüm yoksa liste boştur.

## XmlElement::GetElementsByTagName(String, String) metodu

Belirtilen [XmlElement::get_LocalName](../get_localname/) ve [XmlElement::get_NamespaceURI](../get_namespaceuri/) değerleriyle eşleşen tüm alt öğelerin bir listesini içeren bir [XmlNodeList](../../xmlnodelist/) döndürür.

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlElement::GetElementsByTagName(String localName, String namespaceURI)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Eşleşecek yerel ad. Yıldız işareti (*) tüm etiketlerle eşleşen özel bir değerdir. |
| namespaceURI | [String](../../../system/string/) | Eşleşecek isim alanı URI'si. |

### Dönüş Değeri

Eşleşen tüm düğümlerin bir listesini içeren bir [XmlNodeList](../../xmlnodelist/). Eşleşen düğüm yoksa liste boştur.

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [XmlNodeList](../../xmlnodelist/)
* Sınıf [String](../../../system/string/)
* Sınıf [XmlElement](../)
* İsim Alanı [System::Xml](../../)
* Library [Aspose.Slides](../../../)