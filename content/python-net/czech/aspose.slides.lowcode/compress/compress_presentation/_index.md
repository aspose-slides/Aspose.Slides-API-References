---
title: compress_presentation method
second_title: Aspose.Slides pro Python přes .NET referenci API
description: 
type: docs
url: /cs/aspose.slides.lowcode/compress/compress_presentation/
weight: 30
---
## compress_presentation(presentation) {#presentation}
Reduces the size of a presentation by applying all available compression steps:
            
* Odstraňuje nepoužívané hlavní snímky **Aspose.Slides.LowCode.Compress.RemoveUnusedMasterSlides(Aspose.Slide**.
* Odstraňuje nepoužívané rozložení snímků **Aspose.Slides.LowCode.Compress.RemoveUnusedLayoutSlides(Aspose.Slide**.
* Ponechává pouze glyfy skutečně použité ve vložených fontech **Aspose.Slides.LowCode.Compress.CompressEmbeddedFonts(Aspose.Slide**.
* Snižuje rozlišení obrázků na 150 DPI a odstraňuje oříznuté oblasti obrázků **Aspose.Slides.LowCode.Compress.CompressImages(Aspose.Slides.IPresentation,Aspose.Slides.Expor**.


```python
@staticmethod
def compress_presentation(presentation):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| presentation | [`Presentation`](/slides/python-net/cs/aspose.slides/presentation) | Prezentace ke kompresi. |

### Poznámky

Chcete-li přizpůsobit kompresi, například použít jiné rozlišení obrázku nebo vynechat krok,
            zavolejte výše uvedené metody jednotlivě místo této.
            Oříznuté oblasti obrázků jsou odstraněny trvale a nelze je v PowerPointu obnovit.

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `presentation` je `None`. |



### Viz také
* třída [`Compress`](/slides/python-net/cs/aspose.slides.lowcode/compress)
* třída [`Presentation`](/slides/python-net/cs/aspose.slides/presentation)
* modul [`aspose.slides.lowcode`](/slides/python-net/cs/aspose.slides.lowcode)
* knihovna [`Aspose.Slides`](/slides/python-net)