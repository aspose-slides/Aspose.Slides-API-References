---
title: Convert.GetOutPathCallback
second_title: Aspose.Slides for Android via Java API Reference
description: 
type: docs
url: /fa/com.aspose.slides/convert.getoutpathcallback/
---```
public static interface Convert.GetOutPathCallback
```
## روش‌ها

| Method | Description |
| --- | --- |
| [invoke(Slide slide, int index)](#invoke-com.aspose.slides.Slide-int-) | کال‌بکی که برای هر [Slide](../../com.aspose.slides/slide) فراخوانی می‌شود و مسیر خروجی مورد انتظار بازگردانده می‌شود. |
### invoke(Slide slide, int index) {#invoke-com.aspose.slides.Slide-int-}
```
public abstract String invoke(Slide slide, int index)
```

کال‌بکی که برای هر [Slide](../../com.aspose.slides/slide) فراخوانی می‌شود و مسیر خروجی مورد انتظار بازگردانده می‌شود.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| slide | [Slide](../../com.aspose.slides/slide) | اسلاید فعلی که در حال تکرار است |
| index | int | شاخص اسلاید فعلی |

**بازگشت:**
java.lang.String