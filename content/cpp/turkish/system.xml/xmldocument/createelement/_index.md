---
title: CreateElement()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen adla bir element oluşturur.
type: docs
weight: 339
url: /tr/system.xml/xmldocument/createelement/
---
## XmlDocument::CreateElement(const String\&) yöntemi


Belirtilen adla bir element oluşturur.

```cpp
SharedPtr<XmlElement> System::Xml::XmlDocument::CreateElement(const String &name)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Elementin nitelikli adı. Eğer ad bir iki nokta üst üste içeriyorsa, [XmlNode::get_Prefix](../../xmlnode/get_prefix/) değeri iki nokta üst üstenin önündeki kısmı yansıtır ve [XmlDocument::get_LocalName](../get_localname/) değeri iki nokta üst üstenin sonraki kısmını yansıtır. Nitelikli ad **xmlns** önekini içeremez. |

### Dönüş Değeri

Yeni [XmlElement](../../xmlelement/).

## XmlDocument::CreateElement(const String\&, const String\&) yöntemi


Nitelikli ad ve [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) ile bir [XmlElement](../../xmlelement/) oluşturur.

```cpp
SharedPtr<XmlElement> System::Xml::XmlDocument::CreateElement(const String &qualifiedName, const String &namespaceURI)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| qualifiedName | const [String](../../../system/string/)\& | Elementin nitelikli adı. Eğer ad bir iki nokta üst üste içeriyorsa, [XmlNode::get_Prefix](../../xmlnode/get_prefix/) değeri iki nokta üst üstenin önündeki kısmı yansıtır ve [XmlDocument::get_LocalName](../get_localname/) değeri iki nokta üst üstenin sonraki kısmını yansıtır. Nitelikli ad **xmlns** önekini içeremez. |
| namespaceURI | const [String](../../../system/string/)\& | Elementin ad alanı URI’si. |

### Dönüş Değeri

Yeni [XmlElement](../../xmlelement/).

## XmlDocument::CreateElement(const String\&, const String\&, const String\&) yöntemi


Belirtilen [XmlNode::get_Prefix](../../xmlnode/get_prefix/), [XmlDocument::get_LocalName](../get_localname/) ve [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) ile bir element oluşturur.

```cpp
virtual SharedPtr<XmlElement> System::Xml::XmlDocument::CreateElement(const String &prefix, const String &localName, const String &namespaceURI)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Yeni elementin ön eki (varsa). [String::Empty](../../../system/string/empty/) ve **nullptr** eşdeğerdir. |
| localName | const [String](../../../system/string/)\& | Yeni elementin yerel adı. |
| namespaceURI | const [String](../../../system/string/)\& | Yeni elementin ad alanı URI’si (varsa). [String::Empty](../../../system/string/empty/) ve **nullptr** eşdeğerdir. |

### Dönüş Değeri

Yeni [XmlElement](../../xmlelement/).

## Diğer Bağlantılar

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [XmlElement](../../xmlelement/)
* Sınıf [String](../../../system/string/)
* Sınıf [XmlDocument](../)
* Ad Alanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)