---
title: MarkdownSaveOptions.MarkdownSvgImageSavingHandler
second_title: Aspose.Slides لـ Java مرجع API
description: يمثل معالج حفظ صورة SVG في تنسيق markdown لحدث SvgImageSavingDelegate.SvgImageSavingDelegate.
type: docs
url: /ar/com.aspose.slides/markdownsaveoptions.markdownsvgimagesavinghandler/
---```
public static interface MarkdownSaveOptions.MarkdownSvgImageSavingHandler
```

يمثل معالج حفظ صورة SVG في تنسيق markdown لحدث SvgImageSavingDelegate.SvgImageSavingDelegate.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [invoke(ISvgImage svgImage, String[] link)](#invoke-com.aspose.slides.ISvgImage-java.lang.String---) | Invoked for each SVG image during Markdown export. |
### invoke(ISvgImage svgImage, String[] link) {#invoke-com.aspose.slides.ISvgImage-java.lang.String---}
```
public abstract boolean invoke(ISvgImage svgImage, String[] link)
```

يتم استدعاؤه لكل صورة SVG أثناء تصدير Markdown. أعد true لاستخدام الرابط المحدد، أو false لتطبيق منطق الحفظ الافتراضي.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | صورة SVG التي يتم تصديرها. |
| link | java.lang.String[] | رابط Markdown لاستخدامه عند إرجاع true. |

**القيمة المرجعة:**
boolean