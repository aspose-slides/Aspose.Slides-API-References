---
title: ICellCollection
second_title: Aspose.Slides for Android ผ่าน Java API Reference
description: เป็นตัวแทนของคอลเลกชันของเซลล์.
type: docs
url: /th/com.aspose.slides/icellcollection/
---
**ทั้งหมดที่ทำตามอินเทอร์เฟซ:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), com.aspose.slides.IGenericCollection
```
public interface ICellCollection extends ISlideComponent, IGenericCollection<ICell>
```

เป็นตัวแทนของคอลเลกชันของเซลล์.
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | คืนค่าเซลล์ตามตำแหน่งของมัน. |

### get_Item(int index) {#get-Item-int-}
```
public abstract ICell get_Item(int index)
```

คืนค่าเซลล์ตามตำแหน่งของมัน. อ่านอย่างเดียว [ICell](../../com.aspose.slides/icell).

--------------------

อ็อบเจกต์ CellEx หนึ่งตัวอาจถูกคืนค่าสำหรับหลายดัชนีในกรณีที่เซลล์ถูกรวมเข้าด้วยกัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**คืนค่า:**
[ICell](../../com.aspose.slides/icell)