---
title: MathBar()
second_title: Aspose.Slides för C++ API-referens
description: Initierar MathBar med överstreck (Övre position)
type: docs
weight: 40
url: /sv/aspose.slides.mathtext/mathbar/mathbar/
---
## MathBar::MathBar(System::SharedPtr\<IMathElement\>) konstruktor


Initierar [MathBar](../) med överstreck (övre position)

```cpp
Aspose::Slides::MathText::MathBar::MathBar(System::SharedPtr<IMathElement> element)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Basiselementet som baren appliceras på |
## Anmärkningar



Exempel: 
```cpp
auto mathBar = System::MakeObject<MathBar>(System::MakeObject<MathematicalText>(u"x"));
```

## MathBar::MathBar(System::SharedPtr\<IMathElement\>, MathTopBotPositions) konstruktor


Initierar [MathBar](../) med angiven position

```cpp
Aspose::Slides::MathText::MathBar::MathBar(System::SharedPtr<IMathElement> element, MathTopBotPositions position)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Basiselementet som baren appliceras på |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | Position för barlinjen. |
## Anmärkningar



Exempel: 
```cpp
auto mathBar = System::MakeObject<MathBar>(System::MakeObject<MathematicalText>(u"x"), MathTopBotPositions::Bottom);
```

## Se även

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IMathElement](../../imathelement/)
* Klass [MathBar](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)