---
title: remove method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/icommentcollection/remove/
weight: 60
---
## remove(self, comment) {#icomment}
Belirtilen yorumun bir koleksiyondaki ilk görünümünü kaldırır.


```python
def remove(self, comment):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| comment | [`IComment`](/slides/python-net/tr/aspose.slides/icomment) | Bir koleksiyondan kaldırılacak yorum. |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Yorum `None` olduğunda |
| [`PptxEditException`](/slides/python-net/tr/aspose.slides/pptxeditexception) | Yorum zaten kaldırılmışsa ortaya çıkar. |



### Diğer
* sınıf [`IComment`](/slides/python-net/tr/aspose.slides/icomment)
* sınıf [`ICommentCollection`](/slides/python-net/tr/aspose.slides/icommentcollection)
* sınıf [`PptxEditException`](/slides/python-net/tr/aspose.slides/pptxeditexception)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)