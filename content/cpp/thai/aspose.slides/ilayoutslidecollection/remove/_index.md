---
title: Remove()
second_title: Aspose.Slides สำหรับ C++ API อ้างอิง
description: ลบเลย์เอาต์ออกจากคอลเลกชัน.
type: docs
weight: 27
url: /th/aspose.slides/ilayoutslidecollection/remove/
---
## ILayoutSlideCollection::Remove(System::SharedPtr\<ILayoutSlide\>) เมธอด

ลบเลย์เอาต์ออกจากคอลเลกชัน.

```cpp
virtual void Aspose::Slides::ILayoutSlideCollection::Remove(System::SharedPtr<ILayoutSlide> value)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | สไลด์การจัดวางที่จะลบออกจากคอลเลกชัน. |

## หมายเหตุ

1) เพื่อหลีกเลี่ยงการโยน PptxEditException ให้ตรวจสอบคุณสมบัติ HasDependingSlides ของ layout ก่อน. 2) คุณสามารถใช้เมธอด [ILayoutSlide::Remove](../../ilayoutslide/remove/) เพื่อทำให้โค้ดง่ายขึ้น. 

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [ILayoutSlide](../../ilayoutslide/)
* คลาส [ILayoutSlideCollection](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)