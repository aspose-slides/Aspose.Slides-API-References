---
title: MarkdownSaveOptions.MarkdownSvgImageSavingHandler
second_title: Aspose.Slides for Android via Java API Reference
description: Represents the markdown SVG image saving handler of SvgImageSavingDelegate.SvgImageSavingDelegate event.
type: docs
url: /tr/com.aspose.slides/markdownsaveoptions.markdownsvgimagesavinghandler/
---```
public static interface MarkdownSaveOptions.MarkdownSvgImageSavingHandler
```

SvgImageSavingDelegate.SvgImageSavingDelegate olayının markdown SVG görüntü kaydetme işleyicisini temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [invoke(ISvgImage svgImage, String[] link)](#invoke-com.aspose.slides.ISvgImage-java.lang.String---) | Invoked for each SVG image during Markdown export. |
### invoke(ISvgImage svgImage, String[] link) {#invoke-com.aspose.slides.ISvgImage-java.lang.String---}
```
public abstract boolean invoke(ISvgImage svgImage, String[] link)
```

Markdown dışa aktarma sırasında her SVG görüntü için çağrılır. Belirtilen bağlantıyı kullanmak için true, varsayılan kaydetme mantığını uygulamak için false döndürün.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | Dışa aktarılan SVG görüntüsü. |
| link | java.lang.String[] | true döndürüldüğünde kullanılacak Markdown bağlantısı. |

**Döndürür:**
boolean