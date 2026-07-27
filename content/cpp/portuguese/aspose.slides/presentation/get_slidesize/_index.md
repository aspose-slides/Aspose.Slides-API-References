---
title: get_SlideSize()
second_title: Referência da API Aspose.Slides para C++
description: Retorna o objeto de tamanho de slide. Somente leitura ISlideSize.
type: docs
weight: 79
url: /pt/aspose.slides/presentation/get_slidesize/
---
## Presentation::get_SlideSize() método


Retorna o objeto de tamanho de slide. Somente leitura [ISlideSize](../../islidesize/).

```cpp
System::SharedPtr<ISlideSize> Aspose::Slides::Presentation::get_SlideSize() override
```

## Observações


O exemplo a seguir mostra como alterar o tamanho do slide em um PowerPoint [Presentation](../).
```cpp
auto pres = System::MakeObject<Presentation>(u"pres-4x3-aspect-ratio.pptx");

pres->get_SlideSize()->SetSize(SlideSizeType::OnScreen16x9, SlideSizeScaleType::DoNotScale);
pres->Save(u"pres-4x3-aspect-ratio.pptx", SaveFormat::Pptx);
```
 O exemplo a seguir mostra como definir o tamanho do slide em relação ao dimensionamento de conteúdo para um PowerPoint [Presentation](../).
```cpp
// Instancia um objeto Presentation que representa um arquivo de apresentação
auto presentation = System::MakeObject<Presentation>(u"AccessSlides.pptx");
auto auxPresentation = System::MakeObject<Presentation>();
auto slide = presentation->get_Slides()->idx_get(0);

// Define o tamanho do slide das apresentações geradas para o mesmo do original
presentation->get_SlideSize()->SetSize(540.0f, 720.0f, SlideSizeScaleType::EnsureFit);

// O método SetSize é usado para definir o tamanho do slide com escala de conteúdo para garantir o ajuste
presentation->get_SlideSize()->SetSize(SlideSizeType::A4Paper, SlideSizeScaleType::Maximize);

// O método SetSize é usado para definir o tamanho do slide maximizando o tamanho do conteúdo
// Salva a apresentação no disco
auxPresentation->Save(u"Set_Size_Type_out.pptx", SaveFormat::Pptx);
```
 O exemplo a seguir mostra como especificar tamanhos de slide personalizados em um PowerPoint [Presentation](../).
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
pres->get_SlideSize()->SetSize(780.0f, 540.0f, SlideSizeScaleType::DoNotScale);

// Tamanho de papel A4
pres->Save(u"pres-a4-slide-size.pptx", SaveFormat::Pptx);
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISlideSize](../../islidesize/)
* Classe [Presentation](../)
* Espaço de nomes [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)