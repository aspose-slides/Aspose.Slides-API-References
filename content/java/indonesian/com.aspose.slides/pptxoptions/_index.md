---
title: PptxOptions
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili opsi untuk menyimpan presentasi OpenXml PPTX PPSX POTX PPTM PPSM POTM.
type: docs
url: /id/com.aspose.slides/pptxoptions/
---
**Pewarisan:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IPptxOptions](../../com.aspose.slides/ipptxoptions), java.lang.Cloneable
```
public final class PptxOptions extends SaveOptions implements IPptxOptions, Cloneable
```

Mewakili opsi untuk menyimpan presentasi OpenXml (PPTX, PPSX, POTX, PPTM, PPSM, POTM).
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PptxOptions()](#PptxOptions--) | Creates new instance of PptxOptions |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getConformance()](#getConformance--) | Specifies the conformance class to which the Presentation document conforms. |
| [setConformance(int value)](#setConformance-int-) | Specifies the conformance class to which the Presentation document conforms. |
| [getZip64Mode()](#getZip64Mode--) | Specifies whether the ZIP64 format is used for the Presentation document. |
| [setZip64Mode(int value)](#setZip64Mode-int-) | Specifies whether the ZIP64 format is used for the Presentation document. |
| [getRefreshThumbnail()](#getRefreshThumbnail--) | Specifies whether the presentation thumbnail will be refreshed. |
| [setRefreshThumbnail(boolean value)](#setRefreshThumbnail-boolean-) | Specifies whether the presentation thumbnail will be refreshed. |
| [getCompressionLevel()](#getCompressionLevel--) | Specifies the compression level used when saving the presentation document. |
| [setCompressionLevel(int value)](#setCompressionLevel-int-) | Specifies the compression level used when saving the presentation document. |
### PptxOptions() {#PptxOptions--}
```
public PptxOptions()
```

Membuat instance baru dari PptxOptions

### getConformance() {#getConformance--}
```
public final int getConformance()
```

Menentukan kelas konformansi yang diikuti oleh dokumen Presentation. Nilai default adalah [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**Mengembalikan:**
int
### setConformance(int value) {#setConformance-int-}
```
public final void setConformance(int value)
```

Menentukan kelas konformansi yang diikuti oleh dokumen Presentation. Nilai default adalah [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getZip64Mode() {#getZip64Mode--}
```
public final int getZip64Mode()
```

Menentukan apakah format ZIP64 digunakan untuk dokumen Presentation. Nilai default adalah [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setZip64Mode(Zip64Mode.Always);
>      pres.save("demo-zip64.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Mengembalikan:**
int
### setZip64Mode(int value) {#setZip64Mode-int-}
```
public final void setZip64Mode(int value)
```

Menentukan apakah format ZIP64 digunakan untuk dokumen Presentation. Nilai default adalah [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setZip64Mode(Zip64Mode.Always);
>      pres.save("demo-zip64.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getRefreshThumbnail() {#getRefreshThumbnail--}
```
public final boolean getRefreshThumbnail()
```

Menentukan apakah thumbnail presentasi akan disegarkan. Baca/tulis boolean. Nilai default adalah **true**.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setRefreshThumbnail(false);
>      pres.save("result_with_old_thumbnail.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Ketika nilai opsi adalah **true**, thumbnail baru akan dihasilkan.

Ketika nilai opsi adalah **false**, thumbnail saat ini akan disimpan apa adanya.

**Mengembalikan:**
boolean
### setRefreshThumbnail(boolean value) {#setRefreshThumbnail-boolean-}
```
public final void setRefreshThumbnail(boolean value)
```

Menentukan apakah thumbnail presentasi akan disegarkan. Baca/tulis boolean. Nilai default adalah **true**.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setRefreshThumbnail(false);
>      pres.save("result_with_old_thumbnail.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Ketika nilai opsi adalah **true**, thumbnail baru akan dihasilkan.

Ketika nilai opsi adalah **false**, thumbnail saat ini akan disimpan apa adanya.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getCompressionLevel() {#getCompressionLevel--}
```
public final int getCompressionLevel()
```

Menentukan tingkat kompresi yang digunakan saat menyimpan dokumen presentasi. Nilai default adalah [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setCompressionLevel(CompressionLevel.Level8);
>      pres.save("demo-level8.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Level kompresi yang lebih tinggi menghasilkan file yang lebih kecil namun memerlukan waktu pemrosesan lebih lama. Rasio kompresi sebenarnya bergantung pada konten presentasi.

**Mengembalikan:**
int
### setCompressionLevel(int value) {#setCompressionLevel-int-}
```
public final void setCompressionLevel(int value)
```

Menentukan tingkat kompresi yang digunakan saat menyimpan dokumen presentasi. Nilai default adalah [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setCompressionLevel(CompressionLevel.Level8);
>      pres.save("demo-level8.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Level kompresi yang lebih tinggi menghasilkan file yang lebih kecil namun memerlukan waktu pemrosesan lebih lama. Rasio kompresi sebenarnya bergantung pada konten presentasi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |