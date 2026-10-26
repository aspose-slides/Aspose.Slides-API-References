---
title: get_MasterTheme()
second_title: Aspose.Slides para C++ Referência da API
description: "Retorna o tema mestre. Somente leitura Theme::IMasterTheme."
type: docs
weight: 404
url: /pt/aspose.slides/presentation/get_mastertheme/
---
## Presentation::get_MasterTheme() método

Retorna o tema mestre. Somente leitura [Theme::IMasterTheme](../../../aspose.slides.theme/imastertheme/).

```cpp
System::SharedPtr<Theme::IMasterTheme> Aspose::Slides::Presentation::get_MasterTheme() override
```

## Observações

Os exemplos a seguir mostram como alterar o efeito de um tema modificando partes dos elementos do PowerPoint [Presentation](../).
```cpp
// Instanciar um objeto de apresentação que representa um arquivo de apresentação
auto pres = System::MakeObject<Presentation>(u"Subtle_Moderate_Intense.pptx");
auto masterTheme = pres->get_MasterTheme();
auto formatScheme = masterTheme->get_FormatScheme();

formatScheme->get_LineStyles()->idx_get(0)->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Red());
formatScheme->get_FillStyles()->idx_get(2)->set_FillType(FillType::Solid);
formatScheme->get_FillStyles()->idx_get(2)->get_SolidFillColor()->set_Color(System::Drawing::Color::get_ForestGreen());
formatScheme->get_EffectStyles()->idx_get(2)->get_EffectFormat()->get_OuterShadowEffect()->set_Distance(10.0f);
pres->Save(u"Design_04_Subtle_Moderate_Intense-out.pptx", SaveFormat::Pptx);
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMasterTheme](../../../aspose.slides.theme/imastertheme/)
* Classe [Presentation](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)