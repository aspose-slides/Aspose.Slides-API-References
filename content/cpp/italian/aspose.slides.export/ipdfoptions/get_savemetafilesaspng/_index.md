---
title: get_SaveMetafilesAsPng()
second_title: Riferimento API di Aspose.Slides per C++
description: True per convertire tutti i metafile usati in una presentazione in immagini PNG. Leggi bool.
type: docs
weight: 287
url: /it/aspose.slides.export/ipdfoptions/get_savemetafilesaspng/
---
## IPdfOptions::get_SaveMetafilesAsPng() metodo

True per convertire tutti i metafile usati in una presentazione in immagini PNG. Leggi **bool**.

```cpp
virtual bool Aspose::Slides::Export::IPdfOptions::get_SaveMetafilesAsPng()=0
```

## Osservazioni

Il valore predefinito è **true**. Un documento Pdf può contenere grafica vettoriale e immagini raster. Se SaveMetafilesAsPng è impostato su true, l'immagine Metafile di origine viene convertita in formato Png e salvata nel Pdf come immagine raster. Se SaveMetafilesAsPng è impostato su false, il Metafile di origine viene convertito in grafica vettoriale Pdf. Ogni approccio ha vantaggi e svantaggi. Ad esempio, se il Metafile viene convertito in PNG, è possibile una perdita di qualità durante lo scaling del documento risultante. Se il Metafile viene convertito in grafica vettoriale Pdf, possono verificarsi problemi di prestazioni nello strumento di visualizzazione Pdf.

## Vedi anche

* Classe [IPdfOptions](../)
* Spazio dei nomi [Aspose::Slides::Export](../../)
* Libreria [Aspose.Slides](../../../)