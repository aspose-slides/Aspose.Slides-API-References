---
title: GetEffective()
second_title: Référence API Aspose.Slides pour C++
description: Récupère les données de formatage effectif du cadre de texte avec l'héritage appliqué.
type: docs
weight: 391
url: /fr/aspose.slides/textframeformat/geteffective/
---
## TextFrameFormat::GetEffective() méthode

Récupère les données de formatage effectif du cadre de texte avec l'héritage appliqué.

```cpp
System::SharedPtr<ITextFrameFormatEffectiveData> Aspose::Slides::TextFrameFormat::GetEffective() override
```

### Valeur de retour

A [ITextFrameFormatEffectiveData](../../itextframeformateffectivedata/).

## Remarques

Cet exemple montre comment obtenir certaines des propriétés de formatage effectif du cadre de texte. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectiveTextFrameFormat = shape->get_TextFrame()->get_TextFrameFormat()->GetEffective();

Console::WriteLine(String(u"Anchoring type: ") + ObjectExt::ToString(effectiveTextFrameFormat->get_AnchoringType()));
Console::WriteLine(String(u"Autofit type: ") + ObjectExt::ToString(effectiveTextFrameFormat->get_AutofitType()));
Console::WriteLine(String(u"Text vertical type: ") + ObjectExt::ToString(effectiveTextFrameFormat->get_TextVerticalType()));
Console::WriteLine(u"Margins");
Console::WriteLine(String(u"   Left: ") + effectiveTextFrameFormat->get_MarginLeft());
Console::WriteLine(String(u"   Top: ") + effectiveTextFrameFormat->get_MarginTop());
Console::WriteLine(String(u"   Right: ") + effectiveTextFrameFormat->get_MarginRight());
Console::WriteLine(String(u"   Bottom: ") + effectiveTextFrameFormat->get_MarginBottom());
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ITextFrameFormatEffectiveData](../../itextframeformateffectivedata/)
* Classe [TextFrameFormat](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)