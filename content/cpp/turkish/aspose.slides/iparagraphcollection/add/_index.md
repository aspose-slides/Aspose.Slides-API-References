---
title: Add()
second_title: Aspose.Slides C++ API Referansı için
description: Bir Paragraph'ı koleksiyonun sonuna ekler.
type: docs
weight: 27
url: /tr/aspose.slides/iparagraphcollection/add/
---
## IParagraphCollection::Add(System::SharedPtr\<IParagraph\>) metot

Koleksiyonun sonuna bir [Paragraph](../../paragraph/) ekler.

```cpp
virtual void Aspose::Slides::IParagraphCollection::Add(System::SharedPtr<IParagraph> value)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../iparagraph/)\> | Koleksiyonun sonuna eklenecek [Paragraph](../../paragraph/). |

## IParagraphCollection::Add(System::SharedPtr\<IParagraphCollection\>) metot

Koleksiyonun sonuna [ParagraphCollection](../../paragraphcollection/) içeriği ekler.

```cpp
virtual int32_t Aspose::Slides::IParagraphCollection::Add(System::SharedPtr<IParagraphCollection> value)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraphCollection](../)\> | Koleksiyonun sonuna eklenecek [ParagraphCollection](../../paragraphcollection/). |

### Dönüş Değeri

[Paragraph](../../paragraph/)'nin eklendiği dizin ya da eklenecek bir şey yoksa -1.

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IParagraph](../../iparagraph/)
* Sınıf [IParagraphCollection](../)
* Ad Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)