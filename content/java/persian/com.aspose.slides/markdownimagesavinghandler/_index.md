---
title: MarkdownSaveOptions.MarkdownImageSavingHandler
second_title: Aspose.Slides for Java API Reference
description: Represents the markdown image saving handler of ImageSavingDelegate.ImageSavingDelegate event.
type: docs
url: /fa/com.aspose.slides/markdownsaveoptions.markdownimagesavinghandler/
---```
public static interface MarkdownSaveOptions.MarkdownImageSavingHandler
```

نمایانگر هندلر ذخیره‌سازی تصویر مارک‌داون مربوط به رویداد #ImageSavingDelegate.ImageSavingDelegate است.
## متدها

| متد | توضیح |
| --- | --- |
| [invoke(IImage image, int format, String[] link)](#invoke-com.aspose.slides.IImage-int-java.lang.String---) | برای هر تصویر غیر-SVG (bitmap یا متافایل) هنگام خروجی‌گیری Markdown فراخوانی می‌شود. |
### invoke(IImage image, int format, String[] link) {#invoke-com.aspose.slides.IImage-int-java.lang.String---}
```
public abstract boolean invoke(IImage image, int format, String[] link)
```

برای هر تصویر غیر-SVG (bitmap یا متافایل) هنگام خروجی‌گیری Markdown فراخوانی می‌شود. برای استفاده از لینک مشخص شده **true** بازگردانده شود و برای اعمال منطق ذخیره‌سازی پیش‌فرض **false** بازگردانده شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | تصویر صادر شونده (bitmap یا متافایل). |
| format | int | قالب تصویر. |
| link | java.lang.String[] | لینک Markdown که هنگام بازگرداندن **true** استفاده می‌شود. |

**بازگشت:**
boolean