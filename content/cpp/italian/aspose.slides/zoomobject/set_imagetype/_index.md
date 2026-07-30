---
title: set_ImageType()
second_title: Riferimento API di Aspose.Slides per C++
description: "Imposta il tipo di immagine di un oggetto zoom. Scrivi ZoomImageType. Valore predefinito: Preview"
type: docs
weight: 14
url: /it/aspose.slides/zoomobject/set_imagetype/
---
## ZoomObject::set_ImageType(ZoomImageType) metodo


Imposta il tipo di immagine di un oggetto zoom. Scrivi [ZoomImageType](../../zoomimagetype/). Valore predefinito: Preview

```cpp
void Aspose::Slides::ZoomObject::set_ImageType(ZoomImageType value) override
```

## Osservazioni


Specificare se l'oggetto Zoom utilizza l'anteprima della diapositiva o un'immagine di copertina. 

Il prossimo esempio dimostra la modifica di Image Type al valore Preview. In questo caso l'immagine corrente di un oggetto Zoom cambia in immagine della diapositiva: 
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
* Namespace [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)