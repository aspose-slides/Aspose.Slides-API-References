---
title: get_Name()
second_title: Aspose.Slides için C++ API Referansı
description: Türetilmiş bir sınıfta geçersiz kılındığında, geçerli düğümün nitelikli adını alır.
type: docs
weight: 27
url: /tr/system.xml/xmlreader/get_name/
---
## XmlReader::get_Name() yöntemi


Türetilmiş bir sınıfta geçersiz kılındığında, mevcut düğümün nitelikli adını alır.

```cpp
virtual String System::Xml::XmlReader::get_Name()
```


### Dönüş Değeri

Mevcut düğümün nitelikli adı. Örneğin, **Name** **<bk:book>** öğesi için **bk:book** olur.

## Açıklamalar



Dönen ad, düğümün [XmlReader::get_NodeType](../get_nodetype/) değerine bağlıdır. Aşağıdaki düğüm tipleri listelenen değerleri döndürür. Diğer tüm düğüm tipleri boş bir dize döndürür. 

| Düğüm türü | Ad |
| --- | --- |
| `[Attribute](../../../system/attribute/)`| Özniteliğin adı. |
| `DocumentType`| Belge türünün adı. |
| `Element`| Etiket adı. |
| `EntityReference`| Referans verilen varlığın adı. |
| `ProcessingInstruction`| İşlem talimatının hedefi. |
| [XmlDeclaration](../../xmldeclaration/)| Literal dize `xml`. |


## Ayrıca Bakınız

* Sınıf [String](../../../system/string/)
* Sınıf [XmlReader](../)
* Ad alanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)