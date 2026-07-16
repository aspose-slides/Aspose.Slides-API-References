---
title: SetSubSuperscriptOnTheRight()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée un indice et un exposant à droite
type: docs
weight: 105
url: /fr/aspose.slides.mathtext/imathelement/setsubsuperscriptontheright/
---
## IMathElement::SetSubSuperscriptOnTheRight(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) méthode


Crée un indice et un exposant à droite

```cpp
virtual System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSubSuperscriptOnTheRight(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Subscript (lower index on the right) |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Superscript (upper index on the right) |

### Valeur de retour

New math element of type [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
## Remarques



Exemple: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = baseElement->SetSubSuperscriptOnTheRight(subscript, superscript);
```

## IMathElement::SetSubSuperscriptOnTheRight(System::String, System::String) méthode


Crée un indice et un exposant à droite

```cpp
virtual System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSubSuperscriptOnTheRight(System::String subscript, System::String superscript)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | Subscript (lower index on the right) |
| superscript | [System::String](../../../system/string/) | Superscript (upper index on the right) |

### Valeur de retour

New math element of type [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
## Remarques



Exemple: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subsuperscript = baseElement->SetSubSuperscriptOnTheRight(u"i", u"j");
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
* Classe [IMathElement](../)
* Classe [String](../../../system/string/)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)