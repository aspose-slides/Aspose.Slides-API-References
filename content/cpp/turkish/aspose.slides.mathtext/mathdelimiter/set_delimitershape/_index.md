---
title: set_DelimiterShape()
second_title: Aspose.Slides for C++ API Referansı
description: "Sınırlayıcı nesnesindeki sınırlayıcıların şeklini belirtir. MathDelimiterShape::Centered olduğunda, sınırlayıcılar matematik metninin matematik ekseni etrafında ortalanır ve içeriğin tüm yüksekliğine sığacak şekilde yapılabilir. MathDelimiterShape::Match olduğunda, yükseklikleri ve şekilleri içeriğe tam olarak uyması için değiştirilir."
type: docs
weight: 131
url: /tr/aspose.slides.mathtext/mathdelimiter/set_delimitershape/
---
## MathDelimiter::set_DelimiterShape(MathDelimiterShape) metodu


Sınırlayıcı nesnesindeki sınırlayıcıların şeklini belirtir. [MathDelimiterShape::Centered](../../mathdelimitershape/) olduğunda, sınırlayıcılar matematik metninin matematik ekseni etrafında ortalanır ve içeriğin tam yüksekliğine sığacak şekilde yapılabilir. [MathDelimiterShape::Match](../../mathdelimitershape/) olduğunda, yükseklikleri ve şekilleri içeriğe tam olarak uyması için değiştirilir.

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_DelimiterShape(MathDelimiterShape value) override
```

## Açıklamalar


Örnek: 
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_DelimiterShape(MathDelimiterShape::Match);
```

## Bakınız

* Enum [MathDelimiterShape](../../mathdelimitershape/)
* Sınıf [MathDelimiter](../)
* Ad alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)