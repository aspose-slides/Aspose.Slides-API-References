---
title: CopyPixelOperation
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan bagaimana warna sumber dalam operasi penyalinan piksel digabungkan dengan warna tujuan untuk menghasilkan warna akhir.
type: docs
weight: 391
url: /id/system.drawing/copypixeloperation/
---
## CopyPixelOperation enum

Menentukan bagaimana warna sumber dalam operasi menyalin piksel digabungkan dengan warna tujuan untuk menghasilkan warna akhir.

```cpp
enum class CopyPixelOperation
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| NoMirrorBitmap | n/a | Bitmap tidak dicerminkan. |
| Blackness | 66 | Wilayah tujuan diisi dengan menggunakan warna dengan indeks 0 di palet fisik. |
| NotSourceErase | 1114278 | Warna sumber dan tujuan di-OR, dan warna yang dihasilkan kemudian dibalik. |
| NotSourceCopy | 3342344 | Wilayah sumber dibalik dan kemudian disalin ke tujuan. |
| SourceErase | 4457256 | Warna terbalik dari wilayah tujuan di-AND dengan warna dari wilayah sumber. |
| DestinationInvert | 5570569 | Wilayah tujuan dibalik. |
| PatInvert | 5898313 | Warna kuas yang saat ini dipilih dalam konteks perangkat tujuan di-XOR dengan warna tujuan. |
| SourceInvert | 6684742 | Warna wilayah sumber dan tujuan di-XOR. |
| SourceAnd | 8913094 | Warna wilayah sumber dan tujuan di-AND. |
| MergePaint | 12255782 | Warna wilayah sumber yang terbalik di-OR dengan warna wilayah tujuan. |
| MergeCopy | 12583114 | Warna wilayah sumber di-AND dengan warna kuas yang dipilih dalam konteks perangkat tujuan. |
| SourceCopy | 13369376 | Wilayah sumber disalin langsung ke wilayah tujuan. |
| SourcePaint | 15597702 | Warna wilayah sumber dan tujuan di-OR. |
| PatCopy | 15728673 | Kuas yang saat ini dipilih dalam konteks perangkat tujuan disalin ke bitmap tujuan. |
| PatPaint | 16452105 | Warna kuas yang saat ini dipilih dalam konteks perangkat tujuan di-OR dengan warna wilayah sumber yang terbalik. Hasil operasi ini kemudian di-OR dengan warna wilayah tujuan. |
| Whiteness | 16711778 | Wilayah tujuan diisi dengan menggunakan warna dengan indeks 1 di palet fisik. |
| CaptureBlt | 1073741824 | [Windows](../../system.windows/) yang dilapisi di atas jendela aplikasi termasuk dalam gambar yang dihasilkan. |

## Lihat Juga

* Namespace [System::Drawing](../)
* Perpustakaan [Aspose.Slides](../../)