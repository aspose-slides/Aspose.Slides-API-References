---
title: MarkdownSaveOptions.MarkdownSvgImageSavingHandler
second_title: Aspose.Slides for Android via Java API Reference
description: يمثل معالج حفظ صور SVG في تنسيق markdown لحدث SvgImageSavingDelegate.SvgImageSavingDelegate.
type: docs
url: /ar/com.aspose.slides/markdownsaveoptions.markdownsvgimagesavinghandler/
---```
public static interface MarkdownSaveOptions.MarkdownSvgImageSavingHandler
```

يمثل معالج حفظ صور SVG في تنسيق markdown لحدث SvgImageSavingDelegate.SvgImageSavingDelegate.

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [invoke(ISvgImage svgImage, String[] link)](#invoke-com.aspose.slides.ISvgImage-java.lang.String---) | يتم استدعاؤها لكل صورة SVG أثناء تصدير Markdown. |
### invoke(ISvgImage svgImage, String[] link) {#invoke-com.aspose.slides.ISvgImage-java.lang.String---}
```
public abstract boolean invoke(ISvgImage svgImage, String[] link)
```

يتم استدعاؤها لكل صورة SVG أثناء تصدير Markdown. إرجاع true لاستخدام الرابط المحدد، أو false لتطبيق منطق الحفظ الافتراضي.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | صورة SVG التي يتم تصديرها. |
| link | java.lang.String[] | رابط Markdown لاستخدامه عند إرجاع true. |

**القيمة المرجعة:**
boolean