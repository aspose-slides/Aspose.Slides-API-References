---
title: PptxOptions
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Mewakili opsi untuk menyimpan presentasi OpenXml PPTX PPSX POTX PPTM PPSM POTM.
type: docs
url: /id/com.aspose.slides/pptxoptions/
---
**Warisan:**
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
| [PptxOptions()](#PptxOptions--) | Membuat instance baru dari PptxOptions |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getConformance()](#getConformance--) | Menentukan kelas konformitas yang dipatuhi dokumen Presentation. |
| [setConformance(int value)](#setConformance-int-) | Menentukan kelas konformitas yang dipatuhi dokumen Presentation. |
| [getZip64Mode()](#getZip64Mode--) | Menentukan apakah format ZIP64 digunakan untuk dokumen Presentation. |
| [setZip64Mode(int value)](#setZip64Mode-int-) | Menentukan apakah format ZIP64 digunakan untuk dokumen Presentation. |
| [getRefreshThumbnail()](#getRefreshThumbnail--) | Menentukan apakah thumbnail presentasi akan diperbarui. |
| [setRefreshThumbnail(boolean value)](#setRefreshThumbnail-boolean-) | Menentukan apakah thumbnail presentasi akan diperbarui. |
| [getCompressionLevel()](#getCompressionLevel--) | Menentukan tingkat kompresi yang digunakan saat menyimpan dokumen presentasi. |
| [setCompressionLevel(int value)](#setCompressionLevel-int-) | Menentukan tingkat kompresi yang digunakan saat menyimpan dokumen presentasi. |
### PptxOptions() {#PptxOptions--}
```
public PptxOptions()
```


Membuat instance baru dari PptxOptions

### getConformance() {#getConformance--}
```
public final int getConformance()
```


Menentukan kelas konformitas yang dipatuhi dokumen Presentation. Nilai default adalah [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**Mengembalikan:**
int
### setConformance(int value) {#setConformance-int-}
```
public final void setConformance(int value)
```


Menentukan kelas konformitas yang dipatuhi dokumen Presentation. Nilai default adalah [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

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


Menentukan apakah thumbnail presentasi akan diperbarui. Boolean baca/tulis. Nilai default adalah **true**.

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

Ketika nilai opsi **true**, thumbnail baru akan dihasilkan.

Ketika nilai opsi **false**, thumbnail saat ini akan disimpan apa adanya.

**Mengembalikan:**
boolean
### setRefreshThumbnail(boolean value) {#setRefreshThumbnail-boolean-}
```
public final void setRefreshThumbnail(boolean value)
```


Menentukan apakah thumbnail presentasi akan diperbarui. Boolean baca/tulis. Nilai default adalah **true**.

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

Ketika nilai opsi **true**, thumbnail baru akan dihasilkan.

Ketika nilai opsi **false**, thumbnail saat ini akan disimpan apa adanya.

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

Tingkat kompresi yang lebih tinggi menghasilkan file yang lebih kecil tetapi membutuhkan waktu pemrosesan lebih lama. Rasio kompresi sebenarnya tergantung pada konten presentasi.

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

Tingkat kompresi yang lebih tinggi menghasilkan file yang lebih kecil tetapi membutuhkan waktu pemrosesan lebih lama. Rasio kompresi sebenarnya tergantung pada konten presentasi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |