---
title: CreateMathBorderBox()
second_title: Aspose.Slides dla C++ odniesienie API
description: Utwórz ramkę graniczną matematyczną, stosując do elementu
type: docs
weight: 1
url: /pl/aspose.slides.mathtext/imathborderboxfactory/createmathborderbox/
---
## IMathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr\<IMathElement\>) method

Utwórz ramkę graniczną matematyczną, stosując do elementu

```cpp
virtual System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::IMathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr<IMathElement> element)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | element matematyczny, do którego ma być zastosowana ramka graniczna |

### Wartość zwracana

nowy element ramki granicznej

## IMathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr\<IMathElement\>, bool, bool, bool, bool, bool, bool, bool, bool) method

Utwórz ramkę graniczną matematyczną, stosując do elementu

```cpp
virtual System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::IMathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr<IMathElement> element, bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | element matematyczny, do którego ma być zastosowana ramka graniczna |
| hideTop | **bool** | Ukryj górną krawędź |
| hideBottom | **bool** | Ukryj dolną krawędź |
| hideLeft | **bool** | Ukryj lewą krawędź |
| hideRight | **bool** | Ukryj prawą krawędź |
| strikethroughHorizontal | **bool** | Przekreślenie poziome ramki granicznej |
| strikethroughVertical | **bool** | Przekreślenie pionowe ramki granicznej |
| strikethroughBottomLeftToTopRight | **bool** | Przekreślenie od lewego dolnego do prawego górnego |
| strikethroughTopLeftToBottomRight | **bool** | Przekreślenie od lewego górnego do prawego dolnego |

### Wartość zwracana

nowy element ramki granicznej

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathBorderBox](../../imathborderbox/)
* Klasa [IMathElement](../../imathelement/)
* Klasa [IMathBorderBoxFactory](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)