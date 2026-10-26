---
title: HandleRepeatedSpaces
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan bagaimana karakter spasi reguler yang berulang harus diproses selama ekspor Markdown.
type: docs
weight: 937
url: /id/aspose.slides.export/handlerepeatedspaces/
---
## HandleRepeatedSpaces enum

Menentukan bagaimana karakter spasi reguler yang berulang harus diproses selama ekspor Markdown.

```cpp
enum class HandleRepeatedSpaces
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| None | 0 | Semua spasi dipertahankan sebagai karakter spasi reguler tanpa perubahan apa pun. Tidak ada transformasi yang diterapkan, dan spasi berurutan ganda diekspor apa adanya. |
| AlternateSpacesToNbsp | 1 | Mengonversi urutan dua atau lebih spasi reguler berurutan dengan bergantian antara karakter spasi reguler dan entitas spasi tidak terputus (**&nbsp;**). Spasi pertama selalu dipertahankan sebagai spasi reguler. |
| MultipleSpacesToNbsp | 2 | Mengonversi urutan dua atau lebih spasi reguler berurutan dengan mempertahankan spasi pertama sebagai karakter spasi reguler dan mengganti semua spasi berikutnya dengan entitas spasi tidak terputus (**&nbsp;**). |

## Lihat Juga

* Ruang Nama [Aspose::Slides::Export](../)
* Perpustakaan [Aspose.Slides](../../)