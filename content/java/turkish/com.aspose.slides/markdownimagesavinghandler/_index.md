---
title: MarkdownSaveOptions.MarkdownImageSavingHandler
second_title: Aspose.Slides for Java API Referansı
description: ImageSavingDelegate.ImageSavingDelegate olayının markdown resim kaydetme işleyicisini temsil eder.
type: docs
url: /tr/com.aspose.slides/markdownsaveoptions.markdownimagesavinghandler/
---```
public static interface MarkdownSaveOptions.MarkdownImageSavingHandler
```

ImageSavingDelegate.ImageSavingDelegate olayının markdown resim kaydetme işleyicisini temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [invoke(IImage image, int format, String[] link)](#invoke-com.aspose.slides.IImage-int-java.lang.String---) | Markdown dışa aktarımı sırasında her SVG olmayan resim (bitmap veya metafile) için çağrılır. |
### invoke(IImage image, int format, String[] link) {#invoke-com.aspose.slides.IImage-int-java.lang.String---}
```
public abstract boolean invoke(IImage image, int format, String[] link)
```

Markdown dışa aktarımı sırasında her SVG olmayan resim (bitmap veya metafile) için çağrılır. Belirtilen bağlantıyı kullanmak için true, varsayılan kaydetme mantığını uygulamak için false döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | Dışa aktarılan resim (bitmap veya metafile). |
| format | int | Resim biçimi. |
| link | java.lang.String[] | True döndürüldüğünde kullanılacak Markdown bağlantısı. |

**Döndürür:**
boolean