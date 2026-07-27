---
title: get_MasterTheme()
second_title: Referencia de la API de Aspose.Slides para C++
description: "Devuelve el tema maestro. Sólo lectura Theme::IMasterTheme."
type: docs
weight: 404
url: /es/aspose.slides/presentation/get_mastertheme/
---
## Presentation::get_MasterTheme() método

Devuelve el tema maestro. Sólo lectura [Theme::IMasterTheme](../../../aspose.slides.theme/imastertheme/).

```cpp
System::SharedPtr<Theme::IMasterTheme> Aspose::Slides::Presentation::get_MasterTheme() override
```

## Observaciones

Los siguientes ejemplos muestran cómo cambiar un efecto de tema modificando partes de los elementos de PowerPoint [Presentation](../).
```cpp
// Instanciar un objeto de presentación que representa un archivo de presentación
auto pres = System::MakeObject<Presentation>(u"Subtle_Moderate_Intense.pptx");
auto masterTheme = pres->get_MasterTheme();
auto formatScheme = masterTheme->get_FormatScheme();

formatScheme->get_LineStyles()->idx_get(0)->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Red());
formatScheme->get_FillStyles()->idx_get(2)->set_FillType(FillType::Solid);
formatScheme->get_FillStyles()->idx_get(2)->get_SolidFillColor()->set_Color(System::Drawing::Color::get_ForestGreen());
formatScheme->get_EffectStyles()->idx_get(2)->get_EffectFormat()->get_OuterShadowEffect()->set_Distance(10.0f);
pres->Save(u"Design_04_Subtle_Moderate_Intense-out.pptx", SaveFormat::Pptx);
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IMasterTheme](../../../aspose.slides.theme/imastertheme/)
* Clase [Presentation](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)