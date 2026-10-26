---
title: Convert.GetOutPathCallback
second_title: Aspose.Slides for Java API Reference
description: 
type: docs
url: /fa/com.aspose.slides/convert.getoutpathcallback/
---```
public static interface Convert.GetOutPathCallback
```
## متدها

| Method | Description |
| --- | --- |
| [invoke(Slide slide, int index)](#invoke-com.aspose.slides.Slide-int-) | کال‌بکی که برای هر [Slide](../../com.aspose.slides/slide) فراخوانی می‌شود، مسیر خروجی انتظار می‌رود برگردانده شود. |
### invoke(Slide slide, int index) {#invoke-com.aspose.slides.Slide-int-}
```
public abstract String invoke(Slide slide, int index)
```

کال‌بکی که برای هر [Slide](../../com.aspose.slides/slide) فراخوانی می‌شود، مسیر خروجی انتظار می‌رود برگردانده شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| slide | [Slide](../../com.aspose.slides/slide) | اسلاید جاری |
| index | int | اندیس اسلاید جاری |

**بازگشت:**
java.lang.String