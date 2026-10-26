---
title: IRowCollection
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: เป็นตัวแทนของคอลเลกชันแถวตาราง.
type: docs
url: /th/com.aspose.slides/irowcollection/
---
**อินเทอร์เฟซที่ทำการ Implement ทั้งหมด:**
com.aspose.slides.IGenericCollection
```
public interface IRowCollection extends IGenericCollection<IRow>
```

เป็นตัวแทนของคอลเลกชันแถวตาราง.
## วิธีการ

| วิธีการ | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | รับอิลีเมนต์ที่ตำแหน่งที่ระบุ |
| [addClone(IRow templ, boolean withAttachedRows)](#addClone-com.aspose.slides.IRow-boolean-) | สร้างสำเนาของแถวต้นแบบที่ระบุและแทรกที่ด้านล่างของตาราง |
| [insertClone(int index, IRow templ, boolean withAttachedRows)](#insertClone-int-com.aspose.slides.IRow-boolean-) | สร้างสำเนาของแถวต้นแบบที่ระบุและแทรกที่ตำแหน่งที่ระบุในตาราง |
| [removeAt(int firstRowIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | ลบแถวที่ตำแหน่งที่ระบุออกจากตาราง |
### get_Item(int index) {#get-Item-int-}
```
public abstract IRow get_Item(int index)
```

รับอิลีเมนต์ที่ตำแหน่งที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**ผลลัพธ์:**
[IRow](../../com.aspose.slides/irow)
### addClone(IRow templ, boolean withAttachedRows) {#addClone-com.aspose.slides.IRow-boolean-}
```
public abstract IRow[] addClone(IRow templ, boolean withAttachedRows)
```

สร้างสำเนาของแถวต้นแบบที่ระบุและแทรกที่ด้านล่างของตาราง

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| templ | [IRow](../../com.aspose.slides/irow) | แถวที่ใช้เป็นต้นแบบ |
| withAttachedRows | boolean | เป็นค่า True เพื่อคัดลอกแถวทั้งหมดที่แนบกับแถวต้นแบบ |

**ผลลัพธ์:**
com.aspose.slides.IRow[] - แถวที่เพิ่ม
### insertClone(int index, IRow templ, boolean withAttachedRows) {#insertClone-int-com.aspose.slides.IRow-boolean-}
```
public abstract IRow[] insertClone(int index, IRow templ, boolean withAttachedRows)
```

สร้างสำเนาของแถวต้นแบบที่ระบุและแทรกที่ตำแหน่งที่ระบุในตาราง

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของแถวใหม่ |
| templ | [IRow](../../com.aspose.slides/irow) | แถวที่ใช้เป็นต้นแบบ |
| withAttachedRows | boolean | เป็นค่า True เพื่อคัดลอกแถวทั้งหมดที่แนบกับแถวต้นแบบ |

**ผลลัพธ์:**
com.aspose.slides.IRow[] - แถวที่แทรก
### removeAt(int firstRowIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public abstract void removeAt(int firstRowIndex, boolean withAttachedRows)
```

ลบแถวที่ตำแหน่งที่ระบุออกจากตาราง

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| firstRowIndex | int | ดัชนีของแถวที่ต้องการลบ |
| withAttachedRows | boolean | เป็นค่า True เพื่อทำการลบแถวที่แนบทั้งหมดด้วย |