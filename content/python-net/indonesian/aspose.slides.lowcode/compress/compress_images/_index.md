---
title: compress_images method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.lowcode/compress/compress_images/
weight: 20
---
## compress_images(presentation, resolution) {#ipresentation-asposeslidesexportpicturescompression}
Mengurangi resolusi gambar dalam presentasi dan menghapus area yang dipotong,
            mirip dengan "Compress Pictures" PowerPoint yang diterapkan pada semua gambar.
            Gambar pada slide, slide tata letak, dan slide master diproses, termasuk gambar di dalam bentuk grup
            dan isian gambar pada bentuk.

```python
@staticmethod
def compress_images(presentation, resolution):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| presentation | [`IPresentation`](/slides/python-net/id/aspose.slides/ipresentation) | Presentasi yang akan diproses. |
| resolution | [`PicturesCompression`](/slides/python-net/id/aspose.slides.export/picturescompression) | Resolusi target relatif terhadap ukuran saat setiap gambar ditampilkan.<br/><br/>            [`PicturesCompression.DOCUMENT_RESOLUTION`](/slides/python-net/id/aspose.slides.export/picturescompression/DOCUMENT_RESOLUTION) membiarkan gambar tidak berubah. |

### Keterangan

Gambar yang sudah berada pada atau di bawah resolusi target dibiarkan tidak berubah; gambar tidak pernah ditingkatkan skalanya.

Tidak diproses: latar belakang slide, isian sel tabel, diagram, SmartArt, gambar GIF (untuk mempertahankan animasi),
            gambar SVG dan metafile (EMF/WMF).

Area yang dipotong dihapus secara permanen dan tidak dapat dipulihkan di PowerPoint.

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `presentation` adalah `None`. |

### Lihat Juga
* kelas [`Compress`](/slides/python-net/id/aspose.slides.lowcode/compress)
* kelas [`IPresentation`](/slides/python-net/id/aspose.slides/ipresentation)
* enumerasi [`PicturesCompression`](/slides/python-net/id/aspose.slides.export/picturescompression)
* modul [`aspose.slides.lowcode`](/slides/python-net/id/aspose.slides.lowcode)
* perpustakaan [`Aspose.Slides`](/slides/python-net)