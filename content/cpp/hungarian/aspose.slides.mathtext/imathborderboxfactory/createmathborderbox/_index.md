---
title: CreateMathBorderBox()
second_title: Aspose.Slides C++ API referencia
description: Matematikai szegélydoboz létrehozása az elemre alkalmazva
type: docs
weight: 1
url: /hu/aspose.slides.mathtext/imathborderboxfactory/createmathborderbox/
---
## IMathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr\<IMathElement\>) method

Matematikai szegélydoboz létrehozása az elemre alkalmazva

```cpp
virtual System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::IMathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr<IMathElement> element)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | a szegélydobozra alkalmazandó matematikai elem |

### Visszatérési érték

új szegélydoboz elem

## IMathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr\<IMathElement\>, bool, bool, bool, bool, bool, bool, bool, bool) method

Matematikai szegélydoboz létrehozása az elemre alkalmazva

```cpp
virtual System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::IMathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr<IMathElement> element, bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | a szegélydobozra alkalmazandó matematikai elem |
| hideTop | **bool** | Felső él elrejtése |
| hideBottom | **bool** | Alsó él elrejtése |
| hideLeft | **bool** | Bal él elrejtése |
| hideRight | **bool** | Jobb él elrejtése |
| strikethroughHorizontal | **bool** | Vízszintes áthúzás a szegélydobozban |
| strikethroughVertical | **bool** | Függőleges áthúzás a szegélydobozban |
| strikethroughBottomLeftToTopRight | **bool** | Áthúzás bal alsó saroktól jobb felső sarokig |
| strikethroughTopLeftToBottomRight | **bool** | Áthúzás bal felső saroktól jobb alsó sarokig |

### Visszatérési érték

új szegélydoboz elem

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathBorderBox](../../imathborderbox/)
* Osztály [IMathElement](../../imathelement/)
* Osztály [IMathBorderBoxFactory](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)