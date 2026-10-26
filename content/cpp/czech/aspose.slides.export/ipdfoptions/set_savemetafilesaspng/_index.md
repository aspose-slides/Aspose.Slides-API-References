---
title: set_SaveMetafilesAsPng()
second_title: Aspose.Slides pro C++ API Reference
description: True převádí všechny metafily použité v prezentaci na obrázky PNG. Zapište bool.
type: docs
weight: 300
url: /cs/aspose.slides.export/ipdfoptions/set_savemetafilesaspng/
---
## IPdfOptions::set_SaveMetafilesAsPng(bool) metoda


True převádí všechny metafily použité v prezentaci na obrázky PNG. Zapište **bool**.

```cpp
virtual void Aspose::Slides::Export::IPdfOptions::set_SaveMetafilesAsPng(bool value)=0
```

## Poznámky


Výchozí hodnota je **true**. Dokument Pdf může obsahovat vektorovou grafiku a rastrové obrázky. Pokud je SaveMetafilesAsPng nastaveno na true, pak je zdrojový obrázek Metafile převeden do formátu Png a uložen do Pdf jako rastrový obrázek. Pokud je SaveMetafilesAsPng nastaveno na false, pak je zdrojový Metafile převeden na vektorovou grafiku Pdf. Každý přístup má své výhody i nevýhody. Například pokud je Metafile převeden na PNG, může dojít ke ztrátě kvality při škálování výsledného dokumentu. Pokud je Metafile převeden na vektorovou grafiku Pdf, mohou se objevit problémy s výkonem v prohlížeči Pdf. 
## Viz také

* Třída [IPdfOptions](../)
* Jmenný prostor [Aspose::Slides::Export](../../)
* Knihovna [Aspose.Slides](../../../)