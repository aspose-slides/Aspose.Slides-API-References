---
title: get_LocalName()
second_title: Aspose.Slides için C++ API Referansı
description: Türetilmiş bir sınıfta geçersiz kılındığında düğümün yerel adını döndürür.
type: docs
weight: 209
url: /tr/system.xml/xmlnode/get_localname/
---
## XmlNode::get_LocalName() metod


Türetilmiş bir sınıfta geçersiz kılındığında, düğümün yerel adını döndürür.

```cpp
virtual String System::Xml::XmlNode::get_LocalName()=0
```


### Dönüş Değeri

Önek kaldırılmış düğümün adı. Örneğin, **LocalName** elementi **<bk:book>** için **book** olur.
## Açıklamalar



Dönen ad, düğümün [XmlNode::get_NodeType](../get_nodetype/)'ine bağlıdır: 

| Tür | Ad |
| --- | --- |
| [Attribute](../../../system/attribute/)| Özelliğin yerel adı. |
| CDATA | #cdata-section |
| Comment | #comment |
| Document | #document |
| DocumentFragment | #document-fragment |
| DocumentType | Belge tipi adı. |
| Element | Öğenin yerel adı. |
| Entity | Varlığın adı. |
| EntityReference | Başvurulan varlığın adı. |
| Notation | İşaretleme adı. |
| ProcessingInstruction | İşlem talimatının hedefi. |
| [Text](../../../system.text/)| #text |
| Whitespace | #whitespace |
| SignificantWhitespace | #significant-whitespace |
| [XmlDeclaration](../../xmldeclaration/)| #xml-declaration |


## Diğer Bağlantılar

* Sınıf [String](../../../system/string/)
* Sınıf [XmlNode](../)
* Ad Alanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)