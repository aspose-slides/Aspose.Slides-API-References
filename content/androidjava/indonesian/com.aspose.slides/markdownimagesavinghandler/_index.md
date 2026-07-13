---
title: MarkdownSaveOptions.MarkdownImageSavingHandler
second_title: Aspose.Slides for Android via Java API Reference
description: Mewakili handler penyimpanan gambar markdown dari event ImageSavingDelegate.ImageSavingDelegate.
type: docs
url: /id/com.aspose.slides/markdownsaveoptions.markdownimagesavinghandler/
---```
public static interface MarkdownSaveOptions.MarkdownImageSavingHandler
```

Mewakili handler penyimpanan gambar markdown dari \#ImageSavingDelegate.ImageSavingDelegate event.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [invoke(IImage image, int format, String[] link)](#invoke-com.aspose.slides.IImage-int-java.lang.String---) | Dipanggil untuk setiap gambar non-SVG (bitmap atau metafile) selama ekspor Markdown. |
### invoke(IImage image, int format, String[] link) {#invoke-com.aspose.slides.IImage-int-java.lang.String---}
```
public abstract boolean invoke(IImage image, int format, String[] link)
```

Dipanggil untuk setiap gambar non-SVG (bitmap atau metafile) selama ekspor Markdown. Kembalikan true untuk menggunakan tautan yang ditentukan, atau false untuk menerapkan logika penyimpanan default.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | Gambar yang diekspor (bitmap atau metafile). |
| format | int | Format gambar. |
| link | java.lang.String[] | Tautan Markdown yang digunakan ketika mengembalikan true. |

**Mengembalikan:**
boolean