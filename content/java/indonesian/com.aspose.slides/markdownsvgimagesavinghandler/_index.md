---
title: MarkdownSaveOptions.MarkdownSvgImageSavingHandler
second_title: Aspose.Slides for Java API Reference
description: Mewakili handler penyimpanan gambar SVG markdown dari SvgImageSavingDelegate.SvgImageSavingDelegate event.
type: docs
url: /id/com.aspose.slides/markdownsaveoptions.markdownsvgimagesavinghandler/
---```
public static interface MarkdownSaveOptions.MarkdownSvgImageSavingHandler
```

Mewakili handler penyimpanan gambar SVG markdown dari #SvgImageSavingDelegate.SvgImageSavingDelegate event.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [invoke(ISvgImage svgImage, String[] link)](#invoke-com.aspose.slides.ISvgImage-java.lang.String---) | Dipanggil untuk setiap gambar SVG selama ekspor Markdown. |
### invoke(ISvgImage svgImage, String[] link) {#invoke-com.aspose.slides.ISvgImage-java.lang.String---}
```
public abstract boolean invoke(ISvgImage svgImage, String[] link)
```

Dipanggil untuk setiap gambar SVG selama ekspor Markdown. Kembalikan true untuk menggunakan tautan yang ditentukan, atau false untuk menerapkan logika penyimpanan default.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | Gambar SVG yang sedang diekspor. |
| link | java.lang.String[] | Tautan Markdown yang digunakan ketika mengembalikan true. |

**Mengembalikan:**
boolean