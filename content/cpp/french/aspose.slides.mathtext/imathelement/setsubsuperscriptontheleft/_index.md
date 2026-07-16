---
title: SetSubSuperscriptOnTheLeft()
second_title: Référence API Aspose.Slides pour C++
description: Crée un indice et un exposant à gauche
type: docs
weight: 118
url: /fr/aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft/
---
## IMathElement::SetSubSuperscriptOnTheLeft(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) méthode

Crée un indice et un exposant à gauche

```cpp
virtual System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSubSuperscriptOnTheLeft(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript)=0
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Indice (indice inférieur à gauche) |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Exposant (indice supérieur à gauche) |

### Valeur de retour

New math element of type [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)

## Remarques



Example: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto leftSubsuperscript = baseElement->SetSubSuperscriptOnTheLeft(subscript, superscript);
```

## IMathElement::SetSubSuperscriptOnTheLeft(System::String, System::String) méthode

Crée un indice et un exposant à gauche

```cpp
virtual System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSubSuperscriptOnTheLeft(System::String subscript, System::String superscript)=0
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | Indice (indice inférieur à gauche) |
| superscript | [System::String](../../../system/string/) | Exposant (indice supérieur à gauche) |

### Valeur de retour

New math element of type [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)

## Remarques



Example: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto leftSubsuperscript = baseElement->SetSubSuperscriptOnTheLeft(u"i", u"j");
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
* Classe [IMathElement](../)
* Classe [String](../../../system/string/)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)