---
title: get_DelimiterShape()
second_title: Riferimento API di Aspose.Slides per C++
description: "Specifica la forma dei delimitatori nell'oggetto delimitatore. Quando è MathDelimiterShape::Centered, i delimitatori sono centrati attorno all'asse matematico del testo matematico e vengono comunque adattati per coprire l'intera altezza dei loro contenuti. Quando è MathDelimiterShape::Match, la loro altezza e forma vengono modificate per corrispondere esattamente ai loro contenuti."
type: docs
weight: 118
url: /it/aspose.slides.mathtext/mathdelimiter/get_delimitershape/
---
## MathDelimiter::get_DelimiterShape() metodo


Specifica la forma dei delimitatori nell'oggetto delimitatore. Quando è [MathDelimiterShape::Centered](../../mathdelimitershape/), i delimitatori sono centrati attorno all'asse matematico del testo matematico e vengono comunque adattati per coprire l'intera altezza dei loro contenuti. Quando è [MathDelimiterShape::Match](../../mathdelimitershape/), la loro altezza e forma sono modificate per corrispondere esattamente ai loro contenuti.

```cpp
MathDelimiterShape Aspose::Slides::MathText::MathDelimiter::get_DelimiterShape() override
```

## Osservazioni


Esempio: 
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_DelimiterShape(MathDelimiterShape::Match);
```

## Vedi anche

* Enum [MathDelimiterShape](../../mathdelimitershape/)
* Classe [MathDelimiter](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)