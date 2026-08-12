---
title: get_ParentCell()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: คืนค่าเซลล์แม่หรือ null หากวัตถุแม่ไม่ทำตามอินเทอร์เฟซ ICell. อ่านอย่างเดียว ICell.
type: docs
weight: 79
url: /th/aspose.slides/itextframe/get_parentcell/
---
## ITextFrame::get_ParentCell() เมธอด

คืนค่าเซลล์แม่หรือ null หากวัตถุแม่ไม่ทำตามอินเทอร์เฟซ [ICell](../../icell/). อ่านอย่างเดียว [ICell](../../icell/).

```cpp
virtual System::SharedPtr<ICell> Aspose::Slides::ITextFrame::get_ParentCell()=0
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
* คลาส [ITextFrame](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)