---
title: ToBorderBox()
second_title: Riferimento API di Aspose.Slides per C++
description: Posiziona questo elemento in un border-box
type: docs
weight: 261
url: /it/aspose.slides.mathtext/imathelement/toborderbox/
---
## IMathElement::ToBorderBox() metodo


Posiziona questo elemento in un border-box

```cpp
virtual System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::IMathElement::ToBorderBox()=0
```


### Valore di ritorno

Border-box con questo elemento posizionato all’interno
## Osservazioni



Esempio: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
```

## IMathElement::ToBorderBox(bool, bool, bool, bool, bool, bool, bool, bool) metodo


Posiziona questo elemento in un border-box

```cpp
virtual System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::IMathElement::ToBorderBox(bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| hideTop | **bool** | Nascondi bordo superiore |
| hideBottom | **bool** | Nascondi bordo inferiore |
| hideLeft | **bool** | Nascondi bordo sinistro |
| hideRight | **bool** | Nascondi bordo destro |
| strikethroughHorizontal | **bool** | Border Box barrato orizzontalmente |
| strikethroughVertical | **bool** | Border Box barrato verticalmente |
| strikethroughBottomLeftToTopRight | **bool** | Border Box barrato da basso-sinistra a alto-destra |
| strikethroughTopLeftToBottomRight | **bool** | Border Box barrato da alto-sinistra a basso-destra |

### Valore di ritorno

Border-box con questo elemento posizionato all’interno
## Osservazioni



Esempio: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox(false, false, true, true, false, false, false, false);
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathBorderBox](../../imathborderbox/)
* Classe [IMathElement](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)