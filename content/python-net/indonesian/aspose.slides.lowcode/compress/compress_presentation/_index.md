---
title: compress_presentation method
second_title: Aspose.Slides untuk Python via .NET API Referensi
description: 
type: docs
url: /id/aspose.slides.lowcode/compress/compress_presentation/
weight: 30
---
## compress_presentation(presentation) {#presentation}
Mengurangi ukuran presentasi dengan menerapkan semua langkah kompresi yang tersedia:
            
* Menghapus slide master yang tidak terpakai **Aspose.Slides.LowCode.Compress.RemoveUnusedMasterSlides(Aspose.Slide**.
* Menghapus slide tata letak yang tidak terpakai **Aspose.Slides.LowCode.Compress.RemoveUnusedLayoutSlides(Aspose.Slide**.
* Menyimpan hanya glif yang sebenarnya digunakan dalam font yang disematkan **Aspose.Slides.LowCode.Compress.CompressEmbeddedFonts(Aspose.Slide**.
* Mengurangi resolusi gambar menjadi 150 DPI dan menghapus area gambar yang dipangkas **Aspose.Slides.LowCode.Compress.CompressImages(Aspose.Slides.IPresentation,Aspose.Slides.Expor**.


```python
@staticmethod
def compress_presentation(presentation):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| presentation | [`Presentation`](/slides/python-net/id/aspose.slides/presentation) | Presentasi yang akan dikompresi. |

### Catatan

Untuk menyesuaikan kompresi, misalnya menggunakan resolusi gambar yang berbeda atau melewati sebuah langkah, panggil metode yang tercantum di atas secara individual sebagai ganti yang ini. Area gambar yang dipangkas dihapus secara permanen dan tidak dapat dipulihkan di PowerPoint.

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `presentation` is `None`. |



### Lihat Juga
* kelas [`Compress`](/slides/python-net/id/aspose.slides.lowcode/compress)
* kelas [`Presentation`](/slides/python-net/id/aspose.slides/presentation)
* modul [`aspose.slides.lowcode`](/slides/python-net/id/aspose.slides.lowcode)
* library [`Aspose.Slides`](/slides/python-net)