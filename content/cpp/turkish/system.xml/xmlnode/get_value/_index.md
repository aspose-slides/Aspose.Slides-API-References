---
title: get_Value()
second_title: Aspose.Slides için C++ API Referansı
description: Düğümün değerini döndürür.
type: docs
weight: 14
url: /tr/system.xml/xmlnode/get_value/
---
## XmlNode::get_Value() yöntemi


Düğümün değerini döndürür.

```cpp
virtual String System::Xml::XmlNode::get_Value()
```


### Dönüş Değeri

Dönen değer, düğümün [XmlNode::get_NodeType](../get_nodetype/)'ine bağlıdır: 

| Tür | Değer |
| --- | --- |
| [Attribute](../../../system/attribute/)| Özniteliğin değeri. |
| CDATASection | CDATA Bölümünün içeriği. |
| Comment | Yorumun içeriği. |
| Document | `nullptr`. |
| DocumentFragment | `nullptr`. |
| DocumentType | `nullptr`. |
| Element | `nullptr`. XmlElement::InnerText veya [XmlElement::get_InnerXml](../../xmlelement/get_innerxml/) değerlerini kullanarak element düğümünün değerine erişebilirsiniz. |
| Entity | `nullptr`. |
| EntityReference | `nullptr`. |
| Notation | `nullptr`. |
| ProcessingInstruction | Hedef hariç tüm içerik. |
| [Text](../../../system.text/)| Metin düğümünün içeriği. |
| SignificantWhitespace | Beyaz boşluk karakterleri. Beyaz boşluk bir veya daha fazla boşluk karakteri, satırbaşı, yeni satır veya sekme karakterlerinden oluşabilir. |
| Whitespace | Beyaz boşluk karakterleri. Beyaz boşluk bir veya daha fazla boşluk karakteri, satırbaşı, yeni satır veya sekme karakterlerinden oluşabilir. |
| [XmlDeclaration](../../xmldeclaration/)| Deklarasyonun içeriği (yani `<?xml` ile `?>` arasındaki her şey). |

## Ayrıca Bakınız

* Sınıf [String](../../../system/string/)
* Sınıf [XmlNode](../)
* Ad alanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)