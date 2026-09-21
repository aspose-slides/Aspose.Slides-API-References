---
title: remove method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/icommentcollection/remove/
weight: 60
---
## remove(self, comment) {#icomment}
Removes the first occurrence of the specified comment in a collection.

```python
def remove(self, comment):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| comment | [`IComment`](/slides/python-net/fa/aspose.slides/icomment) | نظری که باید از یک مجموعه حذف شود. |

### استثناها

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | اگر comment برابر `None` باشد |
| [`PptxEditException`](/slides/python-net/fa/aspose.slides/pptxeditexception) | اگر comment قبلاً حذف شده باشد، پرتاب می‌شود. |

### ارجاع‌ها
* کلاس [`IComment`](/slides/python-net/fa/aspose.slides/icomment)
* کلاس [`ICommentCollection`](/slides/python-net/fa/aspose.slides/icommentcollection)
* کلاس [`PptxEditException`](/slides/python-net/fa/aspose.slides/pptxeditexception)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)