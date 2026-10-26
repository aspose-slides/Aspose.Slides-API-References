---
title: IChartCategoryCollection
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API Java
description: เป็นคอลเลกชันของ
type: docs
url: /th/com.aspose.slides/ichartcategorycollection/
---
**อินเทอร์เฟซที่ทำการนำไปใช้ทั้งหมด:**
com.aspose.slides.IGenericCollection
```
public interface IChartCategoryCollection extends IGenericCollection<IChartCategory>
```

แสดงถึงคอลเลกชันของ [IChartCategory](../../com.aspose.slides/ichartcategory)
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | รับอิลีเมนต์ที่ตำแหน่งที่ระบุ |
| [getUseCells()](#getUseCells--) | ถ้าเป็นจริง แล้ว worksheet จะใช้สำหรับเก็บหมวดหมู่ (กรณีนี้รองรับหมวดหมู่หลายระดับ) |
| [setUseCells(boolean value)](#setUseCells-boolean-) | ถ้าเป็นจริง แล้ว worksheet จะใช้สำหรับเก็บหมวดหมู่ (กรณีนี้รองรับหมวดหมู่หลายระดับ) |
| [getGroupingLevelCount()](#getGroupingLevelCount--) | คืนจำนวนระดับการจัดกลุ่มหมวดหมู่ที่ใช้ |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | หากหมวดหมู่มีอยู่ในคอลเลกชัน จะคืนค่า |
| [add(Object value)](#add-java.lang.Object-) | สร้าง [IChartCategory](../../com.aspose.slides/ichartcategory) ใหม่จากค่าและเพิ่มเข้าไปในคอลเลกชัน |
| [indexOf(IChartCategory value)](#indexOf-com.aspose.slides.IChartCategory-) | ค้นหา [IChartCategory](../../com.aspose.slides/ichartcategory) ที่ระบุและคืนดัชนีที่เริ่มจากศูนย์ของการพบครั้งแรกใน Collection ทั้งหมด |
| [remove(IChartCategory value)](#remove-com.aspose.slides.IChartCategory-) | ลบค่าที่ระบุ |
| [removeAt(int index)](#removeAt-int-) | ลบอิลีเมนต์ที่ตำแหน่งที่กำหนด |
| [clear()](#clear--) | ลบทุกอิลีเมนต์จากคอลเลกชัน |

### get_Item(int index) {#get-Item-int-}
```
public abstract IChartCategory get_Item(int index)
```

รับอิลีเมนต์ที่ตำแหน่งที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**คืนค่า:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - อิลีเมนต์ที่ตำแหน่งที่ระบุ

### getUseCells() {#getUseCells--}
```
public abstract boolean getUseCells()
```

ถ้าเป็นจริงแล้ว worksheet จะใช้สำหรับเก็บหมวดหมู่ (กรณีนี้รองรับหมวดหมู่หลายระดับ) หากเป็นเท็จแล้ว worksheet จะไม่ได้ใช้สำหรับเก็บค่า (และกรณีนี้ไม่รองรับหมวดหมู่หลายระดับ) อ่าน/เขียน ตัวบูลีน

**คืนค่า:**
boolean

### setUseCells(boolean value) {#setUseCells-boolean-}
```
public abstract void setUseCells(boolean value)
```

ถ้าเป็นจริงแล้ว worksheet จะใช้สำหรับเก็บหมวดหมู่ (กรณีนี้รองรับหมวดหมู่หลายระดับ) หากเป็นเท็จแล้ว worksheet จะไม่ได้ใช้สำหรับเก็บค่า (และกรณีนี้ไม่รองรับหมวดหมู่หลายระดับ) อ่าน/เขียน ตัวบูลีน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getGroupingLevelCount() {#getGroupingLevelCount--}
```
public abstract int getGroupingLevelCount()
```

คืนจำนวนระดับการจัดกลุ่มของหมวดหมู่ที่ใช้ มีมากกว่าหนึ่งสำหรับหมวดหมู่หลายระดับ อ่านอย่างเดียว int

**คืนค่า:**
int

### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public abstract IChartCategory add(IChartDataCell chartDataCell)
```

หากหมวดหมู่มีอยู่ในคอลเลกชัน จะคืนค่า มิฉะนั้นสร้างหมวดหมู่แผนภูมิใหม่จาก [IChartDataCell](../../com.aspose.slides/ichartdatacell) และเพิ่มเข้าไปในคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | เซลล์ที่ใช้สร้างหมวดหมู่แผนภูมิ |

**คืนค่า:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - เพิ่มหรือหมวดหมู่ที่มีอยู่

### add(Object value) {#add-java.lang.Object-}
```
public abstract IChartCategory add(Object value)
```

สร้าง [IChartCategory](../../com.aspose.slides/ichartcategory) ใหม่จากค่าและเพิ่มเข้าไปในคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.Object | ค่า |

--------------------

เมธอดนี้จะเพิ่ม worksheet ชื่อ AUTO_DATA และเพิ่มค่าทั้งหมดลงไป หากคุณใช้ [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook) เพื่อเพิ่มหรือแก้ไขค่าเซลล์ ให้แน่ใจว่าคุณไม่ได้ใช้ worksheet นี้ จำนวนค่าสูงสุดที่เพิ่มโดยใช้เมธอดนี้ต้องไม่เกิน 16711680 |

**คืนค่า:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - เพิ่ม [IChartCategory](../../com.aspose.slides/ichartcategory).

### indexOf(IChartCategory value) {#indexOf-com.aspose.slides.IChartCategory-}
```
public abstract int indexOf(IChartCategory value)
```

ค้นหา [IChartCategory](../../com.aspose.slides/ichartcategory) ที่ระบุและคืนดัชนีเริ่มจากศูนย์ของการพบครั้งแรกใน Collection ทั้งหมด

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | หมวดหมู่แผนภูมิ |

**คืนค่า:**
int - ดัชนีเริ่มจากศูนย์ของการพบครั้งแรกของค่าใน CollectionBase ทั้งหมด หากพบ; หากไม่พบให้คืนค่า -1

### remove(IChartCategory value) {#remove-com.aspose.slides.IChartCategory-}
```
public abstract void remove(IChartCategory value)
```

ลบค่าที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | ค่า |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

ลบอิลีเมนต์ที่ตำแหน่งที่กำหนด

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของหมวดหมู่ที่จะลบ |

### clear() {#clear--}
```
public abstract void clear()
```

ลบอิลีเมนต์ทั้งหมดจากคอลเลกชัน