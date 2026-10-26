---
title: get_TargetSlide()
second_title: Aspose.Slides para C++ Referência de API
description: Obtém o objeto slide ao qual o objeto Slide Zoom está vinculado. Leia ISlide.
type: docs
weight: 1
url: /pt/aspose.slides/zoomframe/get_targetslide/
---
## ZoomFrame::get_TargetSlide() método

Obtém o objeto slide ao qual o objeto Zoom [Slide](../../slide/) está vinculado. Leia [ISlide](../../islide/).

```cpp
System::SharedPtr<ISlide> Aspose::Slides::ZoomFrame::get_TargetSlide() override
```

## Observações

O próximo exemplo demonstra a alteração do slide de destino e cria uma nova imagem para o objeto Zoom [Slide](../../slide/):
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TargetSlide(pres->get_Slides()->idx_get(2));
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISlide](../../islide/)
* Classe [ZoomFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)