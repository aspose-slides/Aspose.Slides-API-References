---
title: get_HideDegree()
second_title: Référence de l'API Aspose.Slides pour C++
description: Masquer le degré. Lorsque la valeur est vraie, le degré n'est pas affiché, comme dans \\u221A\\uD835\\uDC65
type: docs
weight: 27
url: /fr/aspose.slides.mathtext/mathradical/get_hidedegree/
---
## MathRadical::get_HideDegree() méthode

Masquer le degré. Lorsque la valeur est vraie, le degré n'est pas affiché, comme dans \\u221A\\uD835\\uDC65

```cpp
bool Aspose::Slides::MathText::MathRadical::get_HideDegree() override
```

## Remarques


Exemple:
```cpp
auto radical = System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3"));
radical->set_HideDegree(true);
```

## Voir aussi

* Classe [MathRadical](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)