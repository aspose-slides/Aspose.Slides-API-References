---
title: IColumnCollection
second_title: Aspose.Slides สำหรับ Java API Reference
description: เป็นตัวแทนของคอลเลกชันของคอลัมน์ในตาราง.
type: docs
url: /th/com.aspose.slides/icolumncollection/
---
**ทุกอินเทอร์เฟซที่นำไปใช้:**
com.aspose.slides.IGenericCollection
```
public interface IColumnCollection extends IGenericCollection<IColumn>
```

Represents collection of columns in a table.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | ส่งกลับคอลัมน์ที่ตำแหน่งที่ระบุ. |
| [addClone(IColumn templ, boolean withAttachedColumns)](#addClone-com.aspose.slides.IColumn-boolean-) | สร้างสำเนาของแถวแม่แบบที่ระบุและแทรกลงที่ด้านล่างของตาราง. |
| [insertClone(int index, IColumn templ, boolean withAttachedColumns)](#insertClone-int-com.aspose.slides.IColumn-boolean-) | สร้างสำเนาของคอลัมน์แม่แบบที่ระบุและแทรกลงที่ตำแหน่งที่ระบุในตาราง. |
| [removeAt(int firstColumnIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | ลบคอลัมน์ที่ตำแหน่งที่ระบุออกจากตาราง. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IColumn get_Item(int index)
```

ส่งกลับคอลัมน์ที่ตำแหน่งที่ระบุ. อ่านอย่างเดียว [IColumn](../../com.aspose.slides/icolumn).

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

สร้างสำเนาของแถวแม่แบบที่ระบุและแทรกลงที่ด้านล่างของตาราง.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| templ | [IColumn](../../com.aspose.slides/icolumn) | คอลัมน์ที่ใช้เป็นแม่แบบ. |
| withAttachedColumns | boolean | true เพื่อคัดลอกคอลัมน์ทั้งหมดที่แนบกับแถวแม่แบบด้วย. |

**ผลลัพธ์:**
com.aspose.slides.IColumn[] - คอลัมน์ที่เพิ่ม.
### insertClone(int index, IColumn templ, boolean withAttachedColumns) {#insertClone-int-com.aspose.slides.IColumn-boolean-}
```
public abstract IColumn[] insertClone(int index, IColumn templ, boolean withAttachedColumns)
```

สร้างสำเนาของคอลัมน์แม่แบบที่ระบุและแทรกลงที่ตำแหน่งที่ระบุในตาราง.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ตำแหน่งของคอลัมน์ใหม่. |
| templ | [IColumn](../../com.aspose.slides/icolumn) | คอลัมน์ที่ใช้เป็นแม่แบบ. |
| withAttachedColumns | boolean | true เพื่อคัดลอกคอลัมน์ทั้งหมดที่แนบกับคอลัมน์แม่แบบด้วย. |

**ผลลัพธ์:**
com.aspose.slides.IColumn[] - คอลัมน์ที่แทรก.
### removeAt(int firstColumnIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public abstract void removeAt(int firstColumnIndex, boolean withAttachedRows)
```

ลบคอลัมน์ที่ตำแหน่งที่ระบุออกจากตาราง.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| firstColumnIndex | int | ตำแหน่งของคอลัมน์ที่จะลบ. |
| withAttachedRows | boolean | true เพื่อ ลบคอลัมน์ทั้งหมดที่แนบด้วย. |