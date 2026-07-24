---
title: get_ParentNode()
second_title: Aspose.Slides için C++ API Referansı
description: Bu düğümün ebeveynini döndürür (ebeveynleri olabilen düğümler için).
type: docs
weight: 53
url: /tr/system.xml/xmlnode/get_parentnode/
---
## XmlNode::get_ParentNode() metodu

Bu düğümün ebeveynini döndürür (ebeveynleri olabilen düğümler için).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNode::get_ParentNode() final
```

### Dönen Değer

Geçerli düğümün ebeveyni olan [XmlNode](../).

## Açıklama

Bir düğüm yeni oluşturulmuş ve henüz ağaç yapısına eklenmemişse ya da ağaçtan kaldırılmışsa, ebeveyn **nullptr** olur. Diğer tüm düğümler için döndürülen değer, düğümün [XmlNode::get_NodeType](../get_nodetype/) değerine bağlıdır. Aşağıdaki tablo, **get_NodeType** metodunun olası dönüş değerlerini açıklar.

| NodeType | ParentNode'un Dönen Değeri |
| --- | --- |
| [Attribute](../../../system/attribute/), Document, DocumentFragment, Entity, Notation | `nullptr` döndürür; bu düğümlerin ebeveyni yoktur. |
| CDATA | CDATA bölümünü içeren öğeyi veya varlık referansını döndürür. |
| Comment | Yorumu içeren öğeyi, varlık referansını, belge tipini veya belgeyi döndürür. |
| DocumentType | Belge düğümünü döndürür. |
| Element | Ögenin ebeveyn düğümünü döndürür. Eğer öğe ağaçta kök düğüm ise, ebeveyn belge düğümüdür. |
| EntityReference | Varlık referansını içeren öğeyi, özniteliği veya varlık referansını döndürür. |
| ProcessingInstruction | İşlem talimatını içeren belgeyi, öğeyi, belge tipini veya varlık referansını döndürür. |
| [Text](../../../system.text/) | Metin düğümünü içeren ebeveyn öğeyi, özniteliği veya varlık referansını döndürür. |

## Diğer Bağlantılar

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [XmlNode](../)
* Ad alanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)