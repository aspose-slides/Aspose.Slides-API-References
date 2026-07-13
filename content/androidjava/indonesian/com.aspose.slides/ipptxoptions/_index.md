---
title: IPptxOptions
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Mewakili opsi untuk menyimpan presentasi OpenXml PPTX PPSX POTX PPTM PPSM POTM.
type: docs
url: /id/com.aspose.slides/ipptxoptions/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPptxOptions extends ISaveOptions
```

Mewakili opsi untuk menyimpan presentasi OpenXml (PPTX, PPSX, POTX, PPTM, PPSM, POTM).
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getConformance()](#getConformance--) | Menentukan kelas kepatuhan yang dipatuhi dokumen Presentation. |
| [setConformance(int value)](#setConformance-int-) | Menentukan kelas kepatuhan yang dipatuhi dokumen Presentation. |
| [getZip64Mode()](#getZip64Mode--) | Menentukan apakah format ZIP64 digunakan untuk dokumen Presentation. |
| [setZip64Mode(int value)](#setZip64Mode-int-) | Menentukan apakah format ZIP64 digunakan untuk dokumen Presentation. |
| [getRefreshThumbnail()](#getRefreshThumbnail--) | Menentukan apakah thumbnail presentasi akan diperbarui. |
| [setRefreshThumbnail(boolean value)](#setRefreshThumbnail-boolean-) | Menentukan apakah thumbnail presentasi akan diperbarui. |
| [getCompressionLevel()](#getCompressionLevel--) | Menentukan tingkat kompresi yang digunakan saat menyimpan dokumen presentasi. |
| [setCompressionLevel(int value)](#setCompressionLevel-int-) | Menentukan tingkat kompresi yang digunakan saat menyimpan dokumen presentasi. |
### getConformance() {#getConformance--}
```
public abstract int getConformance()
```


Menentukan kelas kepatuhan yang dipatuhi dokumen Presentation. Nilai default adalah [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**Mengembalikan:**
int
### setConformance(int value) {#setConformance-int-}
```
public abstract void setConformance(int value)
```


Menentukan kelas kepatuhan yang dipatuhi dokumen Presentation. Nilai default adalah [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getZip64Mode() {#getZip64Mode--}
```
public abstract int getZip64Mode()
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
public abstract void setZip64Mode(int value)
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
public abstract boolean getRefreshThumbnail()
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

Ketika nilai opsi adalah **true**, thumbnail baru akan dihasilkan.

Ketika nilai opsi adalah **false**, thumbnail saat ini akan disimpan apa adanya.

**Mengembalikan:**
boolean
### setRefreshThumbnail(boolean value) {#setRefreshThumbnail-boolean-}
```
public abstract void setRefreshThumbnail(boolean value)
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

Ketika nilai opsi adalah **true**, thumbnail baru akan dihasilkan.

Ketika nilai opsi adalah **false**, thumbnail saat ini akan disimpan apa adanya.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getCompressionLevel() {#getCompressionLevel--}
```
public abstract int getCompressionLevel()
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

Tingkat kompresi yang lebih tinggi menghasilkan file yang lebih kecil tetapi memerlukan waktu pemrosesan lebih lama. Rasio kompresi sebenarnya bergantung pada konten presentasi.

**Mengembalikan:**
int
### setCompressionLevel(int value) {#setCompressionLevel-int-}
```
public abstract void setCompressionLevel(int value)
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

Tingkat kompresi yang lebih tinggi menghasilkan file yang lebih kecil tetapi memerlukan waktu pemrosesan lebih lama. Rasio kompresi sebenarnya bergantung pada konten presentasi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |