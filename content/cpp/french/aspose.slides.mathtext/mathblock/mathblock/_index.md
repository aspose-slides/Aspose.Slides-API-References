---
title: MathBlock()
second_title: Référence API Aspose.Slides pour C++
description: Initialise une nouvelle instance de la classe MathBlock.
type: docs
weight: 66
url: /fr/aspose.slides.mathtext/mathblock/mathblock/
---
## MathBlock::MathBlock() constructeur


Initialise une nouvelle instance de la classe [MathBlock](../).

```cpp
Aspose::Slides::MathText::MathBlock::MathBlock()
```

## Remarques


Exemple :
```cpp
auto mathBlock = System::MakeObject<MathBlock>();
```

## MathBlock::MathBlock(System::SharedPtr\<IMathElement\>) constructeur


Crée un nouveau bloc mathématique et place l'élément spécifié dedans

```cpp
Aspose::Slides::MathText::MathBlock::MathBlock(System::SharedPtr<IMathElement> mathElement)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | L'élément mathématique à placer dans le bloc |
## Remarques



Exemple :
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
```

## MathBlock::MathBlock(System::SharedPtr\<System::Collections::Generic::IEnumerable\<System::SharedPtr\<IMathElement\>\>\>) constructeur


Crée un nouveau bloc mathématique et place les éléments spécifiés dedans

```cpp
Aspose::Slides::MathText::MathBlock::MathBlock(System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<IMathElement>>> mathElements)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| mathElements | [System::SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\>\>\> | Éléments mathématiques à placer dans le bloc |
## Remarques



Exemple :
```cpp
auto elems = System::MakeArray<System::SharedPtr<IMathElement>>({System::MakeObject<MathematicalText>(u"item1"), System::MakeObject<MathematicalText>(u"item2")});
auto mathBlock = System::MakeObject<MathBlock>(elems);
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [MathBlock](../)
* Classe [IMathElement](../../imathelement/)
* Classe [IEnumerable](../../../system.collections.generic/ienumerable/)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)