---
title: set_TargetSlide()
second_title: Referência da API Aspose.Slides para C++
description: Define o objeto de slide ao qual o objeto Slide Zoom está vinculado. Escreva ISlide.
type: docs
weight: 14
url: /pt/aspose.slides/zoomframe/set_targetslide/
---
## ZoomFrame::set_TargetSlide(System::SharedPtr\<ISlide\>) método

Define o objeto de slide ao qual o objeto Zoom [Slide](../../slide/) está vinculado. Escreva [ISlide](../../islide/).

```cpp
void Aspose::Slides::ZoomFrame::set_TargetSlide(System::SharedPtr<ISlide> value) override
```

## Observações

O próximo exemplo demonstra a alteração do slide de destino e cria uma nova imagem para o objeto Zoom [Slide](../../slide/):
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TargetSlide(pres->get_Slides()->idx_get(2));
```

## Veja também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISlide](../../islide/)
* Classe [ZoomFrame](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)