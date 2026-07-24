---
title: get_Value()
second_title: Aspose.Slides for C++ API Referansı
description: Türetilmiş bir sınıfta geçersiz kılındığında, geçerli düğümün metin değerini alır.
type: docs
weight: 92
url: /tr/system.xml/xmlreader/get_value/
---
## XmlReader::get_Value() metodu

Türetilmiş bir sınıfta geçersiz kılındığında, geçerli düğümün metin değerini alır.

```cpp
virtual String System::Xml::XmlReader::get_Value()=0
```

### Dönüş Değeri

Dönen değer, düğümün [XmlReader::get_NodeType](../get_nodetype/) değerine bağlıdır.

## Açıklamalar

Aşağıdaki tablo, geri döndürülecek bir değere sahip düğüm türlerini listeler. Diğer tüm düğüm türleri [String::Empty](../../../system/string/empty/) döndürür.

| Düğüm türü | Değer |
| --- | --- |
| `[Attribute](../../../system/attribute/)`| Özelliğin değeri. |
| `CDATA`| CDATA bölümünün içeriği. |
| `Comment`| Yorumun içeriği. |
| `DocumentType`| İç alt küme. |
| `ProcessingInstruction`| Hedef dışındaki tüm içerik. |
| `SignificantWhitespace`| Karışık içerik modelinde işaretleme arasındaki boşluk. |
| `[Text](../../../system.text/)`| Metin düğümünün içeriği. |
| `Whitespace`| İşaretleme arasındaki boşluk. |
| [XmlDeclaration](../../xmldeclaration/)| Deklarasyonun içeriği. |

## Diğer Bağlantılar

* Sınıf [String](../../../system/string/)
* Sınıf [XmlReader](../)
* İsim Alanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)