---
title: GetBasePlaceholder()
second_title: Aspose.Slides for C++ API 참조
description: 기본 자리 표시자 도형을 반환합니다(현재 도형이 상속받은 레이아웃 및/또는 마스터 슬라이드의 도형).
type: docs
weight: 573
url: /ko/aspose.slides/ishape/getbaseplaceholder/
---
## IShape::GetBasePlaceholder() 메서드

Returns a basic placeholder shape (shape from the layout and/or master slide that the current shape is inherited from).

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShape::GetBasePlaceholder()=0
```

## 비고

A null is returned if the current shape is not inherited.

```cpp
// 자리 표시자 도형의 모든 (마스터/레이아웃/슬라이드) 애니메이션 효과를 가져옵니다
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"sample.pptx");

System::SharedPtr<ISlide> slide = pres->get_Slide(0);
System::SharedPtr<IShape> shape = slide->get_Shape(0);
System::ArrayPtr<System::SharedPtr<IEffect>> shapeEffects = slide->get_Timeline()->get_MainSequence()->GetEffectsByShape(shape);

System::SharedPtr<IShape> layoutShape = shape->GetBasePlaceholder();
System::ArrayPtr<System::SharedPtr<IEffect>> layoutShapeEffects = slide->get_LayoutSlide()->get_Timeline()->get_MainSequence()->GetEffectsByShape(layoutShape);

System::SharedPtr<IShape> masterShape = layoutShape->GetBasePlaceholder();
System::ArrayPtr<System::SharedPtr<IEffect>> masterShapeEffects = slide->get_LayoutSlide()->get_MasterSlide()->get_Timeline()->get_MainSequence()->GetEffectsByShape(masterShape);
```

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IShape](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)