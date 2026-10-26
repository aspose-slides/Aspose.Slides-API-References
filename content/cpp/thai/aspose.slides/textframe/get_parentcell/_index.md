---
title: get_ParentCell()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ส่งคืนเซลล์แม่หรือ null หากวัตถุแม่ไม่ได้ทำตามอินเทอร์เฟซ ICell. อ่านอย่างเดียว ICell.
type: docs
weight: 105
url: /th/aspose.slides/textframe/get_parentcell/
---
## TextFrame::get_ParentCell() method


ส่งคืนเซลล์แม่หรือ null หากวัตถุแม่ไม่ได้ทำตามอินเทอร์เฟซ [ICell](../../icell/). อ่านอย่างเดียว [ICell](../../icell/).

```cpp
System::SharedPtr<ICell> Aspose::Slides::TextFrame::get_ParentCell() override
```

## หมายเหตุ


ตัวอย่างโค้ดต่อไปนี้แสดง 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
System::SharedPtr<Table> table = System::ExplicitCast<Table>(presentation->get_Slide(0)->get_Shape(0));

ASSERT_TRUE(table->idx_get(0, 0)->get_TextFrame()->get_ParentCell() == table->idx_get(0, 0));
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [ICell](../../icell/)
* คลาส [TextFrame](../)
* เนมสเปซ [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)