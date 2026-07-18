---
title: MathBar()
second_title: Αναφορά API του Aspose.Slides για C++
description: Αρχικοποιεί το MathBar με overbar (Θέση κορυφής)
type: docs
weight: 40
url: /el/aspose.slides.mathtext/mathbar/mathbar/
---
## MathBar::MathBar(System::SharedPtr\<IMathElement\>) κατασκευαστής


Αρχικοποιεί το [MathBar](../) με overbar (Top position)

```cpp
Aspose::Slides::MathText::MathBar::MathBar(System::SharedPtr<IMathElement> element)
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Το βασικό στοιχείο στο οποίο εφαρμόζεται η γραμμή |
## Σχόλια



Παράδειγμα: 
```cpp
auto mathBar = System::MakeObject<MathBar>(System::MakeObject<MathematicalText>(u"x"));
```

## MathBar::MathBar(System::SharedPtr\<IMathElement\>, MathTopBotPositions) κατασκευαστής


Αρχικοποιεί το [MathBar](../) with specified position

```cpp
Aspose::Slides::MathText::MathBar::MathBar(System::SharedPtr<IMathElement> element, MathTopBotPositions position)
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Το βασικό στοιχείο στο οποίο εφαρμόζεται η γραμμή |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | Θέση της γραμμής της μπάρας. |
## Σχόλια



Παράδειγμα: 
```cpp
auto mathBar = System::MakeObject<MathBar>(System::MakeObject<MathematicalText>(u"x"), MathTopBotPositions::Bottom);
```

## Δείτε επίσης

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [MathBar](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)