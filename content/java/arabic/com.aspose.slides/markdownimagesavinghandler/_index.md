---
title: MarkdownSaveOptions.MarkdownImageSavingHandler
second_title: Aspose.Slides لـ Java مرجع API
description: يمثل معالج حفظ صور markdown لحدث ImageSavingDelegate.ImageSavingDelegate.
type: docs
url: /ar/com.aspose.slides/markdownsaveoptions.markdownimagesavinghandler/
---```
public static interface MarkdownSaveOptions.MarkdownImageSavingHandler
```

يمثل معالج حفظ صور markdown لحدث \#ImageSavingDelegate.ImageSavingDelegate.

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [invoke(IImage image, int format, String[] link)](#invoke-com.aspose.slides.IImage-int-java.lang.String---) | Invoked for each non-SVG image (bitmap or metafile) during Markdown export. |
### invoke(IImage image, int format, String[] link) {#invoke-com.aspose.slides.IImage-int-java.lang.String---}
```
public abstract boolean invoke(IImage image, int format, String[] link)
```

يتم استدعاؤه لكل صورة غير SVG (bitmap أو metafile) أثناء تصدير Markdown. إرجاع true لاستخدام الرابط المحدد، أو false لتطبيق منطق الحفظ الافتراضي.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | الصورة التي يتم تصديرها (bitmap أو metafile). |
| format | int | صيغة الصورة. |
| link | java.lang.String[] | رابط Markdown لاستخدامه عند إرجاع true. |

**القيمة المرجعة:**
boolean