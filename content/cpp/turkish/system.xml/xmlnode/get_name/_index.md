---
title: get_Name()
second_title: Aspose.Slides for C++ API Referansı
description: Türetilmiş bir sınıfta geçersiz kılındığında düğümün nitelikli adını döndürür.
type: docs
weight: 1
url: /tr/system.xml/xmlnode/get_name/
---
## XmlNode::get_Name() metodu


Türetilmiş bir sınıfta geçersiz kılındığında, düğümün nitelikli adını döndürür.

```cpp
virtual String System::Xml::XmlNode::get_Name()=0
```


### Dönüş Değeri

Düğümün nitelikli adı.
## Açıklama



Dönen ad, düğümün [XmlNode::get_NodeType](../get_nodetype/) değerine bağlıdır: 

| Tür | Ad |
| --- | --- |
| [Attribute](../../../system/attribute/)| Özniteliğin nitelikli adı. |
| CDATA | #cdata-section |
| Comment | #comment |
| Document | #document |
| DocumentFragment | #document-fragment |
| DocumentType | Belge türü adı. |
| Element | Öğenin nitelikli adı. |
| Entity | Varlığın adı. |
| EntityReference | Referans verilen varlığın adı. |
| Notation | Notasyon adı. |
| ProcessingInstruction | İşlem talimatının hedefi. |
| [Text](../../../system.text/)| #text |
| Whitespace | #whitespace |
| SignificantWhitespace | #significant-whitespace |
| [XmlDeclaration](../../xmldeclaration/)| #xml-declaration |


## Diğer Bağlantılar

* Sınıf [String](../../../system/string/)
* Sınıf [XmlNode](../)
* Ad alanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)