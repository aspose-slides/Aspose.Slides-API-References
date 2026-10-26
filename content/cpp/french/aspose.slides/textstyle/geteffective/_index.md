---
title: GetEffective()
second_title: Référence de l'API Aspose.Slides pour C++
description: Obtient les données de formatage du style de texte effectif avec l'héritage appliqué.
type: docs
weight: 27
url: /fr/aspose.slides/textstyle/geteffective/
---
## TextStyle::GetEffective() méthode

Obtient les données de formatage du style de texte effectif avec l'héritage appliqué.

```cpp
System::SharedPtr<ITextStyleEffectiveData> Aspose::Slides::TextStyle::GetEffective() override
```

### Valeur de retour

Un [ITextStyleEffectiveData](../../itextstyleeffectivedata/).
## Remarques

Cet exemple montre comment obtenir certaines des propriétés du style de texte effectif.
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectiveTextStyle = shape->get_TextFrame()->get_TextFrameFormat()->get_TextStyle()->GetEffective();

for (int32_t i = 0; i <= 8; i++)
{
    auto effectiveStyleLevel = effectiveTextStyle->GetLevel(i);
    Console::WriteLine(String(u"= Effective paragraph formatting for style level #") + i + u" =");

    Console::WriteLine(String(u"Depth: ") + effectiveStyleLevel->get_Depth());
    Console::WriteLine(String(u"Indent: ") + effectiveStyleLevel->get_Indent());
    Console::WriteLine(String(u"Alignment: ") + ObjectExt::ToString(effectiveStyleLevel->get_Alignment()));
    Console::WriteLine(String(u"Font alignment: ") + ObjectExt::ToString(effectiveStyleLevel->get_FontAlignment()));
}
```

## Voir également

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ITextStyleEffectiveData](../../itextstyleeffectivedata/)
* Class [TextStyle](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)