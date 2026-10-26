---
title: GetEffective()
second_title: Référence de l'API Aspose.Slides pour C++
description: Obtient les données de thème effectives avec l'héritage appliqué.
type: docs
weight: 53
url: /fr/aspose.slides.theme/theme/geteffective/
---
## Theme::GetEffective() méthode


Obtient les données de thème effectives avec l'héritage appliqué.

```cpp
System::SharedPtr<IThemeEffectiveData> Aspose::Slides::Theme::Theme::GetEffective() override
```


### Valeur de retour

A [IThemeEffectiveData](../../ithemeeffectivedata/).
## Remarques



Cet exemple montre l'obtention des propriétés de thème effectives. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto effectiveTheme = pres->get_Slides()->idx_get(0)->get_ThemeManager()->get_OverrideTheme()->GetEffective();

Console::WriteLine(String(u"Font scheme name: ") + effectiveTheme->get_FontScheme()->get_Name());
Console::WriteLine(String(u"Major latin font: ") + effectiveTheme->get_FontScheme()->get_Major()->get_LatinFont()->get_FontName());
Console::WriteLine(String(u"Minor latin font: ") + effectiveTheme->get_FontScheme()->get_Minor()->get_LatinFont()->get_FontName());
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IThemeEffectiveData](../../ithemeeffectivedata/)
* Classe [Theme](../)
* Espace de noms [Aspose::Slides::Theme](../../)
* Bibliothèque [Aspose.Slides](../../../)