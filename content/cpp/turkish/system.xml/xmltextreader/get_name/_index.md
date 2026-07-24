---
title: get_Name()
second_title: Aspose.Slides for C++ API Referansı
description: Geçerli düğümün nitelikli adını döndürür.
type: docs
weight: 14
url: /tr/system.xml/xmltextreader/get_name/
---
## XmlTextReader::get_Name() yöntemi

Geçerli düğümün nitelikli adını döndürür.

```cpp
String System::Xml::XmlTextReader::get_Name() override
```

### Dönüş Değeri

Geçerli düğümün nitelikli adı. Örneğin, **Name**, **<bk:book>** öğesi için **bk:book** olur.

## Açıklamalar

Dönen ad, düğümün [XmlTextReader::get_NodeType](../get_nodetype/) değerine bağlıdır. Aşağıdaki düğüm tipleri listelenen değerleri döndürür. Diğer tüm düğüm tipleri boş bir dize döndürür.

| Düğüm Türü | Ad |
| --- | --- |
| [Attribute](../../../system/attribute/)| Özniteliğin adı. |
| DocumentType| Belge türünün adı. |
| Element| Etiket adı. |
| EntityReference| Referans verilen varlığın adı. |
| ProcessingInstruction| İşleme talimatının hedefi. |
| [XmlDeclaration](../../xmldeclaration/)| Düz metin dizesi `xml`. |

## Ayrıca Bakınız

* Sınıf [String](../../../system/string/)
* Sınıf [XmlTextReader](../)
* İsim Alanı [System::Xml](../../)
* Library [Aspose.Slides](../../../)