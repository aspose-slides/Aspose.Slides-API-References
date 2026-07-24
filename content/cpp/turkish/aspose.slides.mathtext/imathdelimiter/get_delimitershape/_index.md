---
title: get_DelimiterShape()
second_title: Aspose.Slides için C++ API Referansı
description: "Delimiter nesnesindeki sınırlayıcıların şeklini belirtir. MathDelimiterShape::Centered olduğunda, sınırlayıcılar matematiksel metnin matematik ekseni etrafında ortalanır ve içeriklerinin tamamının yüksekliğine sığacak şekilde ayarlanır. MathDelimiterShape::Match olduğunda, yüksekliği ve şekli tam olarak içeriklerine uyacak şekilde değiştirilir."
type: docs
weight: 118
url: /tr/aspose.slides.mathtext/imathdelimiter/get_delimitershape/
---
## IMathDelimiter::get_DelimiterShape() metod


Sınırlayıcı nesnesindeki sınırlayıcıların şeklini belirtir. [MathDelimiterShape::Centered](../../mathdelimitershape/) olduğunda, sınırlayıcılar matematiksel metnin matematik ekseni etrafında ortalanır ve içeriklerinin tamamının yüksekliğine sığacak şekilde yapılır. [MathDelimiterShape::Match](../../mathdelimitershape/) olduğunda, yükseklikleri ve şekilleri tam olarak içeriklerine uyması için değiştirilir.

```cpp
virtual MathDelimiterShape Aspose::Slides::MathText::IMathDelimiter::get_DelimiterShape()=0
```

## Açıklamalar


Örnek: 
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_DelimiterShape(MathDelimiterShape::Match);
```

## Diğer

* Enum [MathDelimiterShape](../../mathdelimitershape/)
* Sınıf [IMathDelimiter](../)
* İsim Uzayı [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)