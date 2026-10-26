---
title: get_Name()
second_title: Aspose.Slides for C++ API Referansı
description: Geçerli düğümün nitelikli adını döndürür.
type: docs
weight: 14
url: /tr/system.xml/xmlvalidatingreader/get_name/
---
## XmlValidatingReader::get_Name() yöntemi

Geçerli düğümün nitelikli adını döndürür.

```cpp
String System::Xml::XmlValidatingReader::get_Name() override
```

### Dönüş Değeri

Geçerli düğümün nitelikli adı. Örneğin, **Name** element **<bk:book>** için **bk:book** şeklindedir.

## Açıklamalar

Ad, XmlValidatingReader::NodeType değerine bağlı olarak döndürülür. Aşağıdaki düğüm türleri belirtilen değerleri döndürür. Diğer tüm düğüm türleri boş bir dize döndürür.

| Düğüm Türü | Ad |
| --- | --- |
| [Attribute](../../../system/attribute/)| Özniteliğin adı. |
| DocumentType| Belge türü adı. |
| Element| Etiket adı. |
| EntityReference| Referans verilen varlığın adı. |
| ProcessingInstruction| İşlem talimatının hedefi. |
| [XmlDeclaration](../../xmldeclaration/)| Gerçek dize `xml`. |

## See Also

* Sınıf [String](../../../system/string/)
* Sınıf [XmlValidatingReader](../)
* İsim Uzayı [System::Xml](../../)
* Library [Aspose.Slides](../../../)