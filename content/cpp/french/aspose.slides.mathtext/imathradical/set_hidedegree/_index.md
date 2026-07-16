---
title: set_HideDegree()
second_title: Référence de l'API Aspose.Slides pour C++
description: Masquer le degré. Lorsque la valeur est vraie, le degré n'est pas affiché, comme dans \\u221A\\uD835\\uDC65
type: docs
weight: 40
url: /fr/aspose.slides.mathtext/imathradical/set_hidedegree/
---
## IMathRadical::set_HideDegree(bool) méthode

Masquer le degré. Lorsque la valeur est vraie, le degré n'est pas affiché, comme dans \\u221A\\uD835\\uDC65

```cpp
virtual void Aspose::Slides::MathText::IMathRadical::set_HideDegree(bool value)=0
```

## Remarques

Exemple:
```cpp
auto radical = System::MakeObject<MathematicalText>(u"x")->Radical(u"3"); // racine cubique
radical->set_HideDegree(true);
```

## Voir aussi

* Classe [IMathRadical](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)