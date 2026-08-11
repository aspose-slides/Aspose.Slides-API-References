---
title: get_ParentCell()
second_title: مرجع API Aspose.Slides برای C++
description: سلول والد را برمی‌گرداند یا null اگر شی والد رابط ICell را پیاده‌سازی نکند. فقط خواندنی ICell.
type: docs
weight: 105
url: /fa/aspose.slides/textframe/get_parentcell/
---
## TextFrame::get_ParentCell() متد

والد سلول را برمی‌گرداند یا null اگر شی والد رابط [ICell](../../icell/) را پیاده‌سازی نکند. فقط خواندنی [ICell](../../icell/).

```cpp
System::SharedPtr<ICell> Aspose::Slides::TextFrame::get_ParentCell() override
```

## توضیحات

نمونه کد زیر را نشان می‌دهد
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
System::SharedPtr<Table> table = System::ExplicitCast<Table>(presentation->get_Slide(0)->get_Shape(0));

ASSERT_TRUE(table->idx_get(0, 0)->get_TextFrame()->get_ParentCell() == table->idx_get(0, 0));
```

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [ICell](../../icell/)
* کلاس [TextFrame](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)