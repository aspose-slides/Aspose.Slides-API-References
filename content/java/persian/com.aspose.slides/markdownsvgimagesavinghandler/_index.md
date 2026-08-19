---
title: MarkdownSaveOptions.MarkdownSvgImageSavingHandler
second_title: Aspose.Slides for Java API Reference
description: نشان‌دهندهٔ هندلر ذخیره‌سازی تصویر SVG در فرمت Markdown برای رویداد SvgImageSavingDelegate.SvgImageSavingDelegate است.
type: docs
url: /fa/com.aspose.slides/markdownsaveoptions.markdownsvgimagesavinghandler/
---```
public static interface MarkdownSaveOptions.MarkdownSvgImageSavingHandler
```

نشان‌دهندهٔ هندلر ذخیره‌سازی تصویر SVG در فرمت Markdown برای رویداد \#SvgImageSavingDelegate.SvgImageSavingDelegate است.
## متدها

| متد | توضیح |
| --- | --- |
| [invoke(ISvgImage svgImage, String[] link)](#invoke-com.aspose.slides.ISvgImage-java.lang.String---) | در هنگام خروجی‌گیری به فرمت Markdown برای هر تصویر SVG فراخوانی می‌شود. |
### invoke(ISvgImage svgImage, String[] link) {#invoke-com.aspose.slides.ISvgImage-java.lang.String---}
```
public abstract boolean invoke(ISvgImage svgImage, String[] link)
```

در هنگام خروجی‌گیری به فرمت Markdown برای هر تصویر SVG فراخوانی می‌شود. برای استفاده از لینک مشخص‌شده مقدار true را برگردانید، یا برای اعمال منطق ذخیره‌سازی پیش‌فرض مقدار false را برگردانید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | تصویر SVG که در حال خروجی‌گیری است. |
| link | java.lang.String[] | لینک Markdown که هنگام برگرداندن true استفاده می‌شود. |

**بازگشت:**
boolean