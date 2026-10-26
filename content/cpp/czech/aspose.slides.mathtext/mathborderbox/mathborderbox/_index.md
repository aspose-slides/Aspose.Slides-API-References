---
title: MathBorderBox()
second_title: Aspose.Slides pro C++ - reference API
description: Vytváří prvek MathBorderBox s obdélníkovým okrajem
type: docs
weight: 222
url: /cs/aspose.slides.mathtext/mathborderbox/mathborderbox/
---
## MathBorderBox::MathBorderBox(System::SharedPtr\<IMathElement\>) konstruktor


Vytváří [MathBorderBox](../) prvek s obdélníkovým okrajem

```cpp
Aspose::Slides::MathText::MathBorderBox::MathBorderBox(System::SharedPtr<IMathElement> element)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Základní prvek, ke kterému se aplikuje rámeček. Může být null. |
## Poznámky



Příklad: 
```cpp
auto borderBox = System::MakeObject<MathBorderBox>(System::MakeObject<MathematicalText>(u"x"));
```

## MathBorderBox::MathBorderBox(System::SharedPtr\<IMathElement\>, bool, bool, bool, bool, bool, bool, bool, bool) konstruktor


Vytváří [MathBorderBox](../) prvek

```cpp
Aspose::Slides::MathText::MathBorderBox::MathBorderBox(System::SharedPtr<IMathElement> element, bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Základní prvek, ke kterému se aplikuje rámeček |
| hideTop | **bool** | Skrýt horní okraj |
| hideBottom | **bool** | Skrýt spodní okraj |
| hideLeft | **bool** | Skrýt levý okraj |
| hideRight | **bool** | Skrýt pravý okraj |
| strikethroughHorizontal | **bool** | Přeškrtávat horizontálně |
| strikethroughVertical | **bool** | Přeškrtávat vertikálně |
| strikethroughBottomLeftToTopRight | **bool** | Přeškrtávat spodní levý do horního pravého |
| strikethroughTopLeftToBottomRight | **bool** | Přeškrtávat horní levý do spodního pravého |
## Poznámky



Příklad: 
```cpp
auto borderBox = System::MakeObject<MathBorderBox>(System::MakeObject<MathematicalText>(u"x"), true, true, true, false, true, true, true, true);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [MathBorderBox](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)