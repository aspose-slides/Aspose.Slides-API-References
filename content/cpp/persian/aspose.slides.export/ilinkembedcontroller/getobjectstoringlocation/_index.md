---
title: GetObjectStoringLocation()
second_title: مستندات API Aspose.Slides برای C++
description: محل ذخیره‌سازی شی را تعیین می‌کند. این متد برای هر شناسه شی یک‌بار فراخوانی می‌شود. تضمینی وجود ندارد که دو شی با داده، semanticName و contentType یکسان اما با شناسه متفاوت وجود نداشته باشند.
type: docs
weight: 1
url: /fa/aspose.slides.export/ilinkembedcontroller/getobjectstoringlocation/
---
## ILinkEmbedController::GetObjectStoringLocation(int32_t, System::ArrayPtr\<uint8_t\>, System::String, System::String, System::String) متد

مکان ذخیره‌سازی شی را تعیین می‌کند. این متد برای هر شناسه‌شی یک‌بار فراخوانی می‌شود. تضمین نمی‌شود که دو شی با داده، semanticName و contentType یکسان اما با شناسه متفاوت وجود نداشته باشند.

```cpp
virtual LinkEmbedDecision Aspose::Slides::Export::ILinkEmbedController::GetObjectStoringLocation(int32_t id, System::ArrayPtr<uint8_t> entityData, System::String semanticName, System::String contentType, System::String recomendedExtension)=0
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| id | **int32_t** | شناسه شی. این شناسه برای تمام عملیات ذخیره‌سازی یکتا است. |
| entityData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | داده باینری شی. این پارامتر می‌تواند null باشد، اگر داده باینری شی هنوز تولید نشده باشد. |
| semanticName | [System::String](../../../system/string/) | متن کوتاهی که معنای شی را توصیف می‌کند. کنترل‌کننده ممکن است از این به عنوان بخشی از نام شی خارجی استفاده کند، اما اطمینان از یکتا بودن نام‌ها و داشتن تنها کاراکترهای مجاز بر عهده‌ی دیسپاچر است. |
| contentType | [System::String](../../../system/string/) | نوع MIME شی. |
| recomendedExtension | [System::String](../../../system/string/) | پسوند نام فایل که برای این نوع MIME توصیه می‌شود. |

### مقدار بازگشت

تصمیم

## موارد مرتبط

* شمارش [LinkEmbedDecision](../../linkembeddecision/)
* تایپ‌دِف [ArrayPtr](../../../system/arrayptr/)
* کلاس [String](../../../system/string/)
* کلاس [ILinkEmbedController](../)
* فضای‌نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)