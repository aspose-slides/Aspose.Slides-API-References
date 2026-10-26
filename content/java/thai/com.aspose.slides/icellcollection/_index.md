---
title: ICellCollection
second_title: Aspose.Slides สำหรับ Java API Reference
description: แสดงชุดของเซลล์.
type: docs
url: /th/com.aspose.slides/icellcollection/
---
**อินเทอร์เฟซที่ใช้งานทั้งหมด:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), com.aspose.slides.IGenericCollection
```
public interface ICellCollection extends ISlideComponent, IGenericCollection<ICell>
```

แสดงชุดของเซลล์.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | ส่งคืนเซลล์ตามตำแหน่งของมัน. |

### get_Item(int index) {#get-Item-int-}
```
public abstract ICell get_Item(int index)
```

ส่งคืนเซลล์ตามตำแหน่งของมัน. อ่านอย่างเดียว [ICell](../../com.aspose.slides/icell).

--------------------

อ็อบเจ็กต์ CellEx หนึ่งตัวอาจถูกส่งคืนสำหรับหลายดัชนีในกรณีที่เซลล์ถูกรวมเข้าด้วยกัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**ค่าที่ส่งกลับ:**
[ICell](../../com.aspose.slides/icell)