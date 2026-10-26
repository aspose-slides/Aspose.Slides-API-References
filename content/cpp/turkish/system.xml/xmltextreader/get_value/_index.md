---
title: get_Value()
second_title: C++ için Aspose.Slides API Referansı
description: Geçerli düğümün metin değerini döndürür.
type: docs
weight: 79
url: /tr/system.xml/xmltextreader/get_value/
---
## XmlTextReader::get_Value() metodu

Geçerli düğümün metin değerini döndürür.

```cpp
String System::Xml::XmlTextReader::get_Value() override
```

### Dönüş Değeri

Dönen değer, düğümün [XmlTextReader::get_NodeType](../get_nodetype/) değerine bağlıdır.

## Açıklamalar

Aşağıdaki tablo, döndürülecek bir değere sahip düğüm türlerini listeler. Diğer tüm düğüm türleri [String::Empty](../../../system/string/empty/) döndürür. 

| Düğüm Türü | Değer |
| --- | --- |
| [Attribute](../../../system/attribute/)| Özelliğin değeri. |
| CDATA| CDATA bölümünün içeriği. |
| Comment| Yorumun içeriği. |
| DocumentType| Dahili alt küme. |
| ProcessingInstruction| Hedef hariç, tüm içerik. |
| SignificantWhitespace| Bir `xml:space='preserve'` kapsamı içindeki boşluk. |
| [Text](../../../system.text/)| Metin düğümünün içeriği. |
| Whitespace| Biçimleme arasındaki boşluk. |
| [XmlDeclaration](../../xmldeclaration/)| Deklarasyonun içeriği. |

## Ayrıca Bakınız

* Sınıf [String](../../../system/string/)
* Sınıf [XmlTextReader](../)
* Ad alanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)