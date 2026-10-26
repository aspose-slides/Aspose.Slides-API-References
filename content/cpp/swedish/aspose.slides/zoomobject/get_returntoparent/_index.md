---
title: get_ReturnToParent()
second_title: Aspose.Slides för C++ API-referens
description: "Hämtar navigeringsbeteendet i bildspelet. Läs bool. Standardvärde: false"
type: docs
weight: 27
url: /sv/aspose.slides/zoomobject/get_returntoparent/
---
## ZoomObject::get_ReturnToParent() metod


Hämtar navigeringsbeteendet i bildspelet. Läs **bool**. Standardvärde: false

```cpp
bool Aspose::Slides::ZoomObject::get_ReturnToParent() override
```

## Anmärkningar


Sant värde på egenskapen anger återgång till förälder-navigeringsbeteendet i bildspelet. 

Exempel: 
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ReturnToParent(true);
```

## Se även

* Klass [ZoomObject](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)