---
title: ToBorderBox()
second_title: Aspose.Slides C++ API-referencia
description: Elhelyezi ezt az elemet egy border-boxban
type: docs
weight: 248
url: /hu/aspose.slides.mathtext/mathelementbase/toborderbox/
---
## MathElementBase::ToBorderBox() metódus

Elhelyezi ezt az elemet egy border-boxba

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathElementBase::ToBorderBox() override
```

### Visszatérési érték

Border-box, amely tartalmazza ezt az elemet

## Megjegyzés

Példa:
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
```

## MathElementBase::ToBorderBox(bool, bool, bool, bool, bool, bool, bool, bool) metódus

Elhelyezi ezt az elemet egy border-boxba

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathElementBase::ToBorderBox(bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| hideTop | **bool** | Felső él elrejtése |
| hideBottom | **bool** | Alsó él elrejtése |
| hideLeft | **bool** | Bal él elrejtése |
| hideRight | **bool** | Jobb él elrejtése |
| strikethroughHorizontal | **bool** | Border Box vízszintes áthúzás |
| strikethroughVertical | **bool** | Border Box függőleges áthúzás |
| strikethroughBottomLeftToTopRight | **bool** | Border Box áthúzás bal alsó saroktól jobb felső sarokig |
| strikethroughTopLeftToBottomRight | **bool** | Border Box áthúzás felső bal saroktól jobb alsó sarokig |

### Visszatérési érték

Border-box, amely tartalmazza ezt az elemet

## Megjegyzés

Példa:
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox(false, false, true, true, false, false, false, false);
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathBorderBox](../../imathborderbox/)
* Osztály [MathElementBase](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)