---
title: get_SpellCheck()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie une valeur indiquant si la vérification orthographique est activée pour la portion de texte. Lorsque cette propriété est définie sur false, les vérifications orthographiques des éléments de texte sont supprimées. Lorsque la propriété est définie sur true, la vérification orthographique est autorisée. La valeur par défaut est false.
type: docs
weight: 599
url: /fr/aspose.slides/baseportionformat/get_spellcheck/
---
## BasePortionFormat::get_SpellCheck() méthode


Obtient une valeur indiquant si la vérification orthographique est activée pour la portion de texte. Lorsque cette propriété est définie sur false, les vérifications orthographiques des éléments de texte sont supprimées. Lorsqu'elle est définie sur true, la vérification orthographique est autorisée. La valeur par défaut est **false**.

```cpp
bool Aspose::Slides::BasePortionFormat::get_SpellCheck() override
```

## Remarques


L'exemple suivant montre comment activer le drapeau SpellCheck avant d'enregistrer la présentation: 
```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
// Access the first portion of text inside the first shape on the first slide
auto portion = (System::ExplicitCast<AutoShape>(pres->get_Slide(0)->get_Shape(0)))->get_TextFrame()->get_Paragraph(0)->get_Portion(0);
// Enable spell checking for this text portion
portion->get_PortionFormat()->set_SpellCheck(true);
// Save the modified presentation
pres->Save(u"output-with-spellcheck.pptx", SaveFormat::Pptx);
```

## Voir aussi

* Classe [BasePortionFormat](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)