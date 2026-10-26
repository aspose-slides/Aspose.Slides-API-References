---
title: MarkdownSaveOptions.MarkdownSvgImageSavingHandler
second_title: Aspose.Slides برای Android از طریق مستندات API
description: نمایانگر پردازشگر ذخیره‌سازی تصویر SVG در قالب markdown رویداد \#SvgImageSavingDelegate.SvgImageSavingDelegate است.
type: docs
url: /fa/com.aspose.slides/markdownsaveoptions.markdownsvgimagesavinghandler/
---```
public static interface MarkdownSaveOptions.MarkdownSvgImageSavingHandler
```

نمایانگر پردازشگر ذخیره‌سازی تصویر SVG در قالب markdown رویداد \#SvgImageSavingDelegate.SvgImageSavingDelegate است.
## متدها

| متد | توضیح |
| --- | --- |
| [invoke(ISvgImage svgImage, String[] link)](#invoke-com.aspose.slides.ISvgImage-java.lang.String---) | Invoked for each SVG image during Markdown export. |
### invoke(ISvgImage svgImage, String[] link) {#invoke-com.aspose.slides.ISvgImage-java.lang.String---}
```
public abstract boolean invoke(ISvgImage svgImage, String[] link)
```

برای هر تصویر SVG هنگام صادرات Markdown فراخوانی می‌شود. برای استفاده از لینک مشخص‌شده true را برگردانید، یا برای اعمال منطق ذخیره‌سازی پیش‌فرض false را برگردانید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | تصویر SVG که در حال صادرات است. |
| link | java.lang.String[] | لینک Markdown که هنگام برگرداندن true استفاده می‌شود. |

**بازگشت:**
boolean