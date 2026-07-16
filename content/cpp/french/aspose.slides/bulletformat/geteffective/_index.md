---
title: GetEffective()
second_title: Référence API Aspose.Slides pour C++
description: Obtient les données de formatage de puces effectif avec l'héritage appliqué.
type: docs
weight: 248
url: /fr/aspose.slides/bulletformat/geteffective/
---
## BulletFormat::GetEffective() méthode

Obtient les données de formatage de puces effectif avec l'héritage appliqué.

```cpp
System::SharedPtr<IBulletFormatEffectiveData> Aspose::Slides::BulletFormat::GetEffective() override
```

### Valeur retournée

Un [IBulletFormatEffectiveData](../../ibulletformateffectivedata/).
## Remarques

Cet exemple montre comment obtenir certaines propriétés du format de puce effectif. 
```cpp
using namespace System;
using namespace Aspose::Slides;

auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<Aspose::Slides::IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectiveBulletFormat = shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_ParagraphFormat()->get_Bullet()->GetEffective();

Console::WriteLine(String(u"Bullet type: ") + ObjectExt::ToString(effectiveBulletFormat->get_Type()));
if (effectiveBulletFormat->get_Type() == Aspose::Slides::BulletType::Numbered)
{
    Console::WriteLine(String(u"Numbered style: ") + ObjectExt::ToString(effectiveBulletFormat->get_NumberedBulletStyle()));
    Console::WriteLine(String(u"Starting number: ") + effectiveBulletFormat->get_NumberedBulletStartWith());
}
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IBulletFormatEffectiveData](../../ibulletformateffectivedata/)
* Classe [BulletFormat](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)