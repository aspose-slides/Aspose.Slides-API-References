---
title: ToBorderBox()
second_title: Aspose.Slides C++ API-referencia
description: Az elemet egy border-boxba helyezi el
type: docs
weight: 261
url: /hu/aspose.slides.mathtext/imathelement/toborderbox/
---
## IMathElement::ToBorderBox() metódus

Az elemet egy border-boxba helyezi el

```cpp
virtual System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::IMathElement::ToBorderBox()=0
```

### Visszatérési érték

Border-box, amelyben ez az elem el van helyezve
## Megjegyzések

Példa:
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
```

## IMathElement::ToBorderBox(bool, bool, bool, bool, bool, bool, bool, bool) metódus

Az elemet egy border-boxba helyezi el

```cpp
virtual System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::IMathElement::ToBorderBox(bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight)=0
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
| strikethroughTopLeftToBottomRight | **bool** | Border Box áthúzás bal felső saroktól jobb alsó sarokig |

### Visszatérési érték

Border-box, amelyben ez az elem el van helyezve
## Megjegyzések

Példa:
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox(false, false, true, true, false, false, false, false);
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathBorderBox](../../imathborderbox/)
* Osztály [IMathElement](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)