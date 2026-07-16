---
title: Overbar()
second_title: Référence de l'API Aspose.Slides for C++
description: Place une barre au-dessus de cet élément
type: docs
weight: 222
url: /fr/aspose.slides.mathtext/imathelement/overbar/
---
## IMathElement::Overbar() méthode


Place une barre au-dessus de cet élément

```cpp
virtual System::SharedPtr<IMathBar> Aspose::Slides::MathText::IMathElement::Overbar()=0
```


### Valeur de retour

Nouvelle instance du type [IMathBar](../../imathbar/)
## Remarques



Exemple :
```cpp
auto bar = System::MakeObject<MathematicalText>(u"x")->Overbar();
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathBar](../../imathbar/)
* Classe [IMathElement](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)