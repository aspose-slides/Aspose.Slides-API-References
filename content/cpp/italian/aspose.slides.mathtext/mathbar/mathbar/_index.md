---
title: MathBar()
second_title: Riferimento API di Aspose.Slides per C++
description: Inizializza MathBar con barra superiore (Posizione superiore)
type: docs
weight: 40
url: /it/aspose.slides.mathtext/mathbar/mathbar/
---
## MathBar::MathBar(System::SharedPtr\<IMathElement\>) constructor

Inizializza [MathBar](../) con barra superiore (Posizione superiore)

```cpp
Aspose::Slides::MathText::MathBar::MathBar(System::SharedPtr<IMathElement> element)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | L'elemento base a cui viene applicata la barra |
## Osservazioni



Esempio: 
```cpp
auto mathBar = System::MakeObject<MathBar>(System::MakeObject<MathematicalText>(u"x"));
```

## MathBar::MathBar(System::SharedPtr\<IMathElement\>, MathTopBotPositions) constructor

Inizializza [MathBar](../) con la posizione specificata

```cpp
Aspose::Slides::MathText::MathBar::MathBar(System::SharedPtr<IMathElement> element, MathTopBotPositions position)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | L'elemento base a cui viene applicata la barra |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | Posizione della linea della barra. |
## Osservazioni



Esempio: 
```cpp
auto mathBar = System::MakeObject<MathBar>(System::MakeObject<MathematicalText>(u"x"), MathTopBotPositions::Bottom);
```

## Vedi anche

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [MathBar](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)