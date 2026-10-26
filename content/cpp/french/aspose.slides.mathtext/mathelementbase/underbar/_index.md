---
title: Underbar()
second_title: Référence de l'API Aspose.Slides pour C++
description: Définit une barre au bas de cet élément
type: docs
weight: 222
url: /fr/aspose.slides.mathtext/mathelementbase/underbar/
---
## MathElementBase::Underbar() méthode

Définit une barre en bas de cet élément

```cpp
System::SharedPtr<IMathBar> Aspose::Slides::MathText::MathElementBase::Underbar() override
```

### Valeur de retour

Nouvelle instance du type [IMathBar](../../imathbar/)
## Remarques



Exemple :
```cpp
auto bar = System::MakeObject<MathematicalText>(u"x")->Underbar();
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* classe [IMathBar](../../imathbar/)
* classe [MathElementBase](../)
* espace de noms [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)