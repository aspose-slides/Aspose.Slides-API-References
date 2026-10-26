---
title: CreateMathBorderBox()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Utwórz ramkę graniczną matematyczną, stosując ją do elementu
type: docs
weight: 1
url: /pl/aspose.slides.mathtext/mathborderboxfactory/createmathborderbox/
---
## MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr\<IMathElement\>) metoda


Utwórz ramkę graniczną matematyczną, stosując ją do elementu

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr<IMathElement> element) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | element matematyczny, do którego ma zostać zastosowana ramka graniczna |

### Wartość zwracana

nowy element ramki granicznej

## MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr\<IMathElement\>, bool, bool, bool, bool, bool, bool, bool, bool) metoda


Utwórz ramkę graniczną matematyczną, stosując ją do elementu

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr<IMathElement> element, bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | element matematyczny, do którego ma zostać zastosowana ramka graniczna |
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

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathBorderBox](../../imathborderbox/)
* Klasa [IMathElement](../../imathelement/)
* Klasa [MathBorderBoxFactory](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)