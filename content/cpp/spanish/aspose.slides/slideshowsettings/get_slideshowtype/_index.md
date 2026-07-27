---
title: get_SlideShowType()
second_title: Referencia de API de Aspose.Slides para C++
description: "Obtiene el tipo de presentación de diapositivas. Representado por los siguientes ancestros de SlideShowType: BrowsedAtKiosk, PresentedBySpeaker y BrowsedByIndividual"
type: docs
weight: 1
url: /es/aspose.slides/slideshowsettings/get_slideshowtype/
---
## SlideShowSettings::get_SlideShowType() método

Obtiene el tipo de presentación de diapositivas. Representado por los siguientes [SlideShowType](../../slideshowtype/) ancestros: [BrowsedAtKiosk](../../browsedatkiosk/), [PresentedBySpeaker](../../presentedbyspeaker/) y [BrowsedByIndividual](../../browsedbyindividual/)

```cpp
System::SharedPtr<Aspose::Slides::SlideShowType> Aspose::Slides::SlideShowSettings::get_SlideShowType()
```

## Observaciones

```cpp
auto pres = System::MakeObject<Presentation>();

// para establecer el tipo "Navegado en un kiosco (pantalla completa)"
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<BrowsedAtKiosk>());

// para establecer el tipo "Navegado por un individuo (ventana)"
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<BrowsedByIndividual>());

// para establecer el tipo "Presentado por un ponente (pantalla completa)"
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<PresentedBySpeaker>());
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [SlideShowType](../../slideshowtype/)
* Clase [SlideShowSettings](../)
* Espacio de nombres [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)