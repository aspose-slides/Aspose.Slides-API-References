---
title: get_TransitionDuration()
second_title: Aspose.Slides para a referência da API C++
description: "Obtém a duração da transição entre Zoom e slide. Lê float. Valor padrão: 1.0f"
type: docs
weight: 105
url: /pt/aspose.slides/zoomobject/get_transitionduration/
---
## ZoomObject::get_TransitionDuration() método

Obtém a duração da transição entre Zoom e slide. Lê **float**. Valor padrão: 1.0f

```cpp
float Aspose::Slides::ZoomObject::get_TransitionDuration() override
```

## Observações

Se não for especificado (TransitionDur = 0), ele usará a transição do slide de destino e os tempos associados a essa transição.

o exemplo demonstra como alterar a duração da transição entre Zoom e slide:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TransitionDuration(2.5f);
```

## Veja também

* Classe [ZoomObject](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)