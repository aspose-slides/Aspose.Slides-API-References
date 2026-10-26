---
title: GetUrl()
second_title: Aspose.Slides برای C++ API مرجع
description: "یک URL به یک شیء خارجی برمی‌گرداند. این متد همیشه وقتی ILinkEmbedController::GetObjectStoringLocation مقدار LinkEmbedDecision::Link را برمی‌گرداند فراخوانی می‌شود و ممکن است زمانی که ILinkEmbedController::GetObjectStoringLocation مقدار LinkEmbedDecision::Embed را برمی‌گرداند فراخوانی شود اما جاسازی غیرممکن است. می‌تواند برای همان شناسه شیء چندین بار فراخوانی شود."
type: docs
weight: 14
url: /fa/aspose.slides.export/ilinkembedcontroller/geturl/
---
## ILinkEmbedController::GetUrl(int32_t, int32_t) متد

یک URL به یک شیء خارجی برمی‌گرداند. این متد همیشه وقتی [ILinkEmbedController::GetObjectStoringLocation](../getobjectstoringlocation/) مقدار [LinkEmbedDecision::Link](../../linkembeddecision/) را برمی‌گرداند صدا زده می‌شود و ممکن است زمانی که [ILinkEmbedController::GetObjectStoringLocation](../getobjectstoringlocation/) مقدار [LinkEmbedDecision::Embed](../../linkembeddecision/) را برمی‌گرداند صدا زده شود اما جاسازی غیرممکن است. می‌تواند برای همان شناسه شیء چندین بار صدا زده شود.

```cpp
virtual System::String Aspose::Slides::Export::ILinkEmbedController::GetUrl(int32_t id, int32_t referrer)=0
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| id | **int32_t** | شناسهٔ شیء. این شناسه برای کل عملیات منحصربه‌فرد است. |
| referrer | **int32_t** | شناسهٔ شیء ارجاع‌دهنده یا 0، اگر شیء توسط سند ریشه ارجاع داده شود. ممکن است برای تولید لینک نسبی استفاده شود. |

### مقدار بازگشت

URL شیء خارجی یا null اگر این شیء باید نادیده گرفته شود.

## مراجع

* کلاس [String](../../../system/string/)
* کلاس [ILinkEmbedController](../)
* فضای‌نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)