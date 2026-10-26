---
title: get_SaveMetafilesAsPng()
second_title: Riferimento API Aspose.Slides per C++
description: True per convertire tutti i metafile usati in una presentazione in immagini PNG. Leggi bool.
type: docs
weight: 326
url: /it/aspose.slides.export/pdfoptions/get_savemetafilesaspng/
---
## PdfOptions::get_SaveMetafilesAsPng() metodo

True per convertire tutti i metafile usati in una presentazione in immagini PNG. Leggi **bool**.

```cpp
bool Aspose::Slides::Export::PdfOptions::get_SaveMetafilesAsPng() override
```

## Osservazioni

Il valore predefinito è **true**. Un documento Pdf può contenere grafica vettoriale e immagini raster. Se SaveMetafilesAsPng è impostato su true, l'immagine Metafile di origine viene convertita nel formato Png e salvata nel Pdf come immagine raster. Se SaveMetafilesAsPng è impostato su false, il Metafile di origine viene convertito nella grafica vettoriale Pdf. Ogni approccio ha vantaggi e svantaggi. Ad esempio, se il Metafile viene convertito in PNG, è possibile una certa perdita di qualità durante il ridimensionamento del documento risultante. Se il Metafile viene convertito nella grafica vettoriale Pdf, possono verificarsi problemi di prestazioni nello strumento di visualizzazione Pdf.

## Vedi anche

* Classe [PdfOptions](../)
* Spazio dei nomi [Aspose::Slides::Export](../../)
* Libreria [Aspose.Slides](../../../)