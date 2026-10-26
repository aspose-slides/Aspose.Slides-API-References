---
title: GetBasePlaceholder()
second_title: Aspose.Slides C++ API 參考
description: 傳回基本的佔位符圖形（從版面配置和/或母片投影片中取得，且為目前圖形所繼承的圖形）。
type: docs
weight: 638
url: /zh-hant/aspose.slides/shape/getbaseplaceholder/
---
## Shape::GetBasePlaceholder() 方法

傳回基本的佔位符圖形（從版面配置和/或母片投影片中取得，且為目前圖形繼承自的圖形）。

```cpp
System::SharedPtr<IShape> Aspose::Slides::Shape::GetBasePlaceholder() override
```

## 備註

如果目前圖形未被繼承，將傳回 null。

```cpp
// 取得佔位符圖形的所有（母片/版面/投影片）動畫效果
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"sample.pptx");

System::SharedPtr<ISlide> slide = pres->get_Slide(0);
System::SharedPtr<IShape> shape = slide->get_Shape(0);
System::ArrayPtr<System::SharedPtr<IEffect>> shapeEffects = slide->get_Timeline()->get_MainSequence()->GetEffectsByShape(shape);

System::SharedPtr<IShape> layoutShape = shape->GetBasePlaceholder();
System::ArrayPtr<System::SharedPtr<IEffect>> layoutShapeEffects = slide->get_LayoutSlide()->get_Timeline()->get_MainSequence()->GetEffectsByShape(layoutShape);

System::SharedPtr<IShape> masterShape = layoutShape->GetBasePlaceholder();
System::ArrayPtr<System::SharedPtr<IEffect>> masterShapeEffects = slide->get_LayoutSlide()->get_MasterSlide()->get_Timeline()->get_MainSequence()->GetEffectsByShape(masterShape);
```

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IShape](../../ishape/)
* 類別 [Shape](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)