---
title: ChartCategoryCollection
second_title: Aspose.Slides สำหรับ Android ผ่านเอกสารอ้างอิง API ของ Java
description: เป็นตัวแทนของคอลเลกชันของ
type: docs
url: /th/com.aspose.slides/chartcategorycollection/
---
**การสืบทอด:**
java.lang.Object, com.aspose.slides.DomObject

**อินเทอร์เฟซที่ใช้งานทั้งหมด:**
[com.aspose.slides.IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
```
public class ChartCategoryCollection extends DomObject<ChartData> implements IChartCategoryCollection
```

เป็นตัวแทนของคอลเลกชันของ [ChartCategory](../../com.aspose.slides/chartcategory)
## เมธอด

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | รับองค์ประกอบที่ตำแหน่งที่ระบุ |
| [getUseCells()](#getUseCells--) | ถ้าเป็น true แล้ว worksheet จะใช้สำหรับเก็บหมวดหมู่ (กรณีนี้สนับสนุนหมวดหมู่หลายระดับ) |
| [setUseCells(boolean value)](#setUseCells-boolean-) | ถ้าเป็น true แล้ว worksheet จะใช้สำหรับเก็บหมวดหมู่ (กรณีนี้สนับสนุนหมวดหมู่หลายระดับ) |
| [getGroupingLevelCount()](#getGroupingLevelCount--) | ส่งคืนจำนวนระดับการจัดกลุ่มหมวดหมู่ที่ใช้ |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | ถ้าหมวดหมู่มีอยู่ในคอลเลกชัน ให้ส่งคืน |
| [add(Object value)](#add-java.lang.Object-) | สร้าง [ChartCategory](../../com.aspose.slides/chartcategory) ใหม่จากค่าและเพิ่มเข้าไปในคอลเลกชัน |
| [indexOf(IChartCategory value)](#indexOf-com.aspose.slides.IChartCategory-) | ค้นหา [ChartCategory](../../com.aspose.slides/chartcategory) ที่ระบุและส่งคืนดัชนีที่เริ่มจากศูนย์ของการพบครั้งแรกในคอลเลกชันทั้งหมด |
| [remove(IChartCategory value)](#remove-com.aspose.slides.IChartCategory-) | ลบค่าที่ระบุ |
| [removeAt(int index)](#removeAt-int-) | ลบองค์ประกอบที่ตำแหน่งที่กำหนด |
| [clear()](#clear--) | ลบทุกองค์ประกอบจากคอลเลกชัน |
| [iterator()](#iterator--) | ส่งคืน enumerator ที่วนซ้ำผ่านคอลเลกชัน |
| [iteratorJava()](#iteratorJava--) | ส่งคืน java iterator สำหรับคอลเลกชันทั้งหมด |
| [size()](#size--) | ส่งคืนจำนวนองค์ประกอบในคอลเลกชัน |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | คัดลอกทุกองค์ประกอบของคอลเลกชันไปยังอาร์เรย์ที่ระบุ |
| [isSynchronized()](#isSynchronized--) | ส่งคืนค่าที่บ่งชี้ว่าการเข้าถึง List มีการซิงโครไนส์ (ปลอดภัยต่อเธรด) |
| [getSyncRoot()](#getSyncRoot--) | ส่งคืนอ็อบเจ็กต์ที่สามารถใช้เพื่อซิงโครไนส์การเข้าถึงคอลเลกชัน |

### get_Item(int index) {#get-Item-int-}
```
public final IChartCategory get_Item(int index)
```

รับองค์ประกอบที่ตำแหน่งที่ระบุ

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**คืนค่า:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - องค์ประกอบที่ตำแหน่งที่ระบุ

### getUseCells() {#getUseCells--}
```
public final boolean getUseCells()
```

ถ้าเป็น true แล้ว worksheet จะใช้สำหรับเก็บหมวดหมู่ (กรณีนี้สนับสนุนหมวดหมู่หลายระดับ) ถ้าเป็น false แล้ว worksheet จะไม่ใช้สำหรับเก็บค่า (และกรณีนี้ไม่สนับสนุนหมวดหมู่หลายระดับ) อ่าน/เขียน boolean.

**คืนค่า:**
boolean

### setUseCells(boolean value) {#setUseCells-boolean-}
```
public final void setUseCells(boolean value)
```

ถ้าเป็น true แล้ว worksheet จะใช้สำหรับเก็บหมวดหมู่ (กรณีนี้สนับสนุนหมวดหมู่หลายระดับ) ถ้าเป็น false แล้ว worksheet จะไม่ใช้สำหรับเก็บค่า (และกรณีนี้ไม่สนับสนุนหมวดหมู่หลายระดับ) อ่าน/เขียน boolean.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getGroupingLevelCount() {#getGroupingLevelCount--}
```
public final int getGroupingLevelCount()
```

ส่งคืนจำนวนระดับการจัดกลุ่มหมวดหมู่ที่ใช้ มีมากกว่าหนึ่งสำหรับหมวดหมู่หลายระดับ อ่านอย่างเดียว int.

**คืนค่า:**
int

### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public final IChartCategory add(IChartDataCell chartDataCell)
```

ถ้าหมวดหมู่มีอยู่ในคอลเลกชัน ให้ส่งคืน มิฉะนั้นสร้างหมวดหมู่แผนภูมิใหม่จาก [IChartDataCell](../../com.aspose.slides/ichartdatacell) และเพิ่มเข้าไปในคอลเลกชัน

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Cell used to create chart category. |

**คืนค่า:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - หมวดหมู่ที่เพิ่มหรือมีอยู่แล้ว

### add(Object value) {#add-java.lang.Object-}
```
public final IChartCategory add(Object value)
```

สร้าง [ChartCategory](../../com.aspose.slides/chartcategory) ใหม่จากค่าและเพิ่มเข้าไปในคอลเลกชัน

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object | The value.

--------------------

เมธอดนี้เพิ่ม worksheet ชื่อ AUTO_DATA และเพิ่มค่าทั้งหมดลงในนั้น หากคุณใช้ [ChartDataWorkbook](../../com.aspose.slides/chartdataworkbook) เพื่อเพิ่มหรือแก้ไขค่าเซลล์ โปรดตรวจสอบว่าไม่ใช้ worksheet นี้ จำนวนค่าสูงสุดที่เพิ่มด้วยเมธอดนี้ต้องไม่เกิน 16711680

**คืนค่า:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - เพิ่ม [IChartCategory](../../com.aspose.slides/ichartcategory).

### indexOf(IChartCategory value) {#indexOf-com.aspose.slides.IChartCategory-}
```
public final int indexOf(IChartCategory value)
```

ค้นหา [ChartCategory](../../com.aspose.slides/chartcategory) ที่ระบุและส่งคืนดัชนีที่เริ่มจากศูนย์ของการพบครั้งแรกในคอลเลกชันทั้งหมด

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | Chart category. |

**คืนค่า:**
int - ดัชนีที่เริ่มจากศูนย์ของการพบครั้งแรกของค่าใน CollectionBase ทั้งหมด หากพบ มิฉะนั้น -1

### remove(IChartCategory value) {#remove-com.aspose.slides.IChartCategory-}
```
public final void remove(IChartCategory value)
```

ลบค่าที่ระบุ

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | The value. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

ลบองค์ประกอบที่ตำแหน่งที่กำหนด

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of a category to remove. |

### clear() {#clear--}
```
public final void clear()
```

ลบทุกองค์ประกอบจากคอลเลกชัน

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartCategory> iterator()
```

ส่งคืน enumerator ที่วนซ้ำผ่านคอลเลกชัน

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartCategory> - IGenericEnumerator ที่สามารถใช้เพื่อวนซ้ำผ่านคอลเลกชัน

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartCategory> iteratorJava()
```

ส่งคืน java iterator สำหรับคอลเลกชันทั้งหมด

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartCategory> - java.util.Iterator สำหรับคอลเลกชันทั้งหมด

### size() {#size--}
```
public final int size()
```

ส่งคืนจำนวนองค์ประกอบในคอลเลกชัน อ่านอย่างเดียว int.

**คืนค่า:**
int

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

คัดลอกทุกองค์ประกอบของคอลเลกชันไปยังอาร์เรย์ที่ระบุ

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Target array. |
| index | int | Starting index in the array. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

ส่งคืนค่าที่บ่งชี้ว่าการเข้าถึง List มีการซิงโครไนส์ (ปลอดภัยต่อเธรด) อ่านอย่างเดียว boolean.

**คืนค่า:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

ส่งคืนอ็อบเจ็กต์ที่สามารถใช้เพื่อซิงโครไนส์การเข้าถึงคอลเลกชัน อ่านอย่างเดียว Object.

ส่งคืนรากการซิงโครไนส์ อ่านอย่างเดียว Object.

**คืนค่า:**
java.lang.Object