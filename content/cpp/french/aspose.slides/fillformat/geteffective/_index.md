---
title: GetEffective()
second_title: Référence de l'API Aspose.Slides pour C++
description: Obtient les données de mise en forme de remplissage effectives avec l'héritage appliqué.
type: docs
weight: 105
url: /fr/aspose.slides/fillformat/geteffective/
---
## FillFormat::GetEffective() méthode


Obtient les données de formatage de remplissage effectives avec l'héritage appliqué.

```cpp
System::SharedPtr<IFillFormatEffectiveData> Aspose::Slides::FillFormat::GetEffective() override
```


### Valeur de retour

Un [IFillFormatEffectiveData](../../ifillformateffectivedata/).
## Remarques



Cet exemple montre comment obtenir les propriétés de format de remplissage effectif d'une forme. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto effectiveFillFormat = pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_FillFormat()->GetEffective();

Console::WriteLine(String(u"Type: ") + ObjectExt::ToString(effectiveFillFormat->get_FillType()));
switch (effectiveFillFormat->get_FillType())
{
    case FillType::Solid:
        Console::WriteLine(String(u"Fill color: ") + effectiveFillFormat->get_SolidFillColor());
        break;

    case FillType::Pattern:
        Console::WriteLine(String(u"Pattern style: ") + ObjectExt::ToString(effectiveFillFormat->get_PatternFormat()->get_PatternStyle()));
        Console::WriteLine(String(u"Fore color: ") + effectiveFillFormat->get_PatternFormat()->get_ForeColor());
        Console::WriteLine(String(u"Back color: ") + effectiveFillFormat->get_PatternFormat()->get_BackColor());
        break;

    case FillType::Gradient:
        Console::WriteLine(String(u"Gradient direction: ") + ObjectExt::ToString(effectiveFillFormat->get_GradientFormat()->get_GradientDirection()));
        Console::WriteLine(String(u"Gradient stops count: ") + effectiveFillFormat->get_GradientFormat()->get_GradientStops()->get_Count());
        break;

    case FillType::Picture:
        Console::WriteLine(String(u"Picture width: ") + effectiveFillFormat->get_PictureFillFormat()->get_Picture()->get_Image()->get_Width());
        Console::WriteLine(String(u"Picture height: ") + effectiveFillFormat->get_PictureFillFormat()->get_Picture()->get_Image()->get_Height());
        break;

    default:
        break;
}
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IFillFormatEffectiveData](../../ifillformateffectivedata/)
* Classe [FillFormat](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)