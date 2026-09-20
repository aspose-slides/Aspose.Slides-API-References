---
title: PresentationLockingBehavior enumeration
second_title: Aspose.Slides untuk Python via .NET API Reference
description: 
type: docs
url: /id/aspose.slides/presentationlockingbehavior/
---
## PresentationLockingBehavior enumerasi

Represents the behavior regarding treating the [`IPresentation`](/slides/python-net/id/aspose.slides/ipresentation) source (file or 
            **io.RawIOBase**) while loading and working with an instance of [`IPresentation`](/slides/python-net/id/aspose.slides/ipresentation).

The PresentationLockingBehavior type exposes the following members:

## Bidang

| Bidang | Deskripsi |
| :- | :- |
| LOAD_AND_RELEASE | Sumber akan dikunci hanya selama eksekusi konstruktor [`IPresentation`](/slides/python-net/id/aspose.slides/ipresentation).<br/>            Jika [`IBlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/id/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed) disetel ke false, semua BLOB akan dimuat ke memori. Jika tidak, metode lain seperti file temporer mungkin akan digunakan. Perilaku ini lebih lambat daripada [`PresentationLockingBehavior.KEEP_LOCKED`](/slides/python-net/id/aspose.slides/presentationlockingbehavior/KEEP_LOCKED), dan jika memungkinkan untuk menyerahkan kepemilikan sumber ke [`IPresentation`](/slides/python-net/id/aspose.slides/ipresentation), disarankan untuk menggunakan [`PresentationLockingBehavior.KEEP_LOCKED`](/slides/python-net/id/aspose.slides/presentationlockingbehavior/KEEP_LOCKED). |
| KEEP_LOCKED | Sumber akan dikunci selama masa hidup penuh instance [`IPresentation`](/slides/python-net/id/aspose.slides/ipresentation), sampai itu dibuang.<br/>            [`IBlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/id/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed) harus disetel ke true untuk menggunakan perilaku ini, jika tidak, pengecualian akan dilempar. Perilaku ini disarankan, lebih cepat dan menggunakan memori lebih sedikit dibandingkan [`PresentationLockingBehavior.LOAD_AND_RELEASE`](/slides/python-net/id/aspose.slides/presentationlockingbehavior/LOAD_AND_RELEASE). |


### Catatan

Sumber adalah parameter yang diberikan ke konstruktor [`IPresentation`](/slides/python-net/id/aspose.slides/ipresentation). Pada contoh di bawah, sumber adalah file "pres.pptx":

Untuk contoh ini, sumber (file "pres.pptx") akan dikunci selama masa hidup instance [`IPresentation`](/slides/python-net/id/aspose.slides/ipresentation), yaitu tidak dapat diubah atau dihapus oleh proses lain.


### Lihat Juga
* kelas [`IPresentation`](/slides/python-net/id/aspose.slides/ipresentation)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)