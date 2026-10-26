---
title: GetEffective()
second_title: Référence de l'API Aspose.Slides pour C++
description: Obtient les données de formatage de portion effectif avec l'héritage appliqué.
type: docs
weight: 131
url: /fr/aspose.slides/portionformat/geteffective/
---
## PortionFormat::GetEffective() méthode


Obtient les données de formatage de portion effectif avec l'héritage appliqué.

```cpp
System::SharedPtr<IPortionFormatEffectiveData> Aspose::Slides::PortionFormat::GetEffective() override
```


### Valeur de retour

A [IPortionFormatEffectiveData](../../iportionformateffectivedata/).
## Remarques



Cet exemple montre comment obtenir certaines propriétés de format de portion effectif. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectivePortionFormat = shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)->get_PortionFormat()->GetEffective();

Console::WriteLine(String(u"Latin font: ") + effectivePortionFormat->get_LatinFont()->get_FontName());
Console::WriteLine(String(u"Font height: ") + effectivePortionFormat->get_FontHeight());
Console::WriteLine(String(u"Fill type: ") + ObjectExt::ToString(effectivePortionFormat->get_FillFormat()->get_FillType()));
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IPortionFormatEffectiveData](../../iportionformateffectivedata/)
* Classe [PortionFormat](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)