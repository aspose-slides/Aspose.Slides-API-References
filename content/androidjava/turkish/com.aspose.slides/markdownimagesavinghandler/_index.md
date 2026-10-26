---
title: MarkdownSaveOptions.MarkdownImageSavingHandler
second_title: Aspose.Slides for Android via Java API Reference
description: Markdown görüntü kaydetme işleyicisini temsil eder ImageSavingDelegate.ImageSavingDelegate olayında.
type: docs
url: /tr/com.aspose.slides/markdownsaveoptions.markdownimagesavinghandler/
---```
public static interface MarkdownSaveOptions.MarkdownImageSavingHandler
```

Markdown görüntü kaydetme işleyicisini temsil eder \#ImageSavingDelegate.ImageSavingDelegate olayında.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [invoke(IImage image, int format, String[] link)](#invoke-com.aspose.slides.IImage-int-java.lang.String---) | Markdown dışa aktarımı sırasında her SVG olmayan görüntü (bitmap veya metafile) için çağrılır. |
### invoke(IImage image, int format, String[] link) {#invoke-com.aspose.slides.IImage-int-java.lang.String---}
```
public abstract boolean invoke(IImage image, int format, String[] link)
```

Markdown dışa aktarımı sırasında her SVG olmayan görüntü (bitmap veya metafile) için çağrılır. Belirtilen bağlantıyı kullanmak için true döndürün, varsayılan kaydetme mantığını uygulamak için false döndürün.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | Dışa aktarılan görüntü (bitmap veya metafile). |
| format | int | Görüntü formatı. |
| link | java.lang.String[] | True döndürüldüğünde kullanılacak Markdown bağlantısı. |

**Döndürür:**
boolean