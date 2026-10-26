---
title: IChartCategoryCollection
second_title: Aspose.Slides สำหรับ Java เอกสารอ้างอิง API
description: แสดงถึงคอลเลกชันของ
type: docs
url: /th/com.aspose.slides/ichartcategorycollection/
---
**อินเทอร์เฟซที่ทำการ Implement ทั้งหมด:**
com.aspose.slides.IGenericCollection
```
public interface IChartCategoryCollection extends IGenericCollection<IChartCategory>
```

แสดงถึงคอลเลกชันของ [IChartCategory](../../com.aspose.slides/ichartcategory)
## เมธอด

| เมธอด | รายละเอียด |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | ดึงองค์ประกอบที่ตำแหน่งที่ระบุ |
| [getUseCells()](#getUseCells--) | หากเป็นจริง worksheet จะถูกใช้เพื่อเก็บประเภท (กรณีนี้รองรับประเภทหลายระดับ) |
| [setUseCells(boolean value)](#setUseCells-boolean-) | หากเป็นจริง worksheet จะถูกใช้เพื่อเก็บประเภท (กรณีนี้รองรับประเภทหลายระดับ) |
| [getGroupingLevelCount()](#getGroupingLevelCount--) | คืนจำนวนระดับการจัดกลุ่มประเภทที่ใช้ |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | หากประเภทมีอยู่ในคอลเลกชัน จะคืนค่ามัน |
| [add(Object value)](#add-java.lang.Object-) | สร้าง [IChartCategory](../../com.aspose.slides/ichartcategory) ใหม่จากค่าและเพิ่มลงในคอลเลกชัน |
| [indexOf(IChartCategory value)](#indexOf-com.aspose.slides.IChartCategory-) | ค้นหา [IChartCategory](../../com.aspose.slides/ichartcategory) ที่ระบุและคืนดัชนีเริ่มจากศูนย์ของการพบครั้งแรกภายใน Collection ทั้งหมด |
| [remove(IChartCategory value)](#remove-com.aspose.slides.IChartCategory-) | ลบค่าที่ระบุ |
| [removeAt(int index)](#removeAt-int-) | ลบองค์ประกอบที่ตำแหน่งที่กำหนด |
| [clear()](#clear--) | ลบทุกองค์ประกอบจากคอลเลกชัน |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartCategory get_Item(int index)
```

ดึงองค์ประกอบที่ตำแหน่งที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**ค่าที่คืน:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - องค์ประกอบที่ตำแหน่งที่ระบุ
### getUseCells() {#getUseCells--}
```
public abstract boolean getUseCells()
```

หากเป็นจริง worksheet จะถูกใช้เพื่อเก็บประเภท (กรณีนี้รองรับประเภทหลายระดับ) หากเป็นเท็จ worksheet จะ **ไม่** ถูกใช้เพื่อเก็บค่า (และกรณีนี้ไม่รองรับประเภทหลายระดับ) อ่าน/เขียน boolean

**ค่าที่คืน:**
boolean
### setUseCells(boolean value) {#setUseCells-boolean-}
```
public abstract void setUseCells(boolean value)
```

หากเป็นจริง worksheet จะถูกใช้เพื่อเก็บประเภท (กรณีนี้รองรับประเภทหลายระดับ) หากเป็นเท็จ worksheet จะ **ไม่** ถูกใช้เพื่อเก็บค่า (และกรณีนี้ไม่รองรับประเภทหลายระดับ) อ่าน/เขียน boolean

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getGroupingLevelCount() {#getGroupingLevelCount--}
```
public abstract int getGroupingLevelCount()
```

คืนจำนวนระดับการจัดกลุ่มประเภทที่ใช้ มีมากกว่าหนึ่งสำหรับประเภทหลายระดับ อ่านอย่างเดียว int

**ค่าที่คืน:**
int
### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public abstract IChartCategory add(IChartDataCell chartDataCell)
```

หากประเภทมีอยู่ในคอลเลกชัน จะคืนค่ามัน ถ้าไม่มีจะสร้างประเภทแผนภูมิใหม่จาก [IChartDataCell](../../com.aspose.slides/ichartdatacell) และเพิ่มลงในคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | เซลล์ที่ใช้สร้างประเภทแผนภูมิ |

**ค่าที่คืน:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - ประเภทที่เพิ่มหรือที่มีอยู่แล้ว
### add(Object value) {#add-java.lang.Object-}
```
public abstract IChartCategory add(Object value)
```

สร้าง [IChartCategory](../../com.aspose.slides/ichartcategory) ใหม่จากค่าและเพิ่มลงในคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.Object | ค่า

--------------------

เมธอดนี้เพิ่ม worksheet ที่ชื่อ AUTO_DATA และเพิ่มค่าทั้งหมดลงในนั้น หากคุณใช้ [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook) เพื่อเพิ่มหรือแก้ไขค่าของเซลล์ โปรดแน่ใจว่าไม่ได้ใช้ worksheet นี้ จำนวนค่าสูงสุดที่เพิ่มด้วยเมธอดนี้ต้องไม่เกิน 16711680

**ค่าที่คืน:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - เพิ่ม [IChartCategory](../../com.aspose.slides/ichartcategory) แล้ว
### indexOf(IChartCategory value) {#indexOf-com.aspose.slides.IChartCategory-}
```
public abstract int indexOf(IChartCategory value)
```

ค้นหา [IChartCategory](../../com.aspose.slides/ichartcategory) ที่ระบุและคืนดัชนีเริ่มจากศูนย์ของการพบครั้งแรกภายใน Collection ทั้งหมด

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | ประเภทแผนภูมิ |

**ค่าที่คืน:**
int - ดัชนีเริ่มจากศูนย์ของการพบครั้งแรกของค่าใน CollectionBase ทั้งหมด หากพบ; มิฉะนั้น -1
### remove(IChartCategory value) {#remove-com.aspose.slides.IChartCategory-}
```
public abstract void remove(IChartCategory value)
```

ลบค่าที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | ค่าที่จะลบ |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

ลบองค์ประกอบที่ตำแหน่งที่กำหนด

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของประเภทที่จะลบ |

### clear() {#clear--}
```
public abstract void clear()
```

ลบทุกองค์ประกอบจากคอลเลกชัน