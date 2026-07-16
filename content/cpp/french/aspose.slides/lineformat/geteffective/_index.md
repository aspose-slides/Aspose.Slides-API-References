---
title: GetEffective()
second_title: Référence API Aspose.Slides pour C++
description: Obtient les données de format de ligne effectives avec l'héritage appliqué.
type: docs
weight: 417
url: /fr/aspose.slides/lineformat/geteffective/
---
## LineFormat::GetEffective() méthode

Obtient les données de format de ligne effectives avec l'héritage appliqué.

```cpp
System::SharedPtr<ILineFormatEffectiveData> Aspose::Slides::LineFormat::GetEffective() override
```

### Valeur de retour

Un [ILineFormatEffectiveData](../../ilineformateffectivedata/).

## Remarques

Cet exemple montre comment obtenir les propriétés de format de ligne effectif d'une forme. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto effectiveLineFormat = pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_LineFormat()->GetEffective();

Console::WriteLine(String(u"Style: ") + ObjectExt::ToString(effectiveLineFormat->get_Style()));
Console::WriteLine(String(u"Width: ") + effectiveLineFormat->get_Width());
Console::WriteLine(String(u"Fill type: ") + ObjectExt::ToString(effectiveLineFormat->get_FillFormat()->get_FillType()));
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ILineFormatEffectiveData](../../ilineformateffectivedata/)
* Classe [LineFormat](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)