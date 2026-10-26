---
title: get_ParentShape()
second_title: Aspose.Slides for C++ API 참조
description: 부모 객체가 IShape 인터페이스를 구현하지 않을 경우 부모 모양을 반환하거나 null을 반환합니다. 읽기 전용 IShape.
type: docs
weight: 92
url: /ko/aspose.slides/textframe/get_parentshape/
---
## TextFrame::get_ParentShape() 메서드


부모 모양을 반환하거나, 부모 객체가 [IShape](../../ishape/) 인터페이스를 구현하지 않을 경우 null을 반환합니다. 읽기 전용 [IShape](../../ishape/).

```cpp
System::SharedPtr<IShape> Aspose::Slides::TextFrame::get_ParentShape() override
```

## 비고


다음 코드 샘플은 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
System::SharedPtr<AutoShape> autoShape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

ASSERT_TRUE(autoShape->get_TextFrame()->get_ParentShape() == autoShape);
```

## 참고

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IShape](../../ishape/)
* 클래스 [TextFrame](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)