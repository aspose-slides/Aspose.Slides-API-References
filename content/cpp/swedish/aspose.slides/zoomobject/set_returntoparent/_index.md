---
title: set_ReturnToParent()
second_title: Aspose.Slides för C++ API-referens
description: "Ställer in navigeringsbeteendet i bildspel. Skriv bool. Standardvärde: false"
type: docs
weight: 40
url: /sv/aspose.slides/zoomobject/set_returntoparent/
---
## ZoomObject::set_ReturnToParent(bool) metod


Ställer in navigeringsbeteendet i bildspel. Skriv **bool**. Standardvärde: false

```cpp
void Aspose::Slides::ZoomObject::set_ReturnToParent(bool value) override
```

## Anmärkningar


Sant värde på egenskapen anger återgång till föräldernavigering i bildspel. 

Exempel: 
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ReturnToParent(true);
```

## Se även

* Klass [ZoomObject](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)