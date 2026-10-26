---
title: get_SaveMetafilesAsPng()
second_title: Aspose.Slides pro C++ API Reference
description: True k převodu všech metafiles použitých v prezentaci na obrázky PNG. Čte se bool.
type: docs
weight: 287
url: /cs/aspose.slides.export/ipdfoptions/get_savemetafilesaspng/
---
## IPdfOptions::get_SaveMetafilesAsPng() metoda

True k převodu všech metafiles použitých v prezentaci na obrázky PNG. Čte se **bool**.

```cpp
virtual bool Aspose::Slides::Export::IPdfOptions::get_SaveMetafilesAsPng()=0
```

## Poznámky

Výchozí hodnota je **true**. Dokument Pdf může obsahovat vektorovou grafiku a rastrové obrázky. Pokud je SaveMetafilesAsPng nastaveno na true, pak je zdrojový obrázek Metafile převeden do formátu Png a uložen do Pdf jako rastrový obrázek. Pokud je SaveMetafilesAsPng nastaveno na false, pak je zdrojový Metafile převeden na vektorovou grafiku Pdf. Každý přístup má své výhody i nevýhody. Například pokud je Metafile převeden na PNG, může dojít k určité ztrátě kvality při škálování výsledného dokumentu. Pokud je Metafile převeden na vektorovou grafiku Pdf, mohou se objevit problémy s výkonem při prohlížení Pdf.

## Viz také

* Třída [IPdfOptions](../)
* Jmenný prostor [Aspose::Slides::Export](../../)
* Knihovna [Aspose.Slides](../../../)