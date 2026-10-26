---
title: get_ParentCell()
second_title: Aspose.Slides C++ API 레퍼런스
description: 부모 셀을 반환하거나, 부모 객체가 ICell 인터페이스를 구현하지 않는 경우 null을 반환합니다. 읽기 전용 ICell.
type: docs
weight: 79
url: /ko/aspose.slides/itextframe/get_parentcell/
---
## ITextFrame::get_ParentCell() method

부모 셀을 반환하거나, 부모 객체가 [ICell](../../icell/) 인터페이스를 구현하지 않는 경우 null을 반환합니다. 읽기 전용 [ICell](../../icell/).

```cpp
virtual System::SharedPtr<ICell> Aspose::Slides::ITextFrame::get_ParentCell()=0
```

## 비고

다음 코드 샘플은
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
System::SharedPtr<Table> table = System::ExplicitCast<Table>(presentation->get_Slide(0)->get_Shape(0));

ASSERT_TRUE(table->idx_get(0, 0)->get_TextFrame()->get_ParentCell() == table->idx_get(0, 0));
```

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICell](../../icell/)
* Class [ITextFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)