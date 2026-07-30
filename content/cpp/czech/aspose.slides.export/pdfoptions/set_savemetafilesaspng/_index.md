---
title: set_SaveMetafilesAsPng()
second_title: Aspose.Slides pro C++ API Reference
description: True, pokud chcete převést všechny metafily použité v prezentaci na obrázky PNG. Zapište bool.
type: docs
weight: 339
url: /cs/aspose.slides.export/pdfoptions/set_savemetafilesaspng/
---
## PdfOptions::set_SaveMetafilesAsPng(bool) metoda

True, pokud chcete převést všechny metafily použité v prezentaci na obrázky PNG. Zapište **bool**.

```cpp
void Aspose::Slides::Export::PdfOptions::set_SaveMetafilesAsPng(bool value) override
```

## Poznámky

Výchozí je **true**. Dokument Pdf může obsahovat vektorovou grafiku a rastrové obrázky. Pokud je SaveMetafilesAsPng nastaveno na true, pak je zdrojový obrázek Metafile převeden do formátu Png a uložen do Pdf jako rastrový obrázek. Pokud je SaveMetafilesAsPng nastaveno na false, pak je zdrojový Metafile převeden na vektorovou grafiku Pdf. Každý přístup má výhody i nevýhody. Například pokud je Metafile převeden na PNG, může dojít k určité ztrátě kvality při škálování výsledného dokumentu. Pokud je Metafile převeden na vektorovou grafiku Pdf, mohou nastat výkonové problémy v prohlížeči Pdf.

## Viz také

* Třída [PdfOptions](../)
* Jmenný prostor [Aspose::Slides::Export](../../)
* Knihovna [Aspose.Slides](../../../)