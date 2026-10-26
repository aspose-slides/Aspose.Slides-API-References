---
title: ToBorderBox()
second_title: Riferimento API di Aspose.Slides per C++
description: Posiziona questo elemento in una border-box
type: docs
weight: 248
url: /it/aspose.slides.mathtext/mathelementbase/toborderbox/
---
## MathElementBase::ToBorderBox() method

Posiziona questo elemento in una border-box

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathElementBase::ToBorderBox() override
```

### Valore di ritorno

Border-box con questo elemento inserito all'interno
## Osservazioni



Esempio: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
```

## MathElementBase::ToBorderBox(bool, bool, bool, bool, bool, bool, bool, bool) method

Posiziona questo elemento in una border-box

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathElementBase::ToBorderBox(bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| hideTop | **bool** | Nascondi bordo superiore |
| hideBottom | **bool** | Nascondi bordo inferiore |
| hideLeft | **bool** | Nascondi bordo sinistro |
| hideRight | **bool** | Nascondi bordo destro |
| strikethroughHorizontal | **bool** | Barrato orizzontale della border box |
| strikethroughVertical | **bool** | Barrato verticale della border box |
| strikethroughBottomLeftToTopRight | **bool** | Barrato della border box da basso-sinistra a alto-destro |
| strikethroughTopLeftToBottomRight | **bool** | Barrato della border box da alto-sinistra a basso-destro |

### Valore di ritorno

Border-box con questo elemento inserito all'interno
## Osservazioni



Esempio: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox(false, false, true, true, false, false, false, false);
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathBorderBox](../../imathborderbox/)
* Classe [MathElementBase](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)