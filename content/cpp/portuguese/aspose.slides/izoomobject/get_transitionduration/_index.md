---
title: get_TransitionDuration()
second_title: Referência da API Aspose.Slides para C++
description: "Obtém a duração da transição entre Zoom e slide. Leitura float. Valor padrão: 1.0f"
type: docs
weight: 105
url: /pt/aspose.slides/izoomobject/get_transitionduration/
---
## IZoomObject::get_TransitionDuration() método


Obtém a duração da transição entre Zoom e slide. Leitura **float**. Valor padrão: 1.0f

```cpp
virtual float Aspose::Slides::IZoomObject::get_TransitionDuration()=0
```

## Observações


Se não for especificado (TransitionDur = 0), ele usará a transição do slide de destino e os tempos associados a essa transição. 

O exemplo demonstra a mudança da duração da transição entre Zoom e slide: 
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