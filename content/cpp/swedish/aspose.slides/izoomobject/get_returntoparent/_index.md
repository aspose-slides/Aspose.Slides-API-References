---
title: get_ReturnToParent()
second_title: Aspose.Slides för C++ API-referens
description: "Hämtar navigeringsbeteendet i bildspelet. Läs bool. Standardvärde: false"
type: docs
weight: 27
url: /sv/aspose.slides/izoomobject/get_returntoparent/
---
## IZoomObject::get_ReturnToParent() metod

Hämtar navigeringsbeteendet i bildspelet. Läs **bool**. Standardvärde: false

```cpp
virtual bool Aspose::Slides::IZoomObject::get_ReturnToParent()=0
```

## Anmärkningar

Sant värde på egenskapen anger återgång till föräldernavigering i bildspelet. 

Exempel: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ReturnToParent(true);
```

## Se även

* Klass [IZoomObject](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)