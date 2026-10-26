---
title: get_Name()
second_title: Aspose.Slides için C++ API Referansı
description: Geçerli düğümün nitelikli adını döndürür.
type: docs
weight: 14
url: /tr/system.xml/xmlnodereader/get_name/
---
## XmlNodeReader::get_Name() metodu


Geçerli düğümün nitelikli adını döndürür.

```cpp
String System::Xml::XmlNodeReader::get_Name() override
```


### Dönüş Değeri

Geçerli düğümün nitelikli adı. Örneğin, **Name** **bk:book** elemanı **<bk:book>** için **bk:book** olur.
## Açıklamalar



[XmlNodeReader::get_NodeType](../get_nodetype/) değerine bağlı olarak döndürülen ad. Aşağıdaki düğüm türleri listelenen değerleri döndürür. Diğer tüm düğüm türleri boş bir dize döndürür. 

| Düğüm Türü | İsim |
| --- | --- |
| [Attribute](../../../system/attribute/)| Özelliğin adı. |
| DocumentType| Belge türünün adı. |
| Element| Etiket adı. |
| EntityReference| Referans verilen varlığın adı. |
| ProcessingInstruction| İşlem yönergesinin hedefi. |
| [XmlDeclaration](../../xmldeclaration/)| Literal dize `xml`. |


## Ayrıca Bakınız

* Sınıf [String](../../../system/string/)
* Sınıf [XmlNodeReader](../)
* Ad Alanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)