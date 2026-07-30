---
title: CreateMathBorderBox()
second_title: Aspose.Slides pro C++ API referenci
description: Vytvoří matematický rámeček aplikací na prvek
type: docs
weight: 1
url: /cs/aspose.slides.mathtext/mathborderboxfactory/createmathborderbox/
---
## MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr\<IMathElement\>) metoda


Vytvoří matematický rámeček aplikací na prvek

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr<IMathElement> element) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | matematický prvek, na který se aplikuje rámeček |

### Návratová hodnota

nový prvek rámečku

## MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr\<IMathElement\>, bool, bool, bool, bool, bool, bool, bool, bool) metoda


Vytvoří matematický rámeček aplikací na prvek

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr<IMathElement> element, bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | matematický prvek, na který se aplikuje rámeček |
| hideTop | **bool** | Skryt horní okraj |
| hideBottom | **bool** | Skryt spodní okraj |
| hideLeft | **bool** | Skryt levý okraj |
| hideRight | **bool** | Skryt pravý okraj |
| strikethroughHorizontal | **bool** | Vodorovné přeškrtnutí rámečku |
| strikethroughVertical | **bool** | Vertikální přeškrtnutí rámečku |
| strikethroughBottomLeftToTopRight | **bool** | Přeškrtnutí rámečku od levého dolního k pravému hornímu |
| strikethroughTopLeftToBottomRight | **bool** | Přeškrtnutí rámečku od levého horního k pravému dolnímu |

### Návratová hodnota

nový prvek rámečku

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IMathBorderBox](../../imathborderbox/)
* Třída [IMathElement](../../imathelement/)
* Třída [MathBorderBoxFactory](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)