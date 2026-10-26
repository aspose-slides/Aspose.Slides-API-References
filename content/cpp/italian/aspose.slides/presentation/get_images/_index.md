---
title: get_Images()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce la collezione di tutte le immagini nella presentazione. Solo lettura IImageCollection.
type: docs
weight: 209
url: /it/aspose.slides/presentation/get_images/
---
## Presentation::get_Images() metodo

Restituisce la collezione di tutte le immagini nella presentazione. Solo lettura [IImageCollection](../../iimagecollection/).

```cpp
System::SharedPtr<IImageCollection> Aspose::Slides::Presentation::get_Images() override
```

## Osservazioni

I seguenti esempi mostrano come aggiungere un'immagine come BLOB in PowerPoint [Presentation](../). 
```cpp
System::String pathToLargeImage = u"large_image.jpg";
// crea una nuova presentazione a cui verrà aggiunta l'immagine.
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

auto fileStream = System::MakeObject<System::IO::FileStream>(pathToLargeImage, System::IO::FileMode::Open);

// Aggiungiamo l'immagine alla presentazione - scegliamo il comportamento KeepLocked perché
// NON intendiamo accedere al file "largeImage.png".
auto img = pres->get_Images()->AddImage(fileStream, LoadingStreamBehavior::KeepLocked);
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 0.0f, 0.0f, 300.0f, 200.0f, img);
// Salva la presentazione. Mentre viene generata una presentazione di grandi dimensioni, il consumo di memoria
// rimane basso per tutta la durata dell'oggetto pres.
pres->Save(u"presentationWithLargeImage.pptx", SaveFormat::Pptx);
```
I seguenti esempi aggiungono un collegamento ipertestuale a un'immagine in un PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

// Aggiunge l'immagine alla presentazione
auto image = pres->get_Images()->AddImage(System::IO::File::ReadAllBytes(u"image.png"));
// Crea un frame immagine nella diapositiva 1 basato sull'immagine aggiunta in precedenza
auto pictureFrame = slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
pictureFrame->set_HyperlinkClick(System::MakeObject<Hyperlink>(u"https://www.aspose.com/"));
pictureFrame->get_HyperlinkClick()->set_Tooltip(u"More than 70% Fortune 100 companies trust Aspose APIs");
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* classe [IImageCollection](../../iimagecollection/)
* classe [Presentation](../)
* spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)