---
title: SetSubSuperscriptOnTheLeft()
second_title: Référence API Aspose.Slides pour C++
description: Crée un indice et un exposant à gauche
type: docs
weight: 105
url: /fr/aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft/
---
## MathElementBase::SetSubSuperscriptOnTheLeft(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) méthode


Crée un indice et un exposant à gauche

```cpp
System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheLeft(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Indice (indice inférieur à gauche) |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Exposant (indice supérieur à gauche) |

### Valeur de retour

Nouvel élément mathématique du type [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
## Remarques



Exemple : 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto leftSubsuperscript = baseElement->SetSubSuperscriptOnTheLeft(subscript, superscript);
```

## MathElementBase::SetSubSuperscriptOnTheLeft(System::String, System::String) méthode


Crée un indice et un exposant à gauche

```cpp
System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheLeft(System::String subscript, System::String superscript) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | Indice (indice inférieur à gauche) |
| superscript | [System::String](../../../system/string/) | Exposant (indice supérieur à gauche) |

### Valeur de retour

Nouvel élément mathématique du type [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
## Remarques



Exemple : 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto leftSubsuperscript = baseElement->SetSubSuperscriptOnTheLeft(u"i", u"j");
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathElementBase](../)
* Classe [String](../../../system/string/)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)