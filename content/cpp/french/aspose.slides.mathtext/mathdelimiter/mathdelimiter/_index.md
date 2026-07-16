---
title: MathDelimiter()
second_title: Référence de l'API Aspose.Slides pour C++
description: Initialise MathDelimiter avec l'élément spécifié comme argument de base unique
type: docs
weight: 144
url: /fr/aspose.slides.mathtext/mathdelimiter/mathdelimiter/
---
## MathDelimiter::MathDelimiter(System::SharedPtr\<IMathElement\>) constructeur


Initialise [MathDelimiter](../) avec l'élément spécifié comme argument de base unique

```cpp
Aspose::Slides::MathText::MathDelimiter::MathDelimiter(System::SharedPtr<IMathElement> element)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | L'élément de base auquel le délimiteur est appliqué. Peut être nul. |
## Remarques



Exemple : 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = System::MakeObject<MathDelimiter>(element);
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* classe [IMathElement](../../imathelement/)
* classe [MathDelimiter](../)
* espace de noms [Aspose::Slides::MathText](../../)
* bibliothèque [Aspose.Slides](../../../)