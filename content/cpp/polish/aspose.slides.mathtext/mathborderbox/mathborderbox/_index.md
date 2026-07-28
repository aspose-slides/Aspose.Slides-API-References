---
title: MathBorderBox()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Tworzy element MathBorderBox o prostokątnym obramowaniu
type: docs
weight: 222
url: /pl/aspose.slides.mathtext/mathborderbox/mathborderbox/
---
## MathBorderBox::MathBorderBox(System::SharedPtr\<IMathElement\>) konstruktor


Tworzy [MathBorderBox](../) element o prostokątnym obramowaniu

```cpp
Aspose::Slides::MathText::MathBorderBox::MathBorderBox(System::SharedPtr<IMathElement> element)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Podstawowy element, do którego stosuje się ramkę obramowania. Może być null. |
## Uwagi



Przykład: 
```cpp
auto borderBox = System::MakeObject<MathBorderBox>(System::MakeObject<MathematicalText>(u"x"));
```

## MathBorderBox::MathBorderBox(System::SharedPtr\<IMathElement\>, bool, bool, bool, bool, bool, bool, bool, bool) konstruktor


Tworzy [MathBorderBox](../) element

```cpp
Aspose::Slides::MathText::MathBorderBox::MathBorderBox(System::SharedPtr<IMathElement> element, bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Podstawowy element, do którego stosuje się ramkę obramowania |
| hideTop | **bool** | Ukryj górną krawędź |
| hideBottom | **bool** | Ukryj dolną krawędź |
| hideLeft | **bool** | Ukryj lewą krawędź |
| hideRight | **bool** | Ukryj prawą krawędź |
| strikethroughHorizontal | **bool** | Przekreślenie poziome |
| strikethroughVertical | **bool** | Przekreślenie pionowe |
| strikethroughBottomLeftToTopRight | **bool** | Przekreślenie od lewego dolnego do prawego górnego |
| strikethroughTopLeftToBottomRight | **bool** | Przekreślenie od lewego górnego do prawego dolnego |
## Uwagi



Przykład: 
```cpp
auto borderBox = System::MakeObject<MathBorderBox>(System::MakeObject<MathematicalText>(u"x"), true, true, true, false, true, true, true, true);
```

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathElement](../../imathelement/)
* Klasa [MathBorderBox](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)