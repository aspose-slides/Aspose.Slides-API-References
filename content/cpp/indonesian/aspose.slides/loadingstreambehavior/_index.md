---
title: LoadingStreamBehavior
second_title: Referensi API Aspose.Slides untuk C++
description: "System::IO::Stream yang diteruskan ke sebuah metode dianggap sebagai Binary Large Object (BLOB) (lihat deskripsi IBlobManagementOptions). Nilai-nilai enumerasi ini mengidentifikasi bagaimana System::IO::Stream harus diperlakukan ketika diteruskan ke metode. Bergantung pada persyaratan, keputusan yang berbeda dapat dibuat untuk menyediakan perilaku yang paling efisien."
type: docs
weight: 6735
url: /id/aspose.slides/loadingstreambehavior/
---
## LoadingStreamBehavior enum

The [System::IO::Stream](../../system.io/stream/) yang diteruskan ke sebuah metode dianggap sebagai Binary Large Object (BLOB) (lihat deskripsi [IBlobManagementOptions](../iblobmanagementoptions/)). Nilai-nilai enumerasi ini mengidentifikasi bagaimana [System::IO::Stream](../../system.io/stream/) harus diperlakukan ketika diteruskan ke metode. Bergantung pada persyaratan, keputusan yang berbeda dapat dibuat untuk menyediakan perilaku yang paling efisien.

```cpp
enum class LoadingStreamBehavior
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| ReadStreamAndRelease | 0 | Aliran akan dibaca sampai akhir dan kemudian dibebaskan - yaitu dijamin bahwa aliran ini tidak akan digunakan oleh instance [IPresentation](../ipresentation/) di masa mendatang. Aliran dapat ditutup oleh kode klien atau digunakan dengan cara lain apa pun. |
| KeepLocked | 1 | Aliran akan dikunci di dalam objek [IPresentation](../ipresentation/), yaitu kepemilikan aliran akan dipindahkan. Objek [IPresentation](../ipresentation/) akan bertanggung jawab untuk secara benar membuang aliran ketika objek ini dibuang sendiri. Perilaku ini sangat berguna ketika Anda perlu menyerialkan file BLOB yang besar (seperti video atau audio besar - lihat deskripsi [IBlobManagementOptions](../iblobmanagementoptions/)) dan ingin mencegah memuat file ini ke memori atau masalah kinerja lainnya. Anda dapat cukup membuka [System::IO::FileStream](../../system.io/filestream/) untuk file ini dan meneruskannya ke sebuah metode, memilih [LoadingStreamBehavior::KeepLocked](./) LoadingStreamBehavior. |

## Lihat Juga

* Ruang nama [Aspose::Slides](../)
* Perpustakaan [Aspose.Slides](../../)