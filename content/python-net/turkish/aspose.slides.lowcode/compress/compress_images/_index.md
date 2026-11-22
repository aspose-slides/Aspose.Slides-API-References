---
title: compress_images method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.lowcode/compress/compress_images/
weight: 20
---
## compress_images(presentation, resolution) {#ipresentation-asposeslidesexportpicturescompression}
Sunumdaki resimlerin çözünürlüğünü düşürür ve kırpılmış alanlarını siler,
            PowerPoint'in tüm resimlere uygulanan "Compress Pictures" özelliğine benzer.
            Slaytlar, düzen slaytları ve ana slaytlardaki resimler işlenir, grup şekilleri içindeki resimler
            ve şekillerin resim doldurmaları dahil.

```python
@staticmethod
def compress_images(presentation, resolution):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| presentation | [`IPresentation`](/slides/python-net/tr/aspose.slides/ipresentation) | İşlenecek sunum. |
| resolution | [`PicturesCompression`](/slides/python-net/tr/aspose.slides.export/picturescompression) | Her bir resmin gösterildiği boyuta göre hedef çözünürlük.<br/><br/>            [`PicturesCompression.DOCUMENT_RESOLUTION`](/slides/python-net/tr/aspose.slides.export/picturescompression/DOCUMENT_RESOLUTION) resimleri değiştirmez. |

### Açıklamalar

Hedef çözünürlüğe zaten eşit ya da daha düşük olan resimler değiştirilmez; resimler asla yükseltilmez.

İşlenmeyenler: slayt arka planları, tablo hücre dolguları, grafikler, SmartArt, GIF görüntüleri (animasyonu korumak için),
            SVG ve metafile (EMF/WMF) görüntüler.

Kırpılmış alanlar kalıcı olarak silinir ve PowerPoint'te geri getirilemez.

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `presentation` is `None`. |

### Diğer Bağlantılar
* sınıf [`Compress`](/slides/python-net/tr/aspose.slides.lowcode/compress)
* sınıf [`IPresentation`](/slides/python-net/tr/aspose.slides/ipresentation)
* enumerasyon [`PicturesCompression`](/slides/python-net/tr/aspose.slides.export/picturescompression)
* modül [`aspose.slides.lowcode`](/slides/python-net/tr/aspose.slides.lowcode)
* kütüphane [`Aspose.Slides`](/slides/python-net)