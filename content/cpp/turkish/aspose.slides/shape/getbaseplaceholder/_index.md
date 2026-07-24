---
title: GetBasePlaceholder()
second_title: Aspose.Slides C++ için API Referansı
description: Temel bir placeholder şekli döndürür (düzen ve/veya ana slayttan gelen şekil, mevcut şeklin kalıtım aldığı).
type: docs
weight: 638
url: /tr/aspose.slides/shape/getbaseplaceholder/
---
## Shape::GetBasePlaceholder() yöntemi


Temel bir placeholder shape döndürür (layout ve/veya ana slayttan gelen shape, mevcut shape'ın kalıtım aldığı).

```cpp
System::SharedPtr<IShape> Aspose::Slides::Shape::GetBasePlaceholder() override
```

## Açıklamalar


Mevcut shape kalıtım almazsa null döndürülür.


```cpp
// placeholder şeklinin tüm (master/layout/slide) animasyon efektlerini al
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
* Sınıf [IShape](../../ishape/)
* Sınıf [Shape](../)
* İsim Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)