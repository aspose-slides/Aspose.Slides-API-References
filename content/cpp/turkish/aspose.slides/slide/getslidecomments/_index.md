---
title: GetSlideComments()
second_title: Aspose.Slides for C++ API Referansı
description: Belirli bir yazar tarafından eklenen tüm slayt yorumlarını döndürür.
type: docs
weight: 209
url: /tr/aspose.slides/slide/getslidecomments/
---
## Slide::GetSlideComments(System::SharedPtr\<ICommentAuthor\>) metodu

Belirli bir yazar tarafından eklenen tüm slayt yorumlarını döndürür.

```cpp
System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::Slide::GetSlideComments(System::SharedPtr<ICommentAuthor> author) override
```

### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| author | [System::SharedPtr](../../../system/sharedptr/)\<[ICommentAuthor](../../icommentauthor/)\> | Bulunacak yorumların yazarı veya tüm yorumları döndürmek için null. |

### Dönüş Değeri

[Comment](../../comment/) dizisi.

## İlgili

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IComment](../../icomment/)
* Sınıf [ICommentAuthor](../../icommentauthor/)
* Sınıf [Slide](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)