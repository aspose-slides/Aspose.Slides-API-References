---
title: MathBorderBox()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt MathBorderBox-element met een rechthoekige rand
type: docs
weight: 222
url: /nl/aspose.slides.mathtext/mathborderbox/mathborderbox/
---
## MathBorderBox::MathBorderBox(System::SharedPtr\<IMathElement\>) constructor


Creëert [MathBorderBox](../) element met een rechthoekige rand

```cpp
Aspose::Slides::MathText::MathBorderBox::MathBorderBox(System::SharedPtr<IMathElement> element)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Het basiselement waarop de randbox wordt toegepast. Kan null zijn. |
## Opmerkingen



Voorbeeld: 
```cpp
auto borderBox = System::MakeObject<MathBorderBox>(System::MakeObject<MathematicalText>(u"x"));
```

## MathBorderBox::MathBorderBox(System::SharedPtr\<IMathElement\>, bool, bool, bool, bool, bool, bool, bool, bool) constructor


Creëert [MathBorderBox](../) element

```cpp
Aspose::Slides::MathText::MathBorderBox::MathBorderBox(System::SharedPtr<IMathElement> element, bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Het basiselement waarop de randbox wordt toegepast |
| hideTop | **bool** | Verberg bovenkant |
| hideBottom | **bool** | Verberg onderkant |
| hideLeft | **bool** | Verberg linkerkant |
| hideRight | **bool** | Verberg rechterkant |
| strikethroughHorizontal | **bool** | Doorhalen horizontaal |
| strikethroughVertical | **bool** | Doorhalen verticaal |
| strikethroughBottomLeftToTopRight | **bool** | Doorhalen onder-links naar boven-rechts |
| strikethroughTopLeftToBottomRight | **bool** | Doorhalen boven-links naar onder-rechts |
## Opmerkingen



Voorbeeld: 
```cpp
auto borderBox = System::MakeObject<MathBorderBox>(System::MakeObject<MathematicalText>(u"x"), true, true, true, false, true, true, true, true);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [MathBorderBox](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)