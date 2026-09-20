---
title: PdfAccessPermissions enumeration
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.export/pdfaccesspermissions/
---
## PdfAccessPermissions enumeration

Berisi sekumpulan flag yang menentukan izin akses mana yang harus diberikan saat dokumen dibuka dengan akses pengguna.

Tipe PdfAccessPermissions mengekspos anggota-anggota berikut:

## Bidang

| Bidang | Deskripsi |
| :- | :- |
| NONE | Menentukan bahwa pengguna tidak memiliki izin akses. |
| PRINT_DOCUMENT | Menentukan apakah pengguna dapat mencetak dokumen (mungkin tidak pada tingkat kualitas tertinggi, tergantung pada <br/>            apakah bit [`PdfAccessPermissions.HIGH_QUALITY_PRINT`](/slides/python-net/id/aspose.slides.export/pdfaccesspermissions/HIGH_QUALITY_PRINT) juga disetel). |
| MODIFY_CONTENT | Menentukan apakah pengguna dapat memodifikasi isi dokumen melalui operasi selain yang dikendalikan<br/>            oleh bit [`PdfAccessPermissions.ADD_OR_MODIFY_FIELDS`](/slides/python-net/id/aspose.slides.export/pdfaccesspermissions/ADD_OR_MODIFY_FIELDS), [`PdfAccessPermissions.FILL_EXISTING_FIELDS`](/slides/python-net/id/aspose.slides.export/pdfaccesspermissions/FILL_EXISTING_FIELDS), [`PdfAccessPermissions.ASSEMBLE_DOCUMENT`](/slides/python-net/id/aspose.slides.export/pdfaccesspermissions/ASSEMBLE_DOCUMENT). |
| COPY_TEXT_AND_GRAPHICS | Menentukan apakah pengguna dapat menyalin atau mengekstrak teks dan grafik dari dokumen melalui operasi <br/>            selain yang dikendalikan oleh bit [`PdfAccessPermissions.EXTRACT_TEXT_AND_GRAPHICS`](/slides/python-net/id/aspose.slides.export/pdfaccesspermissions/EXTRACT_TEXT_AND_GRAPHICS). |
| ADD_OR_MODIFY_FIELDS | Menentukan apakah pengguna dapat menambah atau memodifikasi anotasi teks, mengisi bidang formulir interaktif, dan, jika bit<br/>            [`PdfAccessPermissions.MODIFY_CONTENT`](/slides/python-net/id/aspose.slides.export/pdfaccesspermissions/MODIFY_CONTENT) juga disetel, membuat atau memodifikasi bidang formulir interaktif (termasuk bidang tanda tangan <br/>            ). |
| FILL_EXISTING_FIELDS | Menentukan apakah pengguna dapat mengisi bidang formulir interaktif yang sudah ada (termasuk bidang tanda tangan), bahkan jika<br/>            bit [`PdfAccessPermissions.ADD_OR_MODIFY_FIELDS`](/slides/python-net/id/aspose.slides.export/pdfaccesspermissions/ADD_OR_MODIFY_FIELDS) tidak disetel. |
| EXTRACT_TEXT_AND_GRAPHICS | Menentukan apakah pengguna dapat mengekstrak teks dan grafik untuk mendukung aksesibilitas bagi pengguna dengan disabilitas<br/>            atau untuk tujuan lain. |
| ASSEMBLE_DOCUMENT | Menentukan apakah pengguna dapat menyusun dokumen (menyisipkan, memutar, atau menghapus halaman serta membuat bookmark atau<br/>            gambar mini), bahkan jika bit [`PdfAccessPermissions.MODIFY_CONTENT`](/slides/python-net/id/aspose.slides.export/pdfaccesspermissions/MODIFY_CONTENT) tidak disetel. |
| HIGH_QUALITY_PRINT | Menentukan apakah pengguna dapat mencetak dokumen ke representasi yang memungkinkan salinan digital yang setia dari<br/>            konten PDF dapat dihasilkan. Ketika bit ini tidak disetel (dan bit [`PdfAccessPermissions.PRINT_DOCUMENT`](/slides/python-net/id/aspose.slides.export/pdfaccesspermissions/PRINT_DOCUMENT) disetel),<br/>            pencetakan dibatasi pada representasi tingkat rendah dari tampilan, mungkin dengan kualitas yang menurun. |

### Lihat Juga
* modul [`aspose.slides.export`](/slides/python-net/id/aspose.slides.export)
* perpustakaan [`Aspose.Slides`](/slides/python-net)