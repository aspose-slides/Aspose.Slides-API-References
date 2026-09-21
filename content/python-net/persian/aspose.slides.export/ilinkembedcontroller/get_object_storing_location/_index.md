---
title: get_object_storing_location method
second_title: Aspose.Slides برای پایتون از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides.export/ilinkembedcontroller/get_object_storing_location/
weight: 10
---
## get_object_storing_location(self, id, entity_data, semantic_name, content_type, recomended_extension) {#int-bytes-str-str-str}
مشخص می‌کند که شی باید در کجا ذخیره شود.
این متد برای هر شناسهٔ شی یک بار فراخوانی می‌شود.
تضمین نمی‌شود که دو شی با داده‌های یکسان، semanticName و contentType وجود نداشته باشند اما دارای شناسهٔ متفاوت باشند.

### بازگشت
تصمیم

```python
def get_object_storing_location(self, id, entity_data, semantic_name, content_type, recomended_extension):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| id | **int** | شناسهٔ شی. این شناسه برای تمام عملیات ذخیره‌سازی یکتا است. |
| entity_data | **bytes** | دادهٔ باینری شی. این پارامتر می‌تواند None باشد، اگر دادهٔ باینری شی هنوز تولید نشده باشد. |
| semantic_name | **str** | متنی کوتاه که معنای شی را توصیف می‌کند. کنترلر ممکن است از این به‌عنوان بخشی از نام شی خارجی استفاده کند، اما اطمینان از یکتایی نام‌ها و داشتن فقط کاراکترهای مجاز بر عهدهٔ دیسپچر است. |
| content_type | **str** | نوع MIME شی. |
| recomended_extension | **str** | پسوند نام فایل که برای این نوع MIME توصیه می‌شود. |

### مطالب مرتبط
* کلاس [`ILinkEmbedController`](/slides/python-net/fa/aspose.slides.export/ilinkembedcontroller)
* enumeration [`LinkEmbedDecision`](/slides/python-net/fa/aspose.slides.export/linkembeddecision)
* ماژول [`aspose.slides.export`](/slides/python-net/fa/aspose.slides.export)
* کتابخانه [`Aspose.Slides`](/slides/python-net)