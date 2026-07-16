---
title: get_SpellCheck()
second_title: Référence de l'API Aspose.Slides pour C++
description: Obtient une valeur indiquant si la vérification orthographique est activée pour la portion de texte. Lorsque cette propriété est définie sur false, les vérifications orthographiques pour les éléments de texte sont supprimées. Lorsqu'elle est définie sur true, la vérification orthographique est autorisée. La valeur par défaut est false.
type: docs
weight: 599
url: /fr/aspose.slides/ibaseportionformat/get_spellcheck/
---
## IBasePortionFormat::get_SpellCheck() méthode


Obtient une valeur indiquant si la vérification orthographique est activée pour la portion de texte. Lorsque cette propriété est définie sur false, les vérifications orthographiques pour les éléments de texte sont supprimées. Lorsqu'elle est définie sur true, la vérification orthographique est autorisée. La valeur par défaut est **false**.

```cpp
virtual bool Aspose::Slides::IBasePortionFormat::get_SpellCheck()=0
```

## Remarques


L'exemple suivant montre comment activer le drapeau SpellCheck avant d'enregistrer la présentation :
```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
// Accéder à la première portion de texte à l'intérieur de la première forme de la première diapositive
auto portion = (System::ExplicitCast<AutoShape>(pres->get_Slide(0)->get_Shape(0)))->get_TextFrame()->get_Paragraph(0)->get_Portion(0);
// Activer la vérification orthographique pour cette portion de texte
portion->get_PortionFormat()->set_SpellCheck(true);
// Enregistrer la présentation modifiée
pres->Save(u"output-with-spellcheck.pptx", SaveFormat::Pptx);
```

## Voir aussi

* Classe [IBasePortionFormat](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)