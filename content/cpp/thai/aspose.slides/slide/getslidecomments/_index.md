---
title: GetSlideComments()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ส่งคืนความคิดเห็นสไลด์ทั้งหมดที่เพิ่มโดยผู้เขียนที่ระบุ
type: docs
weight: 209
url: /th/aspose.slides/slide/getslidecomments/
---
## Slide::GetSlideComments(System::SharedPtr\<ICommentAuthor\>) เมธอด

ส่งคืนความคิดเห็นสไลด์ทั้งหมดที่เพิ่มโดยผู้เขียนที่ระบุ

```cpp
System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::Slide::GetSlideComments(System::SharedPtr<ICommentAuthor> author) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| author | [System::SharedPtr](../../../system/sharedptr/)\<[ICommentAuthor](../../icommentauthor/)\> | ผู้เขียนของความคิดเห็นที่ต้องการหา หรือ null เพื่อคืนค่าความคิดเห็นทั้งหมด |

### ค่าที่ส่งคืน

Array ของ [Comment](../../comment/).

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IComment](../../icomment/)
* คลาส [ICommentAuthor](../../icommentauthor/)
* คลาส [Slide](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)