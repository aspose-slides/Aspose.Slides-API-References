---
title: get_Value()
second_title: Aspose.Slides for C++ API Referansı
description: Mevcut düğümün metin değerini döndürür.
type: docs
weight: 79
url: /tr/system.xml/xmlnodereader/get_value/
---
## XmlNodeReader::get_Value() metodu


Mevcut düğümün metin değerini döndürür.

```cpp
String System::Xml::XmlNodeReader::get_Value() override
```


### Dönüş Değeri

Döndürülen değer, düğümün [XmlNodeReader::get_NodeType](../get_nodetype/)'ine bağlıdır.

## Açıklamalar



Aşağıdaki tablo, geri döndürülecek bir değere sahip düğüm türlerini listeler. Diğer tüm düğüm tipleri [String::Empty](../../../system/string/empty/) döndürür. 

| Düğüm Türü | Değer |
| --- | --- |
| [Attribute](../../../system/attribute/)| Özniteliğin değeri. |
| CDATA| CDATA bölümünün içeriği. |
| Comment| Yorumun içeriği. |
| DocumentType| İç alt küme. |
| ProcessingInstruction| Hedef dışındaki tüm içerik. |
| SignificantWhitespace| Karışık içerik modelinde işaretleme arasındaki boşluk. |
| [Text](../../../system.text/)| Metin düğümünün içeriği. |
| Whitespace| İşaretleme arasındaki boşluk. |
| [XmlDeclaration](../../xmldeclaration/)| Deklarasyonun içeriği. |


## Ayrıca Bakınız

* Sınıf [String](../../../system/string/)
* Sınıf [XmlNodeReader](../)
* İsim uzayı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)