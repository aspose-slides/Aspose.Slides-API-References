---
title: MathBorderBox()
second_title: Aspose.Slides for C++ API Referenciája
description: Létrehozza a MathBorderBox elemet téglalap alakú szegéllyel
type: docs
weight: 222
url: /hu/aspose.slides.mathtext/mathborderbox/mathborderbox/
---
## MathBorderBox::MathBorderBox(System::SharedPtr\<IMathElement\>) konstruktor

Létrehozza a [MathBorderBox](../) elemet téglalap alakú szegéllyel

```cpp
Aspose::Slides::MathText::MathBorderBox::MathBorderBox(System::SharedPtr<IMathElement> element)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Az alap element, amelyhez a szegélydoboz alkalmazva van. Lehet null. |

## Megjegyzések

Példa: ```cpp
auto borderBox = System::MakeObject<MathBorderBox>(System::MakeObject<MathematicalText>(u"x"));
```

## MathBorderBox::MathBorderBox(System::SharedPtr\<IMathElement\>, bool, bool, bool, bool, bool, bool, bool, bool) konstruktor

Létrehozza a [MathBorderBox](../) elemet

```cpp
Aspose::Slides::MathText::MathBorderBox::MathBorderBox(System::SharedPtr<IMathElement> element, bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Az alap element, amelyhez a szegélydoboz alkalmazva van |
| hideTop | **bool** | Felső él elrejtése |
| hideBottom | **bool** | Alsó él elrejtése |
| hideLeft | **bool** | Bal él elrejtése |
| hideRight | **bool** | Jobb él elrejtése |
| strikethroughHorizontal | **bool** | Vízszintes áthúzás |
| strikethroughVertical | **bool** | Függőleges áthúzás |
| strikethroughBottomLeftToTopRight | **bool** | Áthúzás bal alsó saroktól jobb felső sarokig |
| strikethroughTopLeftToBottomRight | **bool** | Áthúzás bal felső saroktól jobb alsó sarokig |

## Megjegyzések

Példa: ```cpp
auto borderBox = System::MakeObject<MathBorderBox>(System::MakeObject<MathematicalText>(u"x"), true, true, true, false, true, true, true, true);
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathElement](../../imathelement/)
* Osztály [MathBorderBox](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)