---
title: MathGroupingCharacter()
second_title: Référence de l'API Aspose.Slides pour C++
description: Initialise une nouvelle instance de la classe MathGroupingCharacter avec le caractère de regroupement par défaut U+23DF (ACC CULBUTÉE INFÉRIEURE)
type: docs
weight: 92
url: /fr/aspose.slides.mathtext/mathgroupingcharacter/mathgroupingcharacter/
---
## MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr\<IMathElement\>) constructor


Initialise une nouvelle instance de la classe [MathGroupingCharacter](../) avec le caractère de regroupement par défaut U+23DF (ACC CULBUTÉE INFÉRIEURE)

```cpp
Aspose::Slides::MathText::MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr<IMathElement> element)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | L'élément de base auquel la barre est appliquée |
## Remarks



Exemple : 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
```

## MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr\<IMathElement\>, char16_t, MathTopBotPositions, MathTopBotPositions) constructor


Initialise une nouvelle instance de la classe [MathGroupingCharacter](../).

```cpp
Aspose::Slides::MathText::MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr<IMathElement> element, char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | L'élément de base auquel la barre est appliquée |
| character | char16_t | Caractère de regroupement |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | Position du caractère de regroupement |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | Justification verticale du caractère de groupe |
## Remarks



Exemple : 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"), u'_', MathTopBotPositions::Top, MathTopBotPositions::Bottom);
```

## See Also

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathGroupingCharacter](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)