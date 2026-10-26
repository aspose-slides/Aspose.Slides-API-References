---
title: get_DelimiterShape()
second_title: Riferimento API di Aspose.Slides per C++
description: "Specifica la forma dei delimitatori nell'oggetto delimitatore. Quando è MathDelimiterShape::Centered, i delimitatori sono centrati sull'asse matematico del testo matematico e devono ancora essere adattati per occupare l'intera altezza del loro contenuto. Quando è MathDelimiterShape::Match, la loro altezza e forma vengono modificate per corrispondere esattamente al contenuto."
type: docs
weight: 118
url: /it/aspose.slides.mathtext/imathdelimiter/get_delimitershape/
---
## IMathDelimiter::get_DelimiterShape() metodo


Specifica la forma dei delimitatori nell'oggetto delimitatore. Quando è [MathDelimiterShape::Centered](../../mathdelimitershape/), i delimitatori sono centrati sull'asse matematico del testo matematico e devono ancora essere adattati per occupare l'intera altezza del loro contenuto. Quando è [MathDelimiterShape::Match](../../mathdelimitershape/), la loro altezza e forma vengono modificate per corrispondere esattamente al contenuto.

```cpp
virtual MathDelimiterShape Aspose::Slides::MathText::IMathDelimiter::get_DelimiterShape()=0
```

## Osservazioni


Esempio: 
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_DelimiterShape(MathDelimiterShape::Match);
```

## Vedi anche

* Enum [MathDelimiterShape](../../mathdelimitershape/)
* Class [IMathDelimiter](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)