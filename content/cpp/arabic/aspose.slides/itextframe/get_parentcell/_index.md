---
title: get_ParentCell()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يُعيد الخلية الأصل أو null إذا كان كائن الأصل لا ينفّذ واجهة ICell. للقراءة فقط ICell.
type: docs
weight: 79
url: /ar/aspose.slides/itextframe/get_parentcell/
---
## ITextFrame::get_ParentCell() طريقة

يعيد الخلية الأم أو null إذا كان كائن الأصل لا يدعم واجهة [ICell](../../icell/). للقراءة فقط [ICell](../../icell/).

```cpp
virtual System::SharedPtr<ICell> Aspose::Slides::ITextFrame::get_ParentCell()=0
```

## ملاحظات

العينة البرمجية التالية تظهر
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
System::SharedPtr<Table> table = System::ExplicitCast<Table>(presentation->get_Slide(0)->get_Shape(0));

ASSERT_TRUE(table->idx_get(0, 0)->get_TextFrame()->get_ParentCell() == table->idx_get(0, 0));
```

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [ICell](../../icell/)
* فئة [ITextFrame](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)