---
title: MarkdownSaveOptions.MarkdownImageSavingHandler
second_title: Aspose.Slides لنظام Android عبر مرجع API Java
description: يمثل معالج حفظ صورة markdown لحدث ImageSavingDelegate.ImageSavingDelegate.
type: docs
url: /ar/com.aspose.slides/markdownsaveoptions.markdownimagesavinghandler/
---```
public static interface MarkdownSaveOptions.MarkdownImageSavingHandler
```

يمثل معالج حفظ صورة markdown لحدث #ImageSavingDelegate.ImageSavingDelegate.

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [invoke(IImage image, int format, String[] link)](#invoke-com.aspose.slides.IImage-int-java.lang.String---) | يتم استدعاؤه لكل صورة غير SVG (bitmap أو metafile) أثناء تصدير Markdown. |
### invoke(IImage image, int format, String[] link) {#invoke-com.aspose.slides.IImage-int-java.lang.String---}
```
public abstract boolean invoke(IImage image, int format, String[] link)
```

يتم استدعاؤه لكل صورة غير SVG (bitmap أو metafile) أثناء تصدير Markdown. إرجاع true لاستخدام الرابط المحدد، أو false لتطبيق منطق الحفظ الافتراضي.

**المُعاملات:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | الصورة التي يتم تصديرها (bitmap أو metafile). |
| format | int | تنسيق الصورة. |
| link | java.lang.String[] | رابط Markdown لاستخدامه عند إرجاع true. |

**القيمة المرجعة:**
boolean