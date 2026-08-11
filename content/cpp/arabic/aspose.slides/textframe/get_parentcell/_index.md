---
title: get_ParentCell()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يرجع خلية الأصل أو null إذا كان كائن الأصل لا ينفّذ واجهة ICell. للقراءة فقط ICell.
type: docs
weight: 105
url: /ar/aspose.slides/textframe/get_parentcell/
---
## TextFrame::get_ParentCell() طريقة

يرجع خلية الأصل أو null إذا كان كائن الأصل لا ينفّذ واجهة [ICell](../../icell/). للقراءة فقط [ICell](../../icell/).

```cpp
System::SharedPtr<ICell> Aspose::Slides::TextFrame::get_ParentCell() override
```

## ملاحظات

العينة البرمجية التالية تُظهر
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
System::SharedPtr<Table> table = System::ExplicitCast<Table>(presentation->get_Slide(0)->get_Shape(0));

ASSERT_TRUE(table->idx_get(0, 0)->get_TextFrame()->get_ParentCell() == table->idx_get(0, 0));
```

## انظر أيضا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [ICell](../../icell/)
* فئة [TextFrame](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)