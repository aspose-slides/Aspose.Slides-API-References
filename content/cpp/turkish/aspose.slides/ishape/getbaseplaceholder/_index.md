---
title: GetBasePlaceholder()
second_title: Aspose.Slides for C++ API Referansı
description: Temel bir yer tutucu şekil döndürür (şekil, mevcut şeklin kalıtıldığı düzen ve/veya ana slayttan gelir).
type: docs
weight: 573
url: /tr/aspose.slides/ishape/getbaseplaceholder/
---
## IShape::GetBasePlaceholder() metodu


Temel bir yer tutucu şekil döndürür (şekil, mevcut şeklin kalıtıldığı düzen ve/veya ana slayttan gelir).

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShape::GetBasePlaceholder()=0
```

## Açıklamalar


Mevcut şekil kalıtılmamışsa null döndürülür.


```cpp
// yer tutucu şeklin tüm (master/layout/slide) animasyon etkilerini al
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"sample.pptx");

System::SharedPtr<ISlide> slide = pres->get_Slide(0);
System::SharedPtr<IShape> shape = slide->get_Shape(0);
System::ArrayPtr<System::SharedPtr<IEffect>> shapeEffects = slide->get_Timeline()->get_MainSequence()->GetEffectsByShape(shape);

System::SharedPtr<IShape> layoutShape = shape->GetBasePlaceholder();
System::ArrayPtr<System::SharedPtr<IEffect>> layoutShapeEffects = slide->get_LayoutSlide()->get_Timeline()->get_MainSequence()->GetEffectsByShape(layoutShape);

System::SharedPtr<IShape> masterShape = layoutShape->GetBasePlaceholder();
System::ArrayPtr<System::SharedPtr<IEffect>> masterShapeEffects = slide->get_LayoutSlide()->get_MasterSlide()->get_Timeline()->get_MainSequence()->GetEffectsByShape(masterShape);
```




## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IShape](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)