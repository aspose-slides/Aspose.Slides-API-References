---
title: get_SaveMetafilesAsPng()
second_title: Aspose.Slides pro C++ API Reference
description: True pro konverzi všech metasouborů použitých v prezentaci na obrázky PNG. Čte se bool.
type: docs
weight: 326
url: /cs/aspose.slides.export/pdfoptions/get_savemetafilesaspng/
---
## PdfOptions::get_SaveMetafilesAsPng() metoda


True pro konverzi všech metasouborů použitých v prezentaci na obrázky PNG. Čte se **bool**.

```cpp
bool Aspose::Slides::Export::PdfOptions::get_SaveMetafilesAsPng() override
```

## Poznámky


Výchozí hodnota je **true**. Dokument Pdf může obsahovat vektorovou grafiku a rastrové obrázky. Pokud je SaveMetafilesAsPng nastaveno na true, pak je zdrojový obrázek Metafile převeden do formátu Png a uložen do Pdf jako rastrový obrázek. Pokud je SaveMetafilesAsPng nastaveno na false, pak je zdrojový Metafile převeden na vektorovou grafiku Pdf. Každý přístup má výhody i nevýhody. Například pokud je Metafile převeden na PNG, může během škálování výsledného dokumentu dojít ke ztrátě kvality. Pokud je Metafile převeden na vektorovou grafiku Pdf, mohou se objevit problémy s výkonem v prohlížeči Pdf. 
## Viz také

* Třída [PdfOptions](../)
* Jmenný prostor [Aspose::Slides::Export](../../)
* Knihovna [Aspose.Slides](../../../)