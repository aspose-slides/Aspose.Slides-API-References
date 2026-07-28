---
title: MathBar()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Inicjalizuje MathBar z nadkreśleniem (pozycja górna)
type: docs
weight: 40
url: /pl/aspose.slides.mathtext/mathbar/mathbar/
---
## MathBar::MathBar(System::SharedPtr\<IMathElement\>) konstruktor


Inicjalizuje [MathBar](../) z nadkreśleniem (pozycja górna)

```cpp
Aspose::Slides::MathText::MathBar::MathBar(System::SharedPtr<IMathElement> element)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Podstawowy element, do którego stosowany jest pasek |
## Uwagi



Przykład: 
```cpp
auto mathBar = System::MakeObject<MathBar>(System::MakeObject<MathematicalText>(u"x"));
```

## MathBar::MathBar(System::SharedPtr\<IMathElement\>, MathTopBotPositions) konstruktor


Inicjalizuje [MathBar](../) z określoną pozycją

```cpp
Aspose::Slides::MathText::MathBar::MathBar(System::SharedPtr<IMathElement> element, MathTopBotPositions position)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Podstawowy element, do którego stosowany jest pasek |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | Pozycja linii paska. |
## Uwagi



Przykład: 
```cpp
auto mathBar = System::MakeObject<MathBar>(System::MakeObject<MathematicalText>(u"x"), MathTopBotPositions::Bottom);
```

## Zobacz także

* Wyliczenie [MathTopBotPositions](../../mathtopbotpositions/)
* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathElement](../../imathelement/)
* Klasa [MathBar](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)