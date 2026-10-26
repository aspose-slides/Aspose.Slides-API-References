---
title: Radical()
second_title: Référence API Aspose.Slides pour C++
description: Spécifie la racine mathématique du degré donné à partir de l'argument spécifié.
type: docs
weight: 131
url: /fr/aspose.slides.mathtext/imathelement/radical/
---
## IMathElement::Radical(System::SharedPtr\<IMathElement\>) méthode


Spécifie la racine mathématique du degré donné à partir de l'argument spécifié.

```cpp
virtual System::SharedPtr<IMathRadical> Aspose::Slides::MathText::IMathElement::Radical(System::SharedPtr<IMathElement> degree)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| degree | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Argument of Radical |

### Valeur de retour

Nouvelle instance du type [IMathRadical](../../imathradical/)
## Remarques



Exemple: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto degree = System::MakeObject<MathematicalText>(u"y");
auto radical = baseElement->Radical(degree);
```

## IMathElement::Radical(System::String) méthode


Spécifie la racine mathématique du degré donné à partir de l'argument spécifié.

```cpp
virtual System::SharedPtr<IMathRadical> Aspose::Slides::MathText::IMathElement::Radical(System::String degree)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| degree | [System::String](../../../system/string/) | Argument of Radical |

### Valeur de retour

Nouvelle instance du type [IMathRadical](../../imathradical/)
## Remarques



Exemple: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto radical = baseElement->Radical(u"3");
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathRadical](../../imathradical/)
* Classe [IMathElement](../)
* Classe [String](../../../system/string/)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)