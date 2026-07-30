---
title: set_SaveMetafilesAsPng()
second_title: Riferimento API di Aspose.Slides per C++
description: True per convertire tutti i metafili utilizzati in una presentazione nelle immagini PNG. Scrivi bool.
type: docs
weight: 300
url: /it/aspose.slides.export/ipdfoptions/set_savemetafilesaspng/
---
## IPdfOptions::set_SaveMetafilesAsPng(bool) metodo


True per convertire tutti i metafili utilizzati in una presentazione in immagini PNG. Scrivi **bool**.

```cpp
virtual void Aspose::Slides::Export::IPdfOptions::set_SaveMetafilesAsPng(bool value)=0
```

## Osservazioni


Il valore predefinito è **true**. Il documento Pdf può contenere grafica vettoriale e immagini raster. Se SaveMetafilesAsPng è impostato su true allora l'immagine Metafile di origine viene convertita in formato Png e salvata in Pdf come immagine raster. Se SaveMetafilesAsPng è impostato su false allora il Metafile di origine viene convertito in grafica vettoriale Pdf. Ogni approccio ha vantaggi e svantaggi. Ad esempio, se Metafile viene convertito in PNG, è possibile una perdita di qualità durante lo scaling del documento risultante. Se Metafile viene convertito in grafica vettoriale Pdf, è possibile che si verifichino problemi di prestazioni nello strumento di visualizzazione Pdf. 
## Vedi anche

* Classe [IPdfOptions](../)
* Spazio dei nomi [Aspose::Slides::Export](../../)
* Libreria [Aspose.Slides](../../../)