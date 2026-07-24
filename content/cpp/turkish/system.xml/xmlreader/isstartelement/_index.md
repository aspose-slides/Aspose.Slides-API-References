---
title: IsStartElement()
second_title: Aspose.Slides için C++ API Referansı
description: "XmlReader::MoveToContent metodunu çağırır ve geçerli içerik düğümünün bir başlangıç etiketi veya boş eleman etiketi olup olmadığını test eder."
type: docs
weight: 885
url: /tr/system.xml/xmlreader/isstartelement/
---
## XmlReader::IsStartElement() method

[XmlReader::MoveToContent](../movetocontent/) çağırır ve geçerli içerik düğümünün bir başlangıç etiketi veya boş eleman etiketi olup olmadığını test eder.

```cpp
virtual bool System::Xml::XmlReader::IsStartElement()
```

### Return Value

**true** eğer [XmlReader::MoveToContent](../movetocontent/) bir başlangıç etiketi veya boş eleman etiketi bulursa; **false** eğer [XmlNodeType::Element](../../xmlnodetype/) dışındaki bir düğüm türü bulunmuşsa.

## XmlReader::IsStartElement(String) method

[XmlReader::MoveToContent](../movetocontent/) çağırır ve geçerli içerik düğümünün bir başlangıç etiketi veya boş eleman etiketi olup olmadığını ve bulunan elemanın [XmlReader::get_Name](../get_name/) değerinin verilen argümanla eşleşip eşleşmediğini test eder.

```cpp
virtual bool System::Xml::XmlReader::IsStartElement(String name)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Elemanın bulunan **Name** değeriyle eşleşen dize. |

### Return Value

**true** eğer oluşan düğüm bir eleman ise ve **Name** değeri belirtilen dizeyle eşleşiyorsa. **false** eğer [XmlNodeType::Element](../../xmlnodetype/) dışındaki bir düğüm türü bulunmuşsa veya elemanın **Name** değeri belirtilen dizeyle eşleşmiyorsa.

## XmlReader::IsStartElement(String, String) method

[XmlReader::MoveToContent](../movetocontent/) çağırır ve geçerli içerik düğümünün bir başlangıç etiketi veya boş eleman etiketi olup olmadığını ve bulunan elemanın [XmlReader::get_LocalName](../get_localname/) ve [XmlReader::get_NamespaceURI](../get_namespaceuri/) değerlerinin verilen dizelerle eşleşip eşleşmediğini test eder.

```cpp
virtual bool System::Xml::XmlReader::IsStartElement(String localname, String ns)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| localname | [String](../../../system/string/) | Elemanın bulunan **LocalName** değeriyle eşleşecek dize. |
| ns | [String](../../../system/string/) | Elemanın bulunan **NamespaceURI** değeriyle eşleşecek dize. |

### Return Value

**true** eğer oluşan düğüm bir eleman ise. **false** eğer [XmlNodeType::Element](../../xmlnodetype/) dışındaki bir düğüm türü bulunmuşsa veya elemanın **LocalName** ve **NamespaceURI** değerleri belirtilen dizelerle eşleşmiyorsa.

## See Also

* Class [XmlReader](../)
* Class [String](../../../system/string/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)