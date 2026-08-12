---
title: GetSlideComments()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ส่งคืนคอมเมนต์ของสไลด์ทั้งหมดที่เพิ่มโดยผู้เขียนเฉพาะ
type: docs
weight: 118
url: /th/aspose.slides/islide/getslidecomments/
---
## ISlide::GetSlideComments(System::SharedPtr\<ICommentAuthor\>) เมธอด

ส่งคืนคอมเมนต์ของสไลด์ทั้งหมดที่เพิ่มโดยผู้เขียนเฉพาะ

```cpp
virtual System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::ISlide::GetSlideComments(System::SharedPtr<ICommentAuthor> author)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| author | [System::SharedPtr](../../../system/sharedptr/)\<[ICommentAuthor](../../icommentauthor/)\> | ผู้เขียนของคอมเมนต์ที่ต้องการค้นหา หรือ null เพื่อส่งคืนคอมเมนต์ทั้งหมด |

### ค่าที่ส่งคืน

อาร์เรย์ของ [IComment](../../icomment/).

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IComment](../../icomment/)
* คลาส [ICommentAuthor](../../icommentauthor/)
* คลาส [ISlide](../)
* เนมสเปซ [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)