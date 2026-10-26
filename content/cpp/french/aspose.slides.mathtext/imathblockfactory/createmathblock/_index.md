---
title: CreateMathBlock()
second_title: Référence de l'API Aspose.Slides pour C++
description: Créer un bloc mathématique
type: docs
weight: 1
url: /fr/aspose.slides.mathtext/imathblockfactory/createmathblock/
---
## IMathBlockFactory::CreateMathBlock() méthode

Créer un bloc mathématique

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathBlockFactory::CreateMathBlock()=0
```

### Valeur de retour

nouveau bloc mathématique

## IMathBlockFactory::CreateMathBlock(System::SharedPtr\<IMathElement\>) méthode

Créer un bloc mathématique et y placer l'élément

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathBlockFactory::CreateMathBlock(System::SharedPtr<IMathElement> mathElement)=0
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Un élément mathématique |

### Valeur de retour

nouveau bloc mathématique

## IMathBlockFactory::CreateMathBlock(System::SharedPtr\<IMathElementCollection\>) méthode

Créer un bloc mathématique et y placer les éléments

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathBlockFactory::CreateMathBlock(System::SharedPtr<IMathElementCollection> mathElements)=0
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| mathElements | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElementCollection](../../imathelementcollection/)\> | éléments mathématiques |

### Valeur de retour

nouveau bloc mathématique

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathBlock](../../imathblock/)
* Classe [IMathBlockFactory](../)
* Classe [IMathElement](../../imathelement/)
* Classe [IMathElementCollection](../../imathelementcollection/)
* Espace de noms [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)