---
title: get_Slides()
second_title: Referência da API Aspose.Slides para C++
description: Retorna uma lista de todos os slides que estão definidos na apresentação. Somente leitura ISlideCollection.
type: docs
weight: 53
url: /pt/aspose.slides/presentation/get_slides/
---
## Presentation::get_Slides() method


Retorna uma lista de todos os slides que estão definidos na apresentação. Somente leitura [ISlideCollection](../../islidecollection/).

```cpp
System::SharedPtr<ISlideCollection> Aspose::Slides::Presentation::get_Slides() override
```

## Observações


O exemplo a seguir mostra como definir a cor de fundo dos slides do PowerPoint [Presentation](../). 
```cpp
// Instanciar a classe Presentation que representa o arquivo de apresentação
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

// Definir a cor de fundo do primeiro ISlide como Azul
slide->get_Background()->set_Type(BackgroundType::OwnBackground);
slide->get_Background()->get_FillFormat()->set_FillType(FillType::Solid);
slide->get_Background()->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Blue());
pres->Save(u"ContentBG_out.pptx", SaveFormat::Pptx);
```
 O exemplo a seguir mostra como definir a imagem de fundo dos slides do PowerPoint [Presentation](../). 
```cpp
// Instanciar a classe Presentation que representa o arquivo de apresentação
auto pres = System::MakeObject<Presentation>(u"SetImageAsBackground.pptx");
auto slide = pres->get_Slides()->idx_get(0);

// Definir o fundo com Imagem
slide->get_Background()->set_Type(BackgroundType::OwnBackground);
slide->get_Background()->get_FillFormat()->set_FillType(FillType::Picture);
slide->get_Background()->get_FillFormat()->get_PictureFillFormat()->set_PictureFillMode(PictureFillMode::Stretch);
// Definir a imagem
auto img = System::ExplicitCast<System::Drawing::Image>(System::MakeObject<System::Drawing::Bitmap>(dataDir + u"Tulips.jpg"));
// Adicionar imagem à coleção de imagens da apresentação
auto imgx = pres->get_Images()->AddImage(img);
slide->get_Background()->get_FillFormat()->get_PictureFillFormat()->get_Picture()->set_Image(imgx);
// Gravar a apresentação no disco
pres->Save(u"ContentBG_Img_out.pptx", SaveFormat::Pptx);
```
 O exemplo a seguir mostra como adicionar transição de slide [Presentation](../). 
```cpp
// Instanciar a classe Presentation para carregar o arquivo de apresentação de origem
auto presentation = System::MakeObject<Presentation>(u"AccessSlides.pptx");

// Aplicar transição do tipo círculo no slide 1
presentation->get_Slides()->idx_get(0)->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Circle);
// Aplicar transição do tipo pente no slide 2
presentation->get_Slides()->idx_get(1)->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Comb);
// Gravar a apresentação no disco
presentation->Save(u"SampleTransition_out.pptx", SaveFormat::Pptx);
```
 O exemplo a seguir mostra como adicionar transição de slide avançada. 
```cpp
// Instanciar a classe Presentation que representa um arquivo de apresentação
auto pres = System::MakeObject<Presentation>(u"BetterSlideTransitions.pptx");

auto slide1 = pres->get_Slides()->idx_get(0);
auto slide2 = pres->get_Slides()->idx_get(1);
auto slide3 = pres->get_Slides()->idx_get(2);

// Aplicar transição do tipo círculo no slide 1
slide1->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Circle);
// Definir o tempo de transição de 3 segundos
slide1->get_SlideShowTransition()->set_AdvanceOnClick(true);
slide1->get_SlideShowTransition()->set_AdvanceAfterTime(3000);
// Aplicar transição do tipo pente no slide 2
slide2->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Comb);
// Definir o tempo de transição de 5 segundos
slide2->get_SlideShowTransition()->set_AdvanceOnClick(true);
slide2->get_SlideShowTransition()->set_AdvanceAfterTime(5000);
// Aplicar transição do tipo zoom no slide 3
slide3->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Zoom);
// Definir o tempo de transição de 7 segundos
slide3->get_SlideShowTransition()->set_AdvanceOnClick(true);
slide3->get_SlideShowTransition()->set_AdvanceAfterTime(7000);
// Gravar a apresentação no disco
pres->Save(u"SampleTransition_out.pptx", SaveFormat::Pptx);
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISlideCollection](../../islidecollection/)
* Classe [Presentation](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)