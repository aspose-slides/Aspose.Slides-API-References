---
title: MarkdownSaveOptions.MarkdownImageSavingHandler
second_title: Aspose.Slides for Android via Java API Reference
description: Represents the markdown image saving handler of ImageSavingDelegate.ImageSavingDelegate event.
type: docs
url: /fa/com.aspose.slides/markdownsaveoptions.markdownimagesavinghandler/
---```
public static interface MarkdownSaveOptions.MarkdownImageSavingHandler
```

نمایندهٔ ذخیره‌سازی تصویر markdown برای رویداد \#ImageSavingDelegate.ImageSavingDelegate است.
## متدها

| متد | توضیح |
| --- | --- |
| [invoke(IImage image, int format, String[] link)](#invoke-com.aspose.slides.IImage-int-java.lang.String---) | برای هر تصویر غیر SVG (bitmap یا metafile) در هنگام صادرات Markdown فراخوانی می‌شود. |
### invoke(IImage image, int format, String[] link) {#invoke-com.aspose.slides.IImage-int-java.lang.String---}
```
public abstract boolean invoke(IImage image, int format, String[] link)
```

برای هر تصویر غیر SVG (bitmap یا metafile) در هنگام صادرات Markdown فراخوانی می‌شود. برای استفاده از لینک مشخص شده true برگردانید، یا برای اعمال منطق ذخیره‌سازی پیش‌فرض false برگردانید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | تصویری که در حال صادرات است (bitmap یا metafile). |
| format | int | فرمت تصویر. |
| link | java.lang.String[] | لینک Markdown که هنگام برگرداندن true استفاده می‌شود. |

**مقدار بازگشتی:**
boolean