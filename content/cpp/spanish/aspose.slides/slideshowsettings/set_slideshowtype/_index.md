---
title: set_SlideShowType()
second_title: Referencia de API de Aspose.Slides para C++
description: "Establece el tipo de presentación de diapositivas. Representado por los siguientes ancestros de SlideShowType: BrowsedAtKiosk, PresentedBySpeaker y BrowsedByIndividual"
type: docs
weight: 14
url: /es/aspose.slides/slideshowsettings/set_slideshowtype/
---
## SlideShowSettings::set_SlideShowType(System::SharedPtr\<Aspose::Slides::SlideShowType\>) método


Establece el tipo de presentación de diapositivas. Representado por los siguientes [SlideShowType](../../slideshowtype/) ancestros: [BrowsedAtKiosk](../../browsedatkiosk/), [PresentedBySpeaker](../../presentedbyspeaker/) y [BrowsedByIndividual](../../browsedbyindividual/)

```cpp
void Aspose::Slides::SlideShowSettings::set_SlideShowType(System::SharedPtr<Aspose::Slides::SlideShowType> value)
```

## Observaciones



```cpp
auto pres = System::MakeObject<Presentation>();

// para establecer el tipo "Navegado en un quiosco (pantalla completa)"
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<BrowsedAtKiosk>());

// para establecer el tipo "Navegado por individuo (ventana)"
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<BrowsedByIndividual>());

// para establecer el tipo "Presentado por un orador (pantalla completa)"
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<PresentedBySpeaker>());
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [SlideShowType](../../slideshowtype/)
* Clase [SlideShowSettings](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)