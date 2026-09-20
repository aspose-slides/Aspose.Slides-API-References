---
title: LoadingStreamBehavior enumeration
second_title: Aspose.Slides untuk Python via .NET Referensi API
description: 
type: docs
url: /id/aspose.slides/loadingstreambehavior/
---
## LoadingStreamBehavior enumerasi

Objek **io.RawIOBase** yang diteruskan ke suatu metode dianggap sebagai Binary Large Object (BLOB) (lihat deskripsi [`IBlobManagementOptions`](/slides/python-net/id/aspose.slides/iblobmanagementoptions)). Nilai-nilai enumerasi ini mengidentifikasi bagaimana **io.RawIOBase** harus diperlakukan ketika diteruskan ke metode. Bergantung pada persyaratan, keputusan yang berbeda dapat dibuat untuk memberikan perilaku yang paling efisien.

Tipe LoadingStreamBehavior mengekspos anggota-anggota berikut:

## Bidang

| Bidang | Deskripsi |
| :- | :- |
| READ_STREAM_AND_RELEASE | Aliran akan dibaca sampai akhir dan kemudian dilepaskan - yaitu akan dijamin bahwa aliran ini <br/> tidak akan digunakan oleh [`IPresentation`](/slides/python-net/id/aspose.slides/ipresentation) instansi di masa depan. Itu dapat ditutup oleh kode klien <br/> atau digunakan dengan cara lain. |
| KEEP_LOCKED | Aliran akan dikunci di dalam objek [`IPresentation`](/slides/python-net/id/aspose.slides/ipresentation), yaitu kepemilikan aliran <br/> akan dipindahkan. Objek [`IPresentation`](/slides/python-net/id/aspose.slides/ipresentation) akan bertanggung jawab untuk <br/> membersihkan aliran dengan benar ketika objek ini dibuang sendiri. <br/> Perilaku ini sangat berguna ketika Anda perlu menyerialkan file BLOB besar (seperti video atau audio besar - lihat deskripsi [`IBlobManagementOptions`](/slides/python-net/id/aspose.slides/iblobmanagementoptions)) dan ingin mencegah pemuatan <br/> file ini ke memori atau masalah kinerja lainnya. Anda dapat langsung membuka **System.IO.FileStream** <br/> untuk file ini dan meneruskannya ke suatu metode, memilih [`LoadingStreamBehavior.KEEP_LOCKED`](/slides/python-net/id/aspose.slides/loadingstreambehavior/KEEP_LOCKED) LoadingStreamBehavior. |

### Lihat Juga
* kelas [`IBlobManagementOptions`](/slides/python-net/id/aspose.slides/iblobmanagementoptions)
* kelas [`IPresentation`](/slides/python-net/id/aspose.slides/ipresentation)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)