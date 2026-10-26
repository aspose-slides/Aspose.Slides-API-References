---
title: get_Value()
second_title: Aspose.Slides için C++ API Referansı
description: Geçerli düğümün metin değerini döndürür.
type: docs
weight: 79
url: /tr/system.xml/xmlvalidatingreader/get_value/
---
## XmlValidatingReader::get_Value() yöntemi

Geçerli düğümün metin değerini döndürür.

```cpp
String System::Xml::XmlValidatingReader::get_Value() override
```

### Dönen Değer

Dönen değer, düğümün XmlValidatingReader::NodeType özelliğine bağlıdır.

## Açıklamalar

Aşağıdaki tablo, döndürülecek bir değere sahip düğüm türlerini listeler. Diğer tüm düğüm türleri [String::Empty](../../../system/string/empty/) döndürür.

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

## İlgili

* Sınıf [String](../../../system/string/)
* Sınıf [XmlValidatingReader](../)
* Ad alanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)