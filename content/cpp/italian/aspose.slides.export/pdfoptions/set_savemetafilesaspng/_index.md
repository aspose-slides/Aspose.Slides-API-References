---
title: set_SaveMetafilesAsPng()
second_title: Riferimento API di Aspose.Slides per C++
description: True per convertire tutti i metafile utilizzati in una presentazione in immagini PNG. Scrivi bool.
type: docs
weight: 339
url: /it/aspose.slides.export/pdfoptions/set_savemetafilesaspng/
---
## PdfOptions::set_SaveMetafilesAsPng(bool) metodo

True per convertire tutti i metafile utilizzati in una presentazione in immagini PNG. Scrivi **bool**.

```cpp
void Aspose::Slides::Export::PdfOptions::set_SaveMetafilesAsPng(bool value) override
```

## Osservazioni

Default è **true**. Il documento Pdf può contenere grafica vettoriale e immagini raster. Se SaveMetafilesAsPng è impostato su true allora l'immagine Metafile di origine viene convertita in formato Png e salvata nel Pdf come immagine raster. Se SaveMetafilesAsPng è impostato su false allora il Metafile di origine viene convertito in grafica vettoriale Pdf. Ogni approccio ha vantaggi e svantaggi. Per esempio, se il Metafile viene convertito in PNG, allora è possibile una perdita di qualità durante il ridimensionamento del documento risultante. Se il Metafile viene convertito in grafica vettoriale Pdf, allora è possibile che si verifichino problemi di prestazioni nello strumento di visualizzazione Pdf.

## Vedi anche

* Classe [PdfOptions](../)
* Spazio dei nomi [Aspose::Slides::Export](../../)
* Libreria [Aspose.Slides](../../../)