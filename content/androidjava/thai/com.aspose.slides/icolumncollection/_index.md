---
title: IColumnCollection
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แสดงคอลเลกชันของคอลัมน์ในตาราง.
type: docs
url: /th/com.aspose.slides/icolumncollection/
---
**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**
com.aspose.slides.IGenericCollection
```
public interface IColumnCollection extends IGenericCollection<IColumn>
```

เป็นคอลเลกชันของคอลัมน์ในตาราง.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | คืนค่าคอลัมน์ที่ตำแหน่งที่ระบุ. |
| [addClone(IColumn templ, boolean withAttachedColumns)](#addClone-com.aspose.slides.IColumn-boolean-) | สร้างสำเนาของแถวแม่แบบที่ระบุและแทรกที่ด้านล่างของตาราง. |
| [insertClone(int index, IColumn templ, boolean withAttachedColumns)](#insertClone-int-com.aspose.slides.IColumn-boolean-) | สร้างสำเนาของคอลัมน์แม่แบบที่ระบุและแทรกที่ตำแหน่งที่ระบุในตาราง. |
| [removeAt(int firstColumnIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | ลบคอลัมน์ที่ตำแหน่งที่ระบุจากตาราง. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IColumn get_Item(int index)
```


คืนค่าคอลัมน์ที่ตำแหน่งที่ระบุ. อ่านอย่างเดียว [IColumn](../../com.aspose.slides/icolumn).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**ผลลัพธ์:**
[IColumn](../../com.aspose.slides/icolumn)
### addClone(IColumn templ, boolean withAttachedColumns) {#addClone-com.aspose.slides.IColumn-boolean-}
```
public abstract IColumn[] addClone(IColumn templ, boolean withAttachedColumns)
```


สร้างสำเนาของแถวแม่แบบที่ระบุและแทรกที่ด้านล่างของตาราง.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| templ | [IColumn](../../com.aspose.slides/icolumn) | คอลัมน์ที่ใช้เป็นแม่แบบ. |
| withAttachedColumns | boolean | True เพื่อคัดลอกคอลัมน์ที่แนบกับแถวแม่แบบทั้งหมดด้วย. |

**ผลลัพธ์:**
com.aspose.slides.IColumn[] - คอลัมน์ที่เพิ่ม.
### insertClone(int index, IColumn templ, boolean withAttachedColumns) {#insertClone-int-com.aspose.slides.IColumn-boolean-}
```
public abstract IColumn[] insertClone(int index, IColumn templ, boolean withAttachedColumns)
```


สร้างสำเนาของคอลัมน์แม่แบบที่ระบุและแทรกที่ตำแหน่งที่ระบุในตาราง.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ตำแหน่งของคอลัมน์ใหม่. |
| templ | [IColumn](../../com.aspose.slides/icolumn) | คอลัมน์ที่ใช้เป็นแม่แบบ. |
| withAttachedColumns | boolean | True เพื่อคัดลอกคอลัมน์ที่แนบกับคอลัมน์แม่แบบทั้งหมดด้วย. |

**ผลลัพธ์:**
com.aspose.slides.IColumn[] - คอลัมน์ที่แทรก.
### removeAt(int firstColumnIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public abstract void removeAt(int firstColumnIndex, boolean withAttachedRows)
```


ลบคอลัมน์ที่ตำแหน่งที่ระบุจากตาราง.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| firstColumnIndex | int | ตำแหน่งของคอลัมน์ที่ต้องการลบ. |
| withAttachedRows | boolean | True เพื่อจะลบคอลัมน์ที่แนบทั้งหมดด้วย. |