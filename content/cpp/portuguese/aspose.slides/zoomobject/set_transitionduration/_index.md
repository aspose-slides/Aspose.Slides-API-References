---
title: set_TransitionDuration()
second_title: Referência da API Aspose.Slides para C++
description: "Define a duração da transição entre Zoom e slide. Escreva float. Valor padrão: 1.0f"
type: docs
weight: 118
url: /pt/aspose.slides/zoomobject/set_transitionduration/
---
## ZoomObject::set_TransitionDuration(float) método

Define a duração da transição entre Zoom e slide. Escreva **float**. Valor padrão: 1.0f

```cpp
void Aspose::Slides::ZoomObject::set_TransitionDuration(float value) override
```

## Observações

Se não for especificado (TransitionDur = 0), será usada a transição do slide de destino e os tempos associados a essa transição.  

O exemplo demonstra como alterar a duração da transição entre Zoom e slide: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TransitionDuration(2.5f);
```

## Veja Também

* Classe [ZoomObject](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)