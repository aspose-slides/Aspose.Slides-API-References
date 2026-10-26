---
title: Radical()
second_title: Référence de l'API Aspose.Slides pour C++
description: Spécifie la racine mathématique du degré donné à partir de l'argument spécifié.
type: docs
weight: 118
url: /fr/aspose.slides.mathtext/mathelementbase/radical/
---
## MathElementBase::Radical(System::SharedPtr\<IMathElement\>) méthode


Spécifie la racine mathématique du degré donné à partir de l'argument spécifié.

```cpp
System::SharedPtr<IMathRadical> Aspose::Slides::MathText::MathElementBase::Radical(System::SharedPtr<IMathElement> degree) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| degree | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Argument du radical |

### Valeur de retour

Nouvelle instance du type [IMathRadical](../../imathradical/)
## Remarques



Exemple : 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto degree = System::MakeObject<MathematicalText>(u"y");
auto radical = baseElement->Radical(degree);
```

## MathElementBase::Radical(System::String) méthode


Spécifie la racine mathématique du degré donné à partir de l'argument spécifié.

```cpp
System::SharedPtr<IMathRadical> Aspose::Slides::MathText::MathElementBase::Radical(System::String degree) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| degree | [System::String](../../../system/string/) | Argument du radical |

### Valeur de retour

Nouvelle instance du type [IMathRadical](../../imathradical/)
## Remarques



Exemple : 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto radical = baseElement->Radical(u"3");
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathRadical](../../imathradical/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathElementBase](../)
* Classe [String](../../../system/string/)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)