---
title: get_HeaderFooterManager()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve el administrador real de HeaderFooter. Solo lectura IPresentationHeaderFooterManager.
type: docs
weight: 27
url: /es/aspose.slides/presentation/get_headerfootermanager/
---
## Presentation::get_HeaderFooterManager() método


Devuelve el administrador real de HeaderFooter. Solo lectura [IPresentationHeaderFooterManager](../../ipresentationheaderfootermanager/).

```cpp
System::SharedPtr<IPresentationHeaderFooterManager> Aspose::Slides::Presentation::get_HeaderFooterManager() override
```

## Observaciones


El siguiente ejemplo muestra cómo establecer la visibilidad del pie de página dentro de [Slide](../../slide/) de PowerPoint [Presentation](../). 
```cpp
auto presentation = System::MakeObject<Presentation>(u"presentation.ppt");
auto slide = presentation->get_Slides()->idx_get(0);

System::SharedPtr<IBaseSlideHeaderFooterManager> headerFooterManager = slide->get_HeaderFooterManager();
// Propiedad IsFooterVisible se usa para indicar que no está presente un marcador de posición de pie de página de la diapositiva.
if (!headerFooterManager->get_IsFooterVisible())
{
    // Método SetFooterVisibility se usa para hacer visible un marcador de posición de pie de página de la diapositiva.
    headerFooterManager->SetFooterVisibility(true);
}

// Propiedad IsSlideNumberVisible se usa para indicar que no está presente un marcador de posición del número de página de la diapositiva.
if (!headerFooterManager->get_IsSlideNumberVisible())
{
    // Método SetSlideNumberVisibility se usa para hacer visible un marcador de posición del número de página de la diapositiva.
    headerFooterManager->SetSlideNumberVisibility(true);
}

// Propiedad IsDateTimeVisible se usa para indicar que no está presente un marcador de posición de fecha y hora de la diapositiva.
if (!headerFooterManager->get_IsDateTimeVisible())
{
    // Método SetFooterVisibility se usa para hacer visible un marcador de posición de fecha y hora de la diapositiva.
    headerFooterManager->SetDateTimeVisibility(true);
}

// Método SetFooterText se usa para establecer texto en el marcador de posición de pie de página de la diapositiva.
headerFooterManager->SetFooterText(u"Footer text");
// Método SetDateTimeText se usa para establecer texto en el marcador de posición de fecha y hora de la diapositiva.
headerFooterManager->SetDateTimeText(u"Date and time text");
presentation->Save(u"Presentation.ppt", SaveFormat::Ppt);
```
 El siguiente ejemplo muestra cómo establecer la visibilidad del pie de página hijo dentro de [Slide](../../slide/). 
```cpp
auto presentation = System::MakeObject<Presentation>(u"presentation.ppt");
System::SharedPtr<IMasterSlideHeaderFooterManager> headerFooterManager = presentation->get_Masters()->idx_get(0)->get_HeaderFooterManager();

// Método SetFooterAndChildFootersVisibility se usa para hacer visible una diapositiva maestra y todos los marcadores de posición de pie de página hijos.
headerFooterManager->SetFooterAndChildFootersVisibility(true);

// Método SetSlideNumberAndChildSlideNumbersVisibility se usa para hacer visible una diapositiva maestra y todos los marcadores de posición del número de página hijos.
headerFooterManager->SetSlideNumberAndChildSlideNumbersVisibility(true);

// Método SetDateTimeAndChildDateTimesVisibility se usa para hacer visible una diapositiva maestra y todos los marcadores de posición de fecha y hora hijos.
headerFooterManager->SetDateTimeAndChildDateTimesVisibility(true);

// Método SetFooterAndChildFootersText se usa para establecer texto en la diapositiva maestra y todos los marcadores de posición de pie de página hijos.
headerFooterManager->SetFooterAndChildFootersText(u"Footer text");

// Método SetDateTimeAndChildDateTimesText se usa para establecer texto en la diapositiva maestra y todos los marcadores de posición de fecha y hora hijos.
headerFooterManager->SetDateTimeAndChildDateTimesText(u"Date and time text");
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IPresentationHeaderFooterManager](../../ipresentationheaderfootermanager/)
* Clase [Presentation](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)