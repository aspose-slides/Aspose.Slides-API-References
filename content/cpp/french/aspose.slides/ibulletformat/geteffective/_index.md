---
title: GetEffective()
second_title: Aspose.Slides pour C++ Référence de l'API
description: Obtient les données de formatage de puces effectives avec l'héritage appliqué.
type: docs
weight: 248
url: /fr/aspose.slides/ibulletformat/geteffective/
---
## IBulletFormat::GetEffective() method


Obtient les données de formatage de puces effectives avec l'héritage appliqué.

```cpp
virtual System::SharedPtr<IBulletFormatEffectiveData> Aspose::Slides::IBulletFormat::GetEffective()=0
```


### Valeur de retour

Un [IBulletFormatEffectiveData](../../ibulletformateffectivedata/).
## Remarques



Cet exemple montre comment obtenir certaines propriétés de format de puce effectives. 
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
* Classe [IBulletFormat](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)