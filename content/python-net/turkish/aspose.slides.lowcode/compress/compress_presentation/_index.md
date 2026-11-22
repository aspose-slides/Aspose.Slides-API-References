---
title: compress_presentation method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.lowcode/compress/compress_presentation/
weight: 30
---
## compress_presentation(presentation) {#presentation}
Bir sunumun boyutunu, mevcut tüm sıkıştırma adımlarını uygulayarak azaltır:
            
* Kullanılmayan ana slaytları kaldırır **Aspose.Slides.LowCode.Compress.RemoveUnusedMasterSlides(Aspose.Slide**.
* Kullanılmayan yerleşim slaytlarını kaldırır **Aspose.Slides.LowCode.Compress.RemoveUnusedLayoutSlides(Aspose.Slide**.
* Yerleşik yazı tiplerinde gerçekten kullanılan yalnızca glifleri tutar **Aspose.Slides.LowCode.Compress.CompressEmbeddedFonts(Aspose.Slide**.
* Resim çözünürlüğünü 150 DPI'ye düşürür ve kesilmiş resim alanlarını siler **Aspose.Slides.LowCode.Compress.CompressImages(Aspose.Slides.IPresentation,Aspose.Slides.Expor**.


```python
@staticmethod
def compress_presentation(presentation):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| presentation | [`Presentation`](/slides/python-net/tr/aspose.slides/presentation) | Sıkıştırılacak sunum. |

### Açıklamalar

Sıkıştırmayı özelleştirmek için, örneğin farklı bir resim çözünürlüğü kullanmak veya bir adımı atlamak istediğinizde,
            yukarıda listelenen yöntemleri bu metodun yerine tek tek çağırın.
            Kesilmiş resim alanları kalıcı olarak kaldırılır ve PowerPoint'te geri getirilemez.

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `presentation` `None` değerindedir. |



### Ayrıca Bakınız
* sınıf [`Compress`](/slides/python-net/tr/aspose.slides.lowcode/compress)
* sınıf [`Presentation`](/slides/python-net/tr/aspose.slides/presentation)
* modül [`aspose.slides.lowcode`](/slides/python-net/tr/aspose.slides.lowcode)
* kütüphane [`Aspose.Slides`](/slides/python-net)