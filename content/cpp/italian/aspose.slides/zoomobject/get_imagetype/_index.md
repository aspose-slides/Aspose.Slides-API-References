---
title: get_ImageType()
second_title: Riferimento API Aspose.Slides per C++
description: "Restituisce il tipo di immagine di un oggetto zoom. Leggi ZoomImageType. Valore predefinito: Preview"
type: docs
weight: 1
url: /it/aspose.slides/zoomobject/get_imagetype/
---
## ZoomObject::get_ImageType() metodo

Restituisce il tipo di immagine di un oggetto zoom. Leggi [ZoomImageType](../../zoomimagetype/). Valore predefinito: Preview

```cpp
ZoomImageType Aspose::Slides::ZoomObject::get_ImageType() override
```

## Osservazioni

Specifica se l'oggetto Zoom sta usando l'anteprima della diapositiva o un'immagine di copertina.

Il prossimo esempio dimostra come modificare Image Type al valore Preview. In questo caso l'immagine corrente di un oggetto Zoom cambia in immagine della diapositiva: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
zoomFrame->set_ImageType(ZoomImageType::Preview);
```

## Vedi anche

* Enum [ZoomImageType](../../zoomimagetype/)
* Classe [ZoomObject](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)