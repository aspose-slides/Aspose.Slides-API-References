---
title: GetEffective()
second_title: Référence API Aspose.Slides pour C++
description: Obtient les données de formatage de paragraphe effectif avec l'héritage appliqué.
type: docs
weight: 365
url: /fr/aspose.slides/paragraphformat/geteffective/
---
## ParagraphFormat::GetEffective() méthode

Obtient les données de formatage de paragraphe effectif avec l'héritage appliqué.

```cpp
System::SharedPtr<IParagraphFormatEffectiveData> Aspose::Slides::ParagraphFormat::GetEffective() override
```

### Valeur de retour

Un [IParagraphFormatEffectiveData](../../iparagraphformateffectivedata/).
## Remarques

Cet exemple montre comment obtenir certaines propriétés de format de paragraphe effectif.
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectiveParagraphFormat = shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_ParagraphFormat()->GetEffective();

Console::WriteLine(String(u"Text alignment: ") + ObjectExt::ToString(effectiveParagraphFormat->get_Alignment()));
Console::WriteLine(String(u"Indent: ") + effectiveParagraphFormat->get_Indent());
Console::WriteLine(String(u"Bullet type: ") + ObjectExt::ToString(effectiveParagraphFormat->get_Bullet()->get_Type()));
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IParagraphFormatEffectiveData](../../iparagraphformateffectivedata/)
* Classe [ParagraphFormat](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)