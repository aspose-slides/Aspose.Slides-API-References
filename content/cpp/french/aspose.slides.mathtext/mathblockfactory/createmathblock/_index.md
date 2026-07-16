---
title: CreateMathBlock()
second_title: Référence de l'API Aspose.Slides pour C++
description: Créer un bloc mathématique
type: docs
weight: 1
url: /fr/aspose.slides.mathtext/mathblockfactory/createmathblock/
---
## MathBlockFactory::CreateMathBlock() méthode

Créer un bloc mathématique

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlockFactory::CreateMathBlock() override
```

### Valeur de retour

nouveau bloc mathématique

## MathBlockFactory::CreateMathBlock(System::SharedPtr\<IMathElement\>) méthode

Créer un bloc mathématique et y placer l'élément

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlockFactory::CreateMathBlock(System::SharedPtr<IMathElement> mathElement) override
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | un élément mathématique |

### Valeur de retour

nouveau bloc mathématique

## MathBlockFactory::CreateMathBlock(System::SharedPtr\<IMathElementCollection\>) méthode

Créer un bloc mathématique et y placer des éléments

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlockFactory::CreateMathBlock(System::SharedPtr<IMathElementCollection> mathElements) override
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| mathElements | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElementCollection](../../imathelementcollection/)\> | éléments mathématiques |

### Valeur de retour

nouveau bloc mathématique

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathBlock](../../imathblock/)
* Class [MathBlockFactory](../)
* Class [IMathElement](../../imathelement/)
* Class [IMathElementCollection](../../imathelementcollection/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)