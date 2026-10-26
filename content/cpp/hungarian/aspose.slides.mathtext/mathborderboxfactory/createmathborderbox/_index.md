---
title: CreateMathBorderBox()
second_title: Aspose.Slides C++ API hivatkozás
description: Matematikai szegélydoboz létrehozása az elemre alkalmazva
type: docs
weight: 1
url: /hu/aspose.slides.mathtext/mathborderboxfactory/createmathborderbox/
---
## MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr\<IMathElement\>) method

Math border box létrehozása az elemre alkalmazva

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr<IMathElement> element) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | matematikai elem a szegélydoboz alkalmazásához |

### Visszatérési érték

új szegélydoboz elem

## MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr\<IMathElement\>, bool, bool, bool, bool, bool, bool, bool, bool) method

Math border box létrehozása az elemre alkalmazva

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr<IMathElement> element, bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | matematikai elem a szegélydoboz alkalmazásához |
| hideTop | **bool** | Felső él elrejtése |
| hideBottom | **bool** | Alsó él elrejtése |
| hideLeft | **bool** | Bal él elrejtése |
| hideRight | **bool** | Jobb él elrejtése |
| strikethroughHorizontal | **bool** | Vízszintes áthúzás a szegélydobozban |
| strikethroughVertical | **bool** | Függőleges áthúzás a szegélydobozban |
| strikethroughBottomLeftToTopRight | **bool** | Áthúzás a szegélydobozban bal alsó saroktól jobb felső sarokig |
| strikethroughTopLeftToBottomRight | **bool** | Áthúzás a szegélydobozban bal felső saroktól jobb alsó sarokig |

### Visszatérési érték

új szegélydoboz elem

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathBorderBox](../../imathborderbox/)
* Osztály [IMathElement](../../imathelement/)
* Osztály [MathBorderBoxFactory](../)
* Névtere [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)