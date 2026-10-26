---
title: SetSuperscript()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée un exposant
type: docs
weight: 92
url: /fr/aspose.slides.mathtext/imathelement/setsuperscript/
---
## IMathElement::SetSuperscript(System::SharedPtr\<IMathElement\>) méthode


Crée un exposant

```cpp
virtual System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSuperscript(System::SharedPtr<IMathElement> superscript)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Exposant (indice supérieur à droite) |

### Valeur de retour

Nouvel élément mathématique de type [IMathSuperscriptElement](../../imathsuperscriptelement/)
## Remarques



Exemple :
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"4");
auto superscript = element->SetSuperscript(index);
```

## IMathElement::SetSuperscript(System::String) méthode


Crée un exposant

```cpp
virtual System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSuperscript(System::String superscript)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| superscript | [System::String](../../../system/string/) | Exposant (indice supérieur à droite) |

### Valeur de retour

Nouvel élément mathématique de type [IMathSuperscriptElement](../../imathsuperscriptelement/)
## Remarques



Exemple :
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto superscript = element->SetSuperscript(u"4");
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathSuperscriptElement](../../imathsuperscriptelement/)
* Classe [IMathElement](../)
* Classe [String](../../../system/string/)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)