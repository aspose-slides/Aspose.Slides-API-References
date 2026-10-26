---
title: set_DelimiterShape()
second_title: Aspose.Slides for C++ API Referansı
description: "Sınırlayıcı nesnedeki sınırlayıcıların şeklini belirtir. MathDelimiterShape::Centered olduğunda, sınırlayıcılar matematiksel metnin matematik ekseni etrafında ortalanır ve içerdikleri metnin tüm yüksekliğine uyacak şekilde yeniden boyutlandırılır. MathDelimiterShape::Match olduğunda ise, yükseklikleri ve şekilleri içeriğe tam olarak uyması için değiştirilir."
type: docs
weight: 131
url: /tr/aspose.slides.mathtext/imathdelimiter/set_delimitershape/
---
## IMathDelimiter::set_DelimiterShape(MathDelimiterShape) metodu


Sınırlayıcı nesnedeki sınırlayıcıların şeklini belirtir. [MathDelimiterShape::Centered](../../mathdelimitershape/) olduğunda, sınırlayıcılar matematiksel metnin matematik ekseni etrafında ortalanır ve içerdikleri metnin tüm yüksekliğine uyacak şekilde yeniden boyutlandırılır. [MathDelimiterShape::Match](../../mathdelimitershape/) olduğunda ise, yükseklikleri ve şekilleri içeriğe tam olarak uyması için değiştirilir.

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_DelimiterShape(MathDelimiterShape value)=0
```

## Açıklamalar


Örnek: 
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_DelimiterShape(MathDelimiterShape::Match);
```

## İlgili

* Enum [MathDelimiterShape](../../mathdelimitershape/)
* Sınıf [IMathDelimiter](../)
* Ad alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)