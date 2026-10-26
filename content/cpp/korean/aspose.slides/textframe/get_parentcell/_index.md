---
title: get_ParentCell()
second_title: Aspose.Slides for C++ API 참조
description: 부모 셀을 반환하거나, 부모 객체가 ICell 인터페이스를 구현하지 않으면 null을 반환합니다. 읽기 전용 ICell.
type: docs
weight: 105
url: /ko/aspose.slides/textframe/get_parentcell/
---
## TextFrame::get_ParentCell() 메서드


부모 셀을 반환하거나, 부모 객체가 [ICell](../../icell/) 인터페이스를 구현하지 않으면 null을 반환합니다. 읽기 전용 [ICell](../../icell/).

```cpp
System::SharedPtr<ICell> Aspose::Slides::TextFrame::get_ParentCell() override
```

## 비고


다음 코드 샘플은 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
System::SharedPtr<Table> table = System::ExplicitCast<Table>(presentation->get_Slide(0)->get_Shape(0));

ASSERT_TRUE(table->idx_get(0, 0)->get_TextFrame()->get_ParentCell() == table->idx_get(0, 0));
```

## 참고

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [ICell](../../icell/)
* 클래스 [TextFrame](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)