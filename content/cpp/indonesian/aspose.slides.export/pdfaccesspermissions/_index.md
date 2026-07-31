---
title: PdfAccessPermissions
second_title: Referensi API Aspose.Slides untuk C++
description: Berisi satu set flag yang menentukan izin akses mana yang harus diberikan ketika dokumen dibuka dengan akses pengguna.
type: docs
weight: 989
url: /id/aspose.slides.export/pdfaccesspermissions/
---
## PdfAccessPermissions enum

Berisi satu set flag yang menentukan izin akses mana yang harus diberikan ketika dokumen dibuka dengan akses pengguna.

```cpp
enum class PdfAccessPermissions
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| None | 0 | Menentukan bahwa pengguna tidak memiliki izin akses. |
| PrintDocument | 4 | Menentukan apakah pengguna dapat mencetak dokumen (mungkin tidak pada tingkat kualitas tertinggi, tergantung apakah bit [PdfAccessPermissions::HighQualityPrint](./) juga disetel). |
| ModifyContent | 8 | Menentukan apakah pengguna dapat memodifikasi isi dokumen dengan operasi selain yang dikendalikan oleh bit [PdfAccessPermissions::AddOrModifyFields](./), [PdfAccessPermissions::FillExistingFields](./), [PdfAccessPermissions::AssembleDocument](./). |
| CopyTextAndGraphics | 16 | Menentukan apakah pengguna dapat menyalin atau mengekstrak teks dan grafik dari dokumen dengan operasi selain yang dikendalikan oleh bit [PdfAccessPermissions::ExtractTextAndGraphics](./). |
| AddOrModifyFields | 32 | Menentukan apakah pengguna dapat menambahkan atau memodifikasi anotasi teks, mengisi bidang formulir interaktif, dan, jika bit [PdfAccessPermissions::ModifyContent](./) juga disetel, membuat atau memodifikasi bidang formulir interaktif (termasuk bidang tanda tangan). |
| FillExistingFields | 256 | Menentukan apakah pengguna dapat mengisi bidang formulir interaktif yang ada (termasuk bidang tanda tangan), bahkan jika bit [PdfAccessPermissions::AddOrModifyFields](./) tidak disetel. |
| ExtractTextAndGraphics | 512 | Menentukan apakah pengguna dapat mengekstrak teks dan grafik untuk mendukung aksesibilitas bagi pengguna dengan disabilitas atau untuk tujuan lain. |
| AssembleDocument | 1024 | Menentukan apakah pengguna dapat menyusun dokumen (menyisipkan, memutar, atau menghapus halaman serta membuat penanda atau gambar mini), bahkan jika bit [PdfAccessPermissions::ModifyContent](./) tidak disetel. |
| HighQualityPrint | 2048 | Menentukan apakah pengguna dapat mencetak dokumen ke representasi yang dapat menghasilkan salinan digital yang setia dari konten PDF. Ketika bit ini tidak disetel (dan bit [PdfAccessPermissions::PrintDocument](./) disetel), pencetakan dibatasi pada representasi level rendah dari tampilan, mungkin dengan kualitas yang menurun. |

## Lihat Juga

* Ruang nama [Aspose::Slides::Export](../)
* Perpustakaan [Aspose.Slides](../../)