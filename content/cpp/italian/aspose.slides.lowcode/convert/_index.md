---
title: Convert
second_title: Riferimento API di Aspose.Slides per C++
description: Rappresenta un gruppo di metodi destinati a convertire Presentation.
type: docs
weight: 27
url: /it/aspose.slides.lowcode/convert/
---
## Classe di conversione

Rappresenta un gruppo di metodi destinati a convertire [Presentation](../../aspose.slides/presentation/).

```cpp
class Convert
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| static void [AutoByExtension](./autobyextension/)([System::String](../../system/string/), [System::String](../../system/string/)) | Converte [Presentation](../../aspose.slides/presentation/) usando l'estensione del percorso di output fornita per determinare il formato di esportazione richiesto. |
|  [Convert](./convert/)() |  |
| static void [ToJpeg](./tojpeg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/)) | Converte la presentazione di input in un insieme di immagini in formato JPEG.  

 Se il nome del file di output è fornito come "myPath/myFilename.jpeg", il risultato verrà salvato come un insieme di file "myPath/myFilename_N.jpeg", dove N è il numero della diapositiva. |
| static void [ToJpeg](./tojpeg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), [System::Drawing::Size](../../system.drawing/size/)) | Converte la presentazione di input in un insieme di immagini in formato JPEG.  

 Se il nome del file di output è fornito come "myPath/myFilename.jpeg", il risultato verrà salvato come un insieme di file "myPath/myFilename_N.jpeg", dove N è il numero della diapositiva. |
| static void [ToJpeg](./tojpeg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), **float**, [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>) | Converte la presentazione di input in un insieme di immagini in formato JPEG.  

 Se il nome del file di output è fornito come "myPath/myFilename.jpeg", il risultato verrà salvato come un insieme di file "myPath/myFilename_N.jpeg", dove N è il numero della diapositiva. |
| static void [ToPdf](./topdf/)([System::String](../../system/string/), [System::String](../../system/string/)) | Converte [Presentation](../../aspose.slides/presentation/) in PDF. |
| static void [ToPdf](./topdf/)([System::String](../../system/string/), [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../aspose.slides.export/ipdfoptions/)\>) | Converte [Presentation](../../aspose.slides/presentation/) in PDF. |
| static void [ToPdf](./topdf/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/)) | Converte [Presentation](../../aspose.slides/presentation/) in PDF. |
| static void [ToPdf](./topdf/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../aspose.slides.export/ipdfoptions/)\>) | Converte [Presentation](../../aspose.slides/presentation/) in PDF. |
| static void [ToPng](./topng/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/)) | Converte la presentazione di input in un insieme di immagini in formato PNG.  

 Se il nome del file di output è fornito come "myPath/myFilename.png", il risultato verrà salvato come un insieme di file "myPath/myFilename_N.png", dove N è il numero della diapositiva. |
| static void [ToPng](./topng/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), [System::Drawing::Size](../../system.drawing/size/)) | Converte la presentazione di input in un insieme di immagini in formato PNG.  

 Se il nome del file di output è fornito come "myPath/myFilename.png", il risultato verrà salvato come un insieme di file "myPath/myFilename_N.png", dove N è il numero della diapositiva. |
| static void [ToPng](./topng/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), **float**, [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>) | Converte la presentazione di input in un insieme di immagini in formato PNG.  

 Se il nome del file di output è fornito come "myPath/myFilename.png", il risultato verrà salvato come un insieme di file "myPath/myFilename_N.png", dove N è il numero della diapositiva. |
| static void [ToSvg](./tosvg/)([System::String](../../system/string/)) | Converte [Presentation](../../aspose.slides/presentation/) in SVG. |
| static void [ToSvg](./tosvg/)([System::String](../../system/string/), [Convert::GetOutPathCallback](./getoutpathcallback/)) | Converte [Presentation](../../aspose.slides/presentation/) in SVG. |
| static void [ToSvg](./tosvg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [Convert::GetOutPathCallback](./getoutpathcallback/)) | Converte [Presentation](../../aspose.slides/presentation/) in SVG. |
| static void [ToSvg](./tosvg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | Converte [Presentation](../../aspose.slides/presentation/) in SVG. |
| static void [ToSvg](./tosvg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [Convert::GetOutPathCallback](./getoutpathcallback/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | Converte [Presentation](../../aspose.slides/presentation/) in SVG. |
| static void [ToTiff](./totiff/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/)) | Converte la presentazione di input in un insieme di immagini in formato TIFF.  

 Se il nome del file di output è fornito come "myPath/myFilename.tiff", il risultato verrà salvato come un insieme di file "myPath/myFilename_N.tiff", dove N è il numero della diapositiva. |
| static void [ToTiff](./totiff/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::ITiffOptions](../../aspose.slides.export/itiffoptions/)\>, **bool**) | Converte la presentazione di input in formato TIFF con opzioni personalizzate. Se il nome del file di output è fornito come "myPath/myFilename.tiff" e *multipage* è **false**, il risultato verrà salvato come un insieme di file "myPath/myFilename_N.tiff", dove N è il numero della diapositiva. Altrimenti, se *multipage* è **true**, il risultato sarà un documento multi-pagina "myPath/myFilename.tiff". |

## Typedef

| Typedef | Descrizione |
| --- | --- |
| [GetOutPathCallback](./getoutpathcallback/) | Callback che verrà invocato per ogni [Slide](../../aspose.slides/slide/), con il percorso di output che ci si aspetta venga restituito. |

## Osservazioni



```cpp
Convert::AutoByExtension(u"pres.pptx", u"pres.pdf");
```

## Vedi anche

* Spazio dei nomi [Aspose::Slides::LowCode](../)
* Libreria [Aspose.Slides](../../)