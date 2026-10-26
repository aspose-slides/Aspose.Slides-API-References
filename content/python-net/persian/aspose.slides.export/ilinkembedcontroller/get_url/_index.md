---
title: get_url method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides.export/ilinkembedcontroller/get_url/
weight: 20
---
## get_url(self, id, referrer) {#int-int}
یک URL برای شیء خارجی برمی‌گرداند.
            این روش همیشه فراخوانی می‌شود اگر **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** مقدار [`LinkEmbedDecision.LINK`](/slides/python-net/fa/aspose.slides.export/linkembeddecision/LINK) را برگرداند و ممکن است فراخوانی شود اگر **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** مقدار [`LinkEmbedDecision.EMBED`](/slides/python-net/fa/aspose.slides.export/linkembeddecision/EMBED) را برگرداند اما جاسازی امکان‌پذیر نیست.
            می‌تواند برای همان شناسه شیء چندین بار فراخوانی شود.

### Returns
URL شیء خارجی یا None اگر این شیء باید نادیده گرفته شود.

```python
def get_url(self, id, referrer):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| id | **int** | شناسه شیء. این شناسه به صورت سراسری برای تمام عملیات ذخیره‌سازی یکتا است. |
| referrer | **int** | شناسهٔ شیء مرجع‌دهنده یا ۰، اگر شیء توسط سند ریشه ارجاع داده شود. ممکن است برای ایجاد لینک نسبی استفاده شود. |

### See Also
* کلاس [`ILinkEmbedController`](/slides/python-net/fa/aspose.slides.export/ilinkembedcontroller)
* ماژول [`aspose.slides.export`](/slides/python-net/fa/aspose.slides.export)
* کتابخانه [`Aspose.Slides`](/slides/python-net)