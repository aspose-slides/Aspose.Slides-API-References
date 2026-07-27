---
title: get_Masters()
second_title: Aspose.Slides para C++ – Referência da API
description: Retorna uma lista de todos os slides mestre que são definidos na apresentação. Somente leitura IMasterSlideCollection.
type: docs
weight: 118
url: /pt/aspose.slides/presentation/get_masters/
---
## Presentation::get_Masters() método

Retorna uma lista de todos os slides mestre que são definidos na apresentação. Somente leitura [IMasterSlideCollection](../../imasterslidecollection/).

```cpp
System::SharedPtr<IMasterSlideCollection> Aspose::Slides::Presentation::get_Masters() override
```

## Observações

Os exemplos a seguir mostram como adicionar [Images](../../images/) ao Mestre [Slides](../../) do PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);
auto masterSlide = slide->get_LayoutSlide()->get_MasterSlide();

auto image = pres->get_Images()->AddImage(System::IO::File::ReadAllBytes(u"image.png"));
masterSlide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
pres->Save(u"pres.pptx", SaveFormat::Pptx);
```
 Os exemplos a seguir mostram como alterar a cor de fundo do slide mestre do PowerPoint [Presentation](../). 
```cpp
// Instanciar a classe Presentation que representa o arquivo de apresentação
auto pres = System::MakeObject<Presentation>();

// Definir a cor de fundo do Master ISlide para Verde Floresta
auto masterSlide = pres->get_Masters()->idx_get(0);
auto background = masterSlide->get_Background();
background->set_Type(BackgroundType::OwnBackground);
background->get_FillFormat()->set_FillType(FillType::Solid);
background->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_ForestGreen());
// Gravar a apresentação no disco
pres->Save(u"SetSlideBackgroundMaster_out.pptx", SaveFormat::Pptx);
```
 Os exemplos a seguir mostram como adicionar layout de slide ao PowerPoint [Presentation](../). 
```cpp
// Instanciar a classe Presentation que representa o arquivo de apresentação
auto presentation = System::MakeObject<Presentation>(u"AccessSlides.pptx");

// Tentar procurar pelo tipo de slide de layout
auto layoutSlides = presentation->get_Masters()->idx_get(0)->get_LayoutSlides();
auto layoutSlide = System::ObjectExt::Coalesce(
    layoutSlides->GetByType(SlideLayoutType::TitleAndObject),
    [&](){ return layoutSlides->GetByType(SlideLayoutType::Title); });

if (layoutSlide == nullptr)
{
    // Situação em que uma apresentação não contém certos tipos de layouts.
    // O arquivo de apresentação contém apenas tipos de layout Blank e Custom.
    // Mas slides de layout com tipos Custom têm nomes de slide diferentes,
    // como "Title", "Title and Content", etc. E é possível usar esses
    // nomes para a seleção de slide de layout.
    // Também é possível usar o conjunto de tipos de formas de placeholder. Por exemplo,
    // O slide de título deve ter apenas o tipo de placeholder Title, etc.
    for (auto&& titleAndObjectLayoutSlide : layoutSlides)
    {
        if (titleAndObjectLayoutSlide->get_Name() == u"Title and Object")
        {
            layoutSlide = titleAndObjectLayoutSlide;
            break;
        }
    }

    if (layoutSlide == nullptr)
    {
        for (auto&& titleLayoutSlide : layoutSlides)
        {
            if (titleLayoutSlide->get_Name() == u"Title")
            {
                layoutSlide = titleLayoutSlide;
                break;
            }
        }

        if (layoutSlide == nullptr)
        {
            layoutSlide = layoutSlides->GetByType(SlideLayoutType::Blank);
            if (layoutSlide == nullptr)
            {
                layoutSlide = layoutSlides->Add(SlideLayoutType::TitleAndObject, u"Title and Object");
            }
        }
    }
}

// Adicionando slide vazio com o slide de layout adicionado
presentation->get_Slides()->InsertEmptySlide(0, layoutSlide);
// Salvar apresentação
presentation->Save(u"AddLayoutSlides_out.pptx", SaveFormat::Pptx);
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMasterSlideCollection](../../imasterslidecollection/)
* Classe [Presentation](../)
* Espaço de nomes [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)