---
title: CreateAttribute()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen adla bir XmlAttribute oluşturur.
type: docs
weight: 274
url: /tr/system.xml/xmldocument/createattribute/
---
## XmlDocument::CreateAttribute(const String\&) method

Belirtilen adla bir [XmlAttribute](../../xmlattribute/) oluşturur.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlDocument::CreateAttribute(const String &name)
```

### Arguments

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Ö
zelliğin nitelikli adı. İsim bir iki nokta üst üste içeriyorsa, [XmlNode::get_Prefix](../../xmlnode/get_prefix/) değeri ismin ilk iki nokta üst üstenin öncesindeki bölümünü, [XmlDocument::get_LocalName](../get_localname/) değeri ise ilk iki nokta üst üsteren sonraki bölümünü yansıtır. [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) yalnızca önek **xmlns** gibi tanınmış bir yerleşik önek olmadıkça boş kalır. Bu durumda get_NamespaceURI, [http://www.w3.org/2000/xmlns/](http://www.w3.org/2000/xmlns/) değerine sahiptir. |

### Dönüş Değeri

Yeni [XmlAttribute](../../xmlattribute/).

## XmlDocument::CreateAttribute(const String\&, const String\&) method

Belirtilen nitelikli ad ve [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) ile bir [XmlAttribute](../../xmlattribute/) oluşturur.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlDocument::CreateAttribute(const String &qualifiedName, const String &namespaceURI)
```

### Arguments

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| qualifiedName | const [String](../../../system/string/)\& | Özelliğin nitelikli adı. İsim bir iki nokta üst üste içeriyorsa, [XmlNode::get_Prefix](../../xmlnode/get_prefix/) değeri iki nokta üst üstenin öncesindeki bölümü, [XmlDocument::get_LocalName](../get_localname/) değeri ise iki nokta üst üsten sonraki bölümü yansıtır. |
| namespaceURI | const [String](../../../system/string/)\& | Özelliğin namespaceURI'si. Nitelikli ad **xmlns** önekini içeriyorsa, bu parametre [http://www.w3.org/2000/xmlns/](http://www.w3.org/2000/xmlns/) olmalıdır. |

### Dönüş Değeri

Yeni [XmlAttribute](../../xmlattribute/).

## XmlDocument::CreateAttribute(const String\&, const String\&, const String\&) method

Belirtilen [XmlNode::get_Prefix](../../xmlnode/get_prefix/), [XmlDocument::get_LocalName](../get_localname/) ve [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) ile bir [XmlAttribute](../../xmlattribute/) oluşturur.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlDocument::CreateAttribute(const String &prefix, const String &localName, const String &namespaceURI)
```

### Arguments

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Özelliğin öneki (varsa). [String::Empty](../../../system/string/empty/) ve **nullptr** eşdeğerdir. |
| localName | const [String](../../../system/string/)\& | Özelliğin yerel adı. |
| namespaceURI | const [String](../../../system/string/)\& | Özelliğin namespace URI'si (varsa). [String::Empty](../../../system/string/empty/) ve **nullptr** eşdeğerdir. **prefix** **xmlns** ise, bu parametre [http://www.w3.org/2000/xmlns/;](http://www.w3.org/2000/xmlns/;) olmalıdır; aksi takdirde bir istisna fırlatılır. |

### Dönüş Değeri

Yeni [XmlAttribute](../../xmlattribute/).

## Diğer Bilgiler

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)