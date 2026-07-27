---
title: set_TargetSlide()
second_title: Aspose.Slides para C++ Referência da API
description: Define o objeto slide ao qual o objeto Slide Zoom está vinculado. Escreva ISlide.
type: docs
weight: 14
url: /pt/aspose.slides/izoomframe/set_targetslide/
---
## IZoomFrame::set_TargetSlide(System::SharedPtr\<ISlide\>) método

Define o objeto slide ao qual o objeto Zoom [Slide](../../slide/) está vinculado. Escreva [ISlide](../../islide/).

```cpp
virtual void Aspose::Slides::IZoomFrame::set_TargetSlide(System::SharedPtr<ISlide> value)=0
```

## Observações

O próximo exemplo demonstra a alteração do slide de destino e cria uma nova imagem para o objeto Zoom [Slide](../../slide/):
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TargetSlide(pres->get_Slides()->idx_get(2));
```

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* classe [ISlide](../../islide/)
* classe [IZoomFrame](../)
* namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)