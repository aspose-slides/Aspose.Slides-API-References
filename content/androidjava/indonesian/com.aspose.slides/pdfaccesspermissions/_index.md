---
title: PdfAccessPermissions
second_title: Aspose.Slides untuk Android via Referensi API Java
description: Berisi satu set flag yang menentukan izin akses apa yang harus diberikan ketika dokumen dibuka dengan akses pengguna.
type: docs
url: /id/com.aspose.slides/pdfaccesspermissions/
---
**Warisan:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PdfAccessPermissions extends System.Enum
```

Berisi satu set flag yang menentukan izin akses apa yang harus diberikan ketika dokumen dibuka dengan akses pengguna.
## Bidang

| Field | Description |
| --- | --- |
| [None](#None) | Menentukan bahwa pengguna tidak memiliki izin akses. |
| [PrintDocument](#PrintDocument) | Menentukan apakah pengguna boleh mencetak dokumen (mungkin tidak pada tingkat kualitas tertinggi, tergantung apakah bit [HighQualityPrint](../../com.aspose.slides/pdfaccesspermissions\#HighQualityPrint) juga diatur). |
| [ModifyContent](#ModifyContent) | Menentukan apakah pengguna dapat memodifikasi isi dokumen melalui operasi selain yang dikendalikan oleh bit [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields), [FillExistingFields](../../com.aspose.slides/pdfaccesspermissions\#FillExistingFields), [AssembleDocument](../../com.aspose.slides/pdfaccesspermissions\#AssembleDocument). |
| [CopyTextAndGraphics](#CopyTextAndGraphics) | Menentukan apakah pengguna dapat menyalin atau mengekstrak teks dan grafik dari dokumen melalui operasi selain yang dikendalikan oleh bit [ExtractTextAndGraphics](../../com.aspose.slides/pdfaccesspermissions\#ExtractTextAndGraphics). |
| [AddOrModifyFields](#AddOrModifyFields) | Menentukan apakah pengguna dapat menambahkan atau memodifikasi anotasi teks, mengisi bidang formulir interaktif, dan, jika bit [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) juga diatur, membuat atau memodifikasi bidang formulir interaktif (termasuk bidang tanda tangan). |
| [FillExistingFields](#FillExistingFields) | Menentukan apakah pengguna dapat mengisi bidang formulir interaktif yang ada (termasuk bidang tanda tangan), bahkan jika bit [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields) tidak diatur. |
| [ExtractTextAndGraphics](#ExtractTextAndGraphics) | Menentukan apakah pengguna dapat mengekstrak teks dan grafik untuk mendukung aksesibilitas bagi pengguna dengan disabilitas atau untuk tujuan lain. |
| [AssembleDocument](#AssembleDocument) | Menentukan apakah pengguna dapat menyusun dokumen (menyisipkan, memutar, atau menghapus halaman serta membuat penanda buku atau gambar mini), bahkan jika bit [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) tidak diatur. |
| [HighQualityPrint](#HighQualityPrint) | Menentukan apakah pengguna dapat mencetak dokumen ke sebuah representasi dari mana salinan digital yang akurat dari konten PDF dapat dihasilkan. |
### None {#None}
```
public static final int None
```

Menentukan bahwa pengguna tidak memiliki izin akses.

### PrintDocument {#PrintDocument}
```
public static final int PrintDocument
```

Menentukan apakah pengguna boleh mencetak dokumen (mungkin tidak pada tingkat kualitas tertinggi, tergantung apakah bit [HighQualityPrint](../../com.aspose.slides/pdfaccesspermissions\#HighQualityPrint) juga diatur).

### ModifyContent {#ModifyContent}
```
public static final int ModifyContent
```

Menentukan apakah pengguna dapat memodifikasi isi dokumen melalui operasi selain yang dikendalikan oleh bit [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields), [FillExistingFields](../../com.aspose.slides/pdfaccesspermissions\#FillExistingFields), [AssembleDocument](../../com.aspose.slides/pdfaccesspermissions\#AssembleDocument).

### CopyTextAndGraphics {#CopyTextAndGraphics}
```
public static final int CopyTextAndGraphics
```

Menentukan apakah pengguna dapat menyalin atau mengekstrak teks dan grafik dari dokumen melalui operasi selain yang dikendalikan oleh bit [ExtractTextAndGraphics](../../com.aspose.slides/pdfaccesspermissions\#ExtractTextAndGraphics).

### AddOrModifyFields {#AddOrModifyFields}
```
public static final int AddOrModifyFields
```

Menentukan apakah pengguna dapat menambahkan atau memodifikasi anotasi teks, mengisi bidang formulir interaktif, dan, jika bit [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) juga diatur, membuat atau memodifikasi bidang formulir interaktif (termasuk bidang tanda tangan).

### FillExistingFields {#FillExistingFields}
```
public static final int FillExistingFields
```

Menentukan apakah pengguna dapat mengisi bidang formulir interaktif yang ada (termasuk bidang tanda tangan), bahkan jika bit [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields) tidak diatur.

### ExtractTextAndGraphics {#ExtractTextAndGraphics}
```
public static final int ExtractTextAndGraphics
```

Menentukan apakah pengguna dapat mengekstrak teks dan grafik untuk mendukung aksesibilitas bagi pengguna dengan disabilitas atau untuk tujuan lain.

### AssembleDocument {#AssembleDocument}
```
public static final int AssembleDocument
```

Menentukan apakah pengguna dapat menyusun dokumen (menyisipkan, memutar, atau menghapus halaman serta membuat penanda buku atau gambar mini), bahkan jika bit [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) tidak diatur.

### HighQualityPrint {#HighQualityPrint}
```
public static final int HighQualityPrint
```

Menentukan apakah pengguna dapat mencetak dokumen ke sebuah representasi dari mana salinan digital yang akurat dari konten PDF dapat dihasilkan. Ketika bit ini tidak diatur (dan bit [PrintDocument](../../com.aspose.slides/pdfaccesspermissions\#PrintDocument) diatur), pencetakan dibatasi pada representasi tingkat rendah dari tampilan, mungkin dengan kualitas yang menurun.