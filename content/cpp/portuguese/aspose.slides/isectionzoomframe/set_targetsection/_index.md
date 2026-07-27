---
title: set_TargetSection()
second_title: Referência da API Aspose.Slides para C++
description: Define o objeto de seção ao qual o objeto Section Zoom está ligado. Escreva ISection.
type: docs
weight: 14
url: /pt/aspose.slides/isectionzoomframe/set_targetsection/
---
## ISectionZoomFrame::set_TargetSection(System::SharedPtr\<ISection\>) método

Define o objeto de seção ao qual o objeto Zoom [Section](../../section/) está ligado. Escreva [ISection](../../isection/).

```cpp
virtual void Aspose::Slides::ISectionZoomFrame::set_TargetSection(System::SharedPtr<ISection> value)=0
```

## Observações

Este exemplo demonstra a alteração da seção de destino e cria uma nova imagem para o objeto de zoom da seção: 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto sectionZoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
sectionZoomFrame->set_TargetSection(pres->get_Sections()->idx_get(2));
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISection](../../isection/)
* Classe [ISectionZoomFrame](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)