---
title: MoveToContent()
second_title: Aspose.Slides for C++ API Referansı
description: "Geçerli düğümün içerik (boşluk olmayan metin, CDATA, Element, EndElement, EntityReference veya EndEntity) düğümü olup olmadığını denetler. Düğüm bir içerik düğümü değilse, okuyucu bir sonraki içerik düğümüne ya da dosyanın sonuna kadar ilerler. Aşağıdaki türdeki düğümleri atlar: ProcessingInstruction, DocumentType, Comment, Whitespace veya SignificantWhitespace."
type: docs
weight: 833
url: /tr/system.xml/xmlreader/movetocontent/
---
## XmlReader::MoveToContent() metodu


Geçerli düğümün içerik (boşluk olmayan metin, **CDATA**, **Element**, **EndElement**, **EntityReference** veya **EndEntity**) düğümü olup olmadığını denetler. Düğüm bir içerik düğümü değilse, okuyucu bir sonraki içerik düğümüne ya da dosyanın sonuna kadar ilerler. Aşağıdaki türdeki düğümleri atlar: **ProcessingInstruction**, **DocumentType**, **Comment**, **Whitespace** veya **SignificantWhitespace**.

```cpp
virtual XmlNodeType System::Xml::XmlReader::MoveToContent()
```


### Dönüş Değeri

Yöntem tarafından bulunan geçerli düğümün [XmlReader::get_NodeType](../get_nodetype/) değeri ya da okuyucu giriş akışının sonuna ulaşmışsa [XmlNodeType::None](../../xmlnodetype/).

## İlgili Bağlantılar

* Enum [XmlNodeType](../../xmlnodetype/)
* Sınıf [XmlReader](../)
* Ad alanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)