---
title: set_TransitionDuration()
second_title: Aspose.Slides para C++ Referência da API
description: "Define a duração da transição entre Zoom e slide. Escreva float. Valor padrão: 1.0f"
type: docs
weight: 118
url: /pt/aspose.slides/izoomobject/set_transitionduration/
---
## IZoomObject::set_TransitionDuration(float) método

Define a duração da transição entre Zoom e slide. Escreva **float**. Valor padrão: 1.0f

```cpp
virtual void Aspose::Slides::IZoomObject::set_TransitionDuration(float value)=0
```

## Observações

Se não for especificado (TransitionDur = 0), será usado a transição do slide de destino e os tempos associados a essa transição. 

O exemplo demonstra a alteração da duração da transição entre Zoom e slide: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TransitionDuration(2.5f);
```

## Ver também

* Classe [IZoomObject](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)