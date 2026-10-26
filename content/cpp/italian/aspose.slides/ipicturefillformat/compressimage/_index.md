---
title: CompressImage()
second_title: Riferimento API di Aspose.Slides per C++
description: Comprimi l'immagine riducendo le sue dimensioni in base alle dimensioni della forma e alla risoluzione specificata. Facoltativamente, elimina anche le aree ritagliate.
type: docs
weight: 443
url: /it/aspose.slides/ipicturefillformat/compressimage/
---
## IPictureFillFormat::CompressImage(bool, Export::PicturesCompression) method

Comprimi l'immagine riducendo le sue dimensioni in base alle dimensioni della forma e alla risoluzione specificata. Facoltativamente, elimina anche le aree ritagliate.

```cpp
virtual bool Aspose::Slides::IPictureFillFormat::CompressImage(bool deleteCroppedAreasOfImage, Export::PicturesCompression resolution)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| deleteCroppedAreasOfImage | **bool** | Se true, il metodo rimuoverà le aree ritagliate dell'immagine, riducendo ulteriormente le sue dimensioni. |
| resolution | [Export::PicturesCompression](../../../aspose.slides.export/picturescompression/) | La risoluzione target per la compressione, specificata come valore dell'enum [Export::PicturesCompression](../../../aspose.slides.export/picturescompression/). |

### Valore di ritorno

Un **bool** che indica se l'immagine è stata compressa con successo. Restituisce ****true****

## Osservazioni

Questo metodo modifica le dimensioni e la risoluzione dell'immagine in modo simile alla funzionalità "Picture Format -> Compress Pictures" di PowerPoint.

se l'immagine è stata ridimensionata o ritagliata, altrimenti ****false****

. 

L'esempio seguente dimostra come utilizzare il metodo **CompressImage** per ridurre le dimensioni di un'immagine in una presentazione impostando una risoluzione target e rimuovendo le aree ritagliate: 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));
// Comprimi l'immagine con una risoluzione target di 150 DPI (risoluzione Web) e rimuovi le aree ritagliate
bool result = picFrame->get_PictureFormat()->CompressImage(true, PicturesCompression::Dpi150);
```

## IPictureFillFormat::CompressImage(bool, float) method

Comprimi l'immagine riducendo le sue dimensioni in base alle dimensioni della forma e alla risoluzione specificata. Facoltativamente, elimina anche le aree ritagliate.

```cpp
virtual bool Aspose::Slides::IPictureFillFormat::CompressImage(bool deleteCroppedAreasOfImage, float resolution)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| deleteCroppedAreasOfImage | **bool** | Se true, il metodo rimuoverà le aree ritagliate dell'immagine, riducendo ulteriormente le sue dimensioni. |
| resolution | **float** | La risoluzione target in DPI. Questo valore deve essere positivo e definisce come l'immagine verrà ridimensionata. |

### Valore di ritorno

Un **bool** che indica se l'immagine è stata compressa con successo. Restituisce ****true****

## Osservazioni

Questo metodo modifica le dimensioni e la risoluzione dell'immagine in modo simile alla funzionalità "Picture Format -> Compress Pictures" di PowerPoint.

se l'immagine è stata ridimensionata o ritagliata, altrimenti ****false****

. 

L'esempio seguente dimostra come utilizzare il metodo **CompressImage** per ridurre le dimensioni di un'immagine in una presentazione impostando una risoluzione target e rimuovendo le aree ritagliate: 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Ottiene il PictureFrame
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));

// Comprimi l'immagine con una risoluzione target di 150 DPI (risoluzione Web) e rimuovi le aree ritagliate
bool result = picFrame->get_PictureFormat()->CompressImage(true, 150.0f); // risoluzione Web
```

## Vedi anche

* Enum [PicturesCompression](../../../aspose.slides.export/picturescompression/)
* Classe [IPictureFillFormat](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)