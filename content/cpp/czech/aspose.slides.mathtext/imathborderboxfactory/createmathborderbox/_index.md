---
title: CreateMathBorderBox()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vytvoří matematický ohraničovací rámeček aplikací na prvek
type: docs
weight: 1
url: /cs/aspose.slides.mathtext/imathborderboxfactory/createmathborderbox/
---
## IMathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr\<IMathElement\>) method


Vytvoří matematický ohraničovací rámeček aplikací na prvek

```cpp
virtual System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::IMathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr<IMathElement> element)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | matematický prvek, na který se aplikuje ohraničovací rámeček |

### Návratová hodnota

nový prvek ohraničovacího rámečku

## IMathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr\<IMathElement\>, bool, bool, bool, bool, bool, bool, bool, bool) method


Vytvoří matematický ohraničovací rámeček aplikací na prvek

```cpp
virtual System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::IMathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr<IMathElement> element, bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | matematický prvek, na který se aplikuje ohraničovací rámeček |
| hideTop | **bool** | Skrýt horní okraj |
| hideBottom | **bool** | Skrýt dolní okraj |
| hideLeft | **bool** | Skrýt levý okraj |
| hideRight | **bool** | Skrýt pravý okraj |
| strikethroughHorizontal | **bool** | Vodorovné přeškrtnutí ohraničovacího rámečku |
| strikethroughVertical | **bool** | Svislé přeškrtnutí ohraničovacího rámečku |
| strikethroughBottomLeftToTopRight | **bool** | Přeškrtnutí ohraničovacího rámečku od levého dolního rohu k pravému hornímu rohu |
| strikethroughTopLeftToBottomRight | **bool** | Přeškrtnutí ohraničovacího rámečku od levého horního rohu k pravému dolnímu rohu |

### Návratová hodnota

nový prvek ohraničovacího rámečku

## Viz také

* Definice typu [SharedPtr](../../../system/sharedptr/)
* Třída [IMathBorderBox](../../imathborderbox/)
* Třída [IMathElement](../../imathelement/)
* Třída [IMathBorderBoxFactory](../)
* Prostor názvů [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)