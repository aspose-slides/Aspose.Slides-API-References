---
title: set_SpellCheck()
second_title: Référence de l'API Aspose.Slides pour C++
description: Définit une valeur indiquant si la vérification orthographique est activée pour la partie de texte. Lorsque cette propriété est définie sur false, les vérifications orthographiques des éléments de texte sont supprimées. Lorsqu'elle est définie sur true, la vérification orthographique est autorisée. La valeur par défaut est false.
type: docs
weight: 612
url: /fr/aspose.slides/baseportionformat/set_spellcheck/
---
## BasePortionFormat::set_SpellCheck(bool) méthode

Définit une valeur indiquant si la vérification orthographique est activée pour la partie de texte. Lorsque cette propriété est définie sur false, les vérifications orthographiques des éléments de texte sont supprimées. Lorsqu'elle est définie sur true, la vérification orthographique est autorisée. La valeur par défaut est **false**.

```cpp
void Aspose::Slides::BasePortionFormat::set_SpellCheck(bool value) override
```

## Remarques

L'exemple suivant montre comment activer le drapeau SpellCheck avant d'enregistrer la présentation :
```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
// Accéder à la première portion de texte à l'intérieur de la première forme sur la première diapositive
auto portion = (System::ExplicitCast<AutoShape>(pres->get_Slide(0)->get_Shape(0)))->get_TextFrame()->get_Paragraph(0)->get_Portion(0);
// Activer la vérification orthographique pour cette portion de texte
portion->get_PortionFormat()->set_SpellCheck(true);
// Enregistrer la présentation modifiée
pres->Save(u"output-with-spellcheck.pptx", SaveFormat::Pptx);
```

## Voir aussi

* Classe [BasePortionFormat](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)