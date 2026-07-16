---
title: SetSubSuperscriptOnTheRight()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée l'indice inférieur et l'indice supérieur à droite
type: docs
weight: 92
url: /fr/aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright/
---
## MathElementBase::SetSubSuperscriptOnTheRight(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) méthode


Crée l'indice inférieur et l'indice supérieur à droite

```cpp
System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheRight(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Indice inférieur (indice inférieur à droite) |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Indice supérieur (indice supérieur à droite) |

### Valeur de retour

Nouvel élément mathématique de type [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
## Remarques



Exemple : 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = baseElement->SetSubSuperscriptOnTheRight(subscript, superscript);
```

## MathElementBase::SetSubSuperscriptOnTheRight(System::String, System::String) méthode


Crée l'indice inférieur et l'indice supérieur à droite

```cpp
System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheRight(System::String subscript, System::String superscript) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | Indice inférieur (indice inférieur à droite) |
| superscript | [System::String](../../../system/string/) | Indice supérieur (indice supérieur à droite) |

### Valeur de retour

Nouvel élément mathématique de type [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
## Remarques



Exemple : 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subsuperscript = baseElement->SetSubSuperscriptOnTheRight(u"i", u"j");
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathElementBase](../)
* Classe [String](../../../system/string/)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)