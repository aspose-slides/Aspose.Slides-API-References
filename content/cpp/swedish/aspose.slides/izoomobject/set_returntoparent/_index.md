---
title: set_ReturnToParent()
second_title: Aspose.Slides för C++ API-referens
description: "Ställer in navigeringsbeteendet i bildspelet. Skriv bool. Standardvärde: false"
type: docs
weight: 40
url: /sv/aspose.slides/izoomobject/set_returntoparent/
---
## IZoomObject::set_ReturnToParent(bool) metod


Ställer in navigeringsbeteendet i bildspelet. Skriv **bool**. Standardvärde: false

```cpp
virtual void Aspose::Slides::IZoomObject::set_ReturnToParent(bool value)=0
```

## Anmärkningar


Sant värde på egenskapen anger återgång till föräldernavigeringsbeteende i bildspelet. 

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