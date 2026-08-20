---
title: IRowCollection
second_title: Aspose.Slides สำหรับ Java API Reference
description: แสดงชุดแถวของตาราง.
type: docs
url: /th/com.aspose.slides/irowcollection/
---
**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
com.aspose.slides.IGenericCollection
```
public interface IRowCollection extends IGenericCollection<IRow>
```

แสดงชุดแถวของตาราง.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | ดึงเอาองค์ประกอบที่ตำแหน่งที่ระบุ |
| [addClone(IRow templ, boolean withAttachedRows)](#addClone-com.aspose.slides.IRow-boolean-) | สร้างสำเนาของแถวแม่แบบที่ระบุและแทรกลงที่ด้านล่างของตาราง |
| [insertClone(int index, IRow templ, boolean withAttachedRows)](#insertClone-int-com.aspose.slides.IRow-boolean-) | สร้างสำเนาของแถวแม่แบบที่ระบุและแทรกลงในตำแหน่งที่กำหนดของตาราง |
| [removeAt(int firstRowIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | ลบแถวที่ตำแหน่งที่ระบุออกจากตาราง |
### get_Item(int index) {#get-Item-int-}
```
public abstract IRow get_Item(int index)
```

ดึงเอาองค์ประกอบที่ตำแหน่งที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**คืนค่า:**
[IRow](../../com.aspose.slides/irow)
### addClone(IRow templ, boolean withAttachedRows) {#addClone-com.aspose.slides.IRow-boolean-}
```
public abstract IRow[] addClone(IRow templ, boolean withAttachedRows)
```

สร้างสำเนาของแถวแม่แบบที่ระบุและแทรกลงที่ด้านล่างของตาราง

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| templ | [IRow](../../com.aspose.slides/irow) | แถวที่ใช้เป็นแม่แบบ |
| withAttachedRows | boolean | ตั้งค่าเป็น true เพื่อคัดลอกแถวทั้งหมดที่แนบกับแถวแม่แบบด้วย |

**คืนค่า:**
com.aspose.slides.IRow[] - แถวที่เพิ่ม
### insertClone(int index, IRow templ, boolean withAttachedRows) {#insertClone-int-com.aspose.slides.IRow-boolean-}
```
public abstract IRow[] insertClone(int index, IRow templ, boolean withAttachedRows)
```

สร้างสำเนาของแถวแม่แบบที่ระบุและแทรกลงในตำแหน่งที่กำหนดของตาราง

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ตำแหน่งของแถวใหม่ |
| templ | [IRow](../../com.aspose.slides/irow) | แถวที่ใช้เป็นแม่แบบ |
| withAttachedRows | boolean | ตั้งค่าเป็น true เพื่อคัดลอกแถวทั้งหมดที่แนบกับแถวแม่แบบด้วย |

**คืนค่า:**
com.aspose.slides.IRow[] - แถวที่แทรก
### removeAt(int firstRowIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public abstract void removeAt(int firstRowIndex, boolean withAttachedRows)
```

ลบแถวที่ตำแหน่งที่ระบุออกจากตาราง

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| firstRowIndex | int | ตำแหน่งของแถวที่ต้องการลบ |
| withAttachedRows | boolean | ตั้งค่าเป็น true เพื่อลบแถวที่แนบทั้งหมดด้วย |