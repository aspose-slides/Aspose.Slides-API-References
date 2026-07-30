---
title: set_DelimiterShape()
second_title: Riferimento API Aspose.Slides per C++
description: "Specifica la forma dei delimitatori nell'oggetto delimitatore. Quando è MathDelimiterShape::Centered, i delimitatori sono centrati attorno all'asse matematico del testo matematico e vengono comunque adattati per riempire l'intera altezza del loro contenuto. Quando è MathDelimiterShape::Match, la loro altezza e forma vengono modificate per corrispondere esattamente al loro contenuto."
type: docs
weight: 131
url: /it/aspose.slides.mathtext/imathdelimiter/set_delimitershape/
---
## IMathDelimiter::set_DelimiterShape(MathDelimiterShape) metodo

Specifica la forma dei delimitatori nell'oggetto delimitatore. Quando è [MathDelimiterShape::Centered](../../mathdelimitershape/), i delimitatori sono centrati attorno all'asse matematico del testo matematico e vengono comunque adattati per riempire l'intera altezza del loro contenuto. Quando è [MathDelimiterShape::Match](../../mathdelimitershape/), la loro altezza e forma sono modificate per corrispondere esattamente al loro contenuto.

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_DelimiterShape(MathDelimiterShape value)=0
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