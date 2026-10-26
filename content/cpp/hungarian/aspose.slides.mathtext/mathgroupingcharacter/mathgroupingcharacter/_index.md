---
title: MathGroupingCharacter()
second_title: Aspose.Slides C++ API-referencia
description: Új példányt hoz létre a MathGroupingCharacter osztályból az alapértelmezett csoportosító karakterrel U+23DF (alsó kapcsos zárójel)
type: docs
weight: 92
url: /hu/aspose.slides.mathtext/mathgroupingcharacter/mathgroupingcharacter/
---
## MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr\<IMathElement\>) konstruktor


Új példányt hoz létre a [MathGroupingCharacter](../) osztályból az alapértelmezett csoportosító karakterrel U+23DF (alsó kapcsos zárójel)

```cpp
Aspose::Slides::MathText::MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr<IMathElement> element)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Az alap elem, amelyhez a vonalat alkalmazzák |
## Megjegyzés



Példa: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
```

## MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr\<IMathElement\>, char16_t, MathTopBotPositions, MathTopBotPositions) konstruktor


Új példányt hoz létre a [MathGroupingCharacter](../) osztályból.

```cpp
Aspose::Slides::MathText::MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr<IMathElement> element, char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Az alap elem, amelyhez a vonalat alkalmazzák |
| character | char16_t | Csoportosító karakter |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | A csoportosító karakter pozíciója |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | A csoport karakter függőleges igazítása |
## Megjegyzés



Példa: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"), u'_', MathTopBotPositions::Top, MathTopBotPositions::Bottom);
```

## Lásd még

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathElement](../../imathelement/)
* Osztály [MathGroupingCharacter](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)