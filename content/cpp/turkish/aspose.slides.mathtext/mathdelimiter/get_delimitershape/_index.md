---
title: get_DelimiterShape()
second_title: Aspose.Slides for C++ API Referansı
description: "Delimiter nesnesindeki sınırlayıcıların şeklini belirler. MathDelimiterShape::Centered olduğunda, sınırlayıcılar matematiksel metnin matematik ekseni etrafında ortalanır ve içeriklerinin tüm yüksekliğine sığacak şekilde yapılır. MathDelimiterShape::Match olduğunda, yüksekliği ve şekli içeriklerine tam olarak uyması için değiştirilir."
type: docs
weight: 118
url: /tr/aspose.slides.mathtext/mathdelimiter/get_delimitershape/
---
## MathDelimiter::get_DelimiterShape() metodu


Sınırlayıcı nesnesindeki sınırlayıcıların şeklini belirler. [MathDelimiterShape::Centered](../../mathdelimitershape/) olduğunda, sınırlayıcılar matematiksel metnin matematik ekseninin etrafında ortalanır ve içeriklerinin tüm yüksekliğine sığacak şekilde yapılır. [MathDelimiterShape::Match](../../mathdelimitershape/) olduğunda, yüksekliği ve şekli içeriklerine tam olarak uyması için değiştirilir.

```cpp
MathDelimiterShape Aspose::Slides::MathText::MathDelimiter::get_DelimiterShape() override
```

## Açıklamalar


Örnek: 
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_DelimiterShape(MathDelimiterShape::Match);
```

## Ayrıca Bakınız

* Enum [MathDelimiterShape](../../mathdelimitershape/)
* Sınıf [MathDelimiter](../)
* AdAlanı [Aspose::Slides::MathText](../../)
* Kitaplık [Aspose.Slides](../../../)