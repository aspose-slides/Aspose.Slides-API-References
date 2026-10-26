---
title: get_ParentCell()
second_title: مرجع API Aspose.Slides برای C++
description: سلول والد را برمی‌گرداند یا null اگر شیء والد رابط ICell را پیاده‌سازی نکند. فقط‌خواندنی ICell.
type: docs
weight: 79
url: /fa/aspose.slides/itextframe/get_parentcell/
---
## ITextFrame::get_ParentCell() متد


والد سلول یا null را برمی‌گرداند اگر شیء والد رابط [ICell](../../icell/) را پیاده‌سازی نکند. فقط خواندنی [ICell](../../icell/).

```cpp
virtual System::SharedPtr<ICell> Aspose::Slides::ITextFrame::get_ParentCell()=0
```

## توضیحات


نمونه کد زیر نشان می‌دهد 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
System::SharedPtr<Table> table = System::ExplicitCast<Table>(presentation->get_Slide(0)->get_Shape(0));

ASSERT_TRUE(table->idx_get(0, 0)->get_TextFrame()->get_ParentCell() == table->idx_get(0, 0));
```

## موارد مرتبط

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [ICell](../../icell/)
* کلاس [ITextFrame](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)