---
title: ChartCategoryCollection
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แสดงถึงคอลเลกชันของ
type: docs
url: /th/com.aspose.slides/chartcategorycollection/
---
**การสืบทอด:**
java.lang.Object, com.aspose.slides.DomObject

**ทั้งหมดที่ทำการ Implement อินเทอร์เฟซ:**
[com.aspose.slides.IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
```
public class ChartCategoryCollection extends DomObject<ChartData> implements IChartCategoryCollection
```

แสดงถึงคอลเลกชันของ [ChartCategory](../../com.aspose.slides/chartcategory)
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | ดึงอิลิเมนต์ที่ตำแหน่งที่ระบุ |
| [getUseCells()](#getUseCells--) | หากเป็น true แล้ว worksheet จะใช้สำหรับเก็บหมวดหมู่ (กรณีนี้สนับสนุนหมวดหมู่หลายระดับ) |
| [setUseCells(boolean value)](#setUseCells-boolean-) | หากเป็น true แล้ว worksheet จะใช้สำหรับเก็บหมวดหมู่ (กรณีนี้สนับสนุนหมวดหมู่หลายระดับ) |
| [getGroupingLevelCount()](#getGroupingLevelCount--) | คืนค่าจำนวนระดับการจัดกลุ่มหมวดหมู่ที่ใช้ |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | หากหมวดหมู่มีอยู่ในคอลเลกชัน จะคืนค่ามัน |
| [add(Object value)](#add-java.lang.Object-) | สร้าง [ChartCategory](../../com.aspose.slides/chartcategory) ใหม่จากค่าและเพิ่มเข้าไปในคอลเลกชัน |
| [indexOf(IChartCategory value)](#indexOf-com.aspose.slides.IChartCategory-) | ค้นหา [ChartCategory](../../com.aspose.slides/chartcategory) ที่ระบุและคืนค่าดัชนีที่เริ่มจาก 0 ของการพบครั้งแรกใน Collection ทั้งหมด |
| [remove(IChartCategory value)](#remove-com.aspose.slides.IChartCategory-) | ลบค่าที่ระบุ |
| [removeAt(int index)](#removeAt-int-) | ลบอิลิเมนต์ที่ตำแหน่งที่ระบุ |
| [clear()](#clear--) | ลบอิลิเมนต์ทั้งหมดจากคอลเลกชัน |
| [iterator()](#iterator--) | คืนค่า enumerator ที่วนผ่านคอลเลกชัน |
| [iteratorJava()](#iteratorJava--) | คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด |
| [size()](#size--) | คืนค่าจำนวนอิลิเมนต์ในคอลเลกชัน |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | คัดลอกอิลิเมนต์ทั้งหมดของคอลเลกชันไปยังอาร์เรย์ที่กำหนด |
| [isSynchronized()](#isSynchronized--) | คืนค่าที่บ่งชี้ว่าการเข้าถึง List ถูกซิงโครไนซ์ (ปลอดภัยต่อเธรด) |
| [getSyncRoot()](#getSyncRoot--) | คืนออบเจกต์ที่สามารถใช้เพื่อซิงโครไนซ์การเข้าถึงคอลเลกชัน |

### get_Item(int index) {#get-Item-int-}
```
public final IChartCategory get_Item(int index)
```

ดึงอิลิเมนต์ที่ตำแหน่งที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**คืนค่า:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - อิลิเมนต์ที่ตำแหน่งที่ระบุ

### getUseCells() {#getUseCells--}
```
public final boolean getUseCells()
```

หากเป็น true แล้ว worksheet จะใช้สำหรับเก็บหมวดหมู่ (กรณีนี้สนับสนุนหมวดหมู่หลายระดับ) หากเป็น false แล้ว worksheet จะไม่ใช้สำหรับเก็บค่า (และกรณีนี้ไม่สนับสนุนหมวดหมู่หลายระดับ) Read/write boolean.

**คืนค่า:**
boolean

### setUseCells(boolean value) {#setUseCells-boolean-}
```
public final void setUseCells(boolean value)
```

หากเป็น true แล้ว worksheet จะใช้สำหรับเก็บหมวดหมู่ (กรณีนี้สนับสนุนหมวดหมู่หลายระดับ) หากเป็น false แล้ว worksheet จะไม่ใช้สำหรับเก็บค่า (และกรณีนี้ไม่สนับสนุนหมวดหมู่หลายระดับ) Read/write boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getGroupingLevelCount() {#getGroupingLevelCount--}
```
public final int getGroupingLevelCount()
```

คืนค่าจำนวนระดับการจัดกลุ่มหมวดหมู่ที่ใช้ จำนวนมากกว่าหนึ่งสำหรับหมวดหมู่หลายระดับ Read-only int.

**คืนค่า:**
int

### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public final IChartCategory add(IChartDataCell chartDataCell)
```

หากหมวดหมู่มีอยู่ในคอลเลกชัน จะคืนค่า หากไม่มีจะสร้างหมวดหมู่แผนภูมิใหม่จาก [IChartDataCell](../../com.aspose.slides/ichartdatacell) และเพิ่มเข้าไปในคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | เซลล์ที่ใช้สร้างหมวดหมู่แผนภูมิ |

**คืนค่า:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - หมวดหมู่ที่เพิ่มหรือที่มีอยู่แล้ว

### add(Object value) {#add-java.lang.Object-}
```
public final IChartCategory add(Object value)
```

สร้าง [ChartCategory](../../com.aspose.slides/chartcategory) ใหม่จากค่าและเพิ่มเข้าไปในคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.Object | ค่าที่ให้ |

เมธอดนี้เพิ่ม worksheet ชื่อ AUTO\_DATA และเพิ่มค่าทั้งหมดลงในนั้น หากคุณใช้ [ChartDataWorkbook](../../com.aspose.slides/chartdataworkbook) เพื่อเพิ่มหรือแก้ไขค่าของเซลล์ โปรดตรวจสอบว่าไม่ได้ใช้ worksheet นี้ จำนวนค่าสูงสุดที่เพิ่มโดยเมธอดนี้ต้องไม่เกิน 16711680 |

**คืนค่า:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - เพิ่ม [IChartCategory](../../com.aspose.slides/ichartcategory)

### indexOf(IChartCategory value) {#indexOf-com.aspose.slides.IChartCategory-}
```
public final int indexOf(IChartCategory value)
```

ค้นหา [ChartCategory](../../com.aspose.slides/chartcategory) ที่ระบุและคืนค่าดัชนีที่เริ่มจาก 0 ของการพบครั้งแรกใน Collection ทั้งหมด

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | หมวดหมู่แผนภูมิ |

**คืนค่า:**
int - ดัชนีที่เริ่มจาก 0 ของการพบครั้งแรกของค่าใน CollectionBase ทั้งหมด หากพบ; ไม่เช่นนั้น -1

### remove(IChartCategory value) {#remove-com.aspose.slides.IChartCategory-}
```
public final void remove(IChartCategory value)
```

ลบค่าที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | ค่าที่ต้องการลบ |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

ลบอิลิเมนต์ที่ตำแหน่งที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของหมวดหมู่ที่ต้องการลบ |

### clear() {#clear--}
```
public final void clear()
```

ลบอิลิเมนต์ทั้งหมดจากคอลเลกชัน

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartCategory> iterator()
```

คืนค่า enumerator ที่วนผ่านคอลเลกชัน

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartCategory> - IGenericEnumerator ที่สามารถใช้เพื่อวนผ่านคอลเลกชัน

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartCategory> iteratorJava()
```

คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartCategory> - java.util.Iterator สำหรับคอลเลกชันทั้งหมด

### size() {#size--}
```
public final int size()
```

คืนค่าจำนวนอิลิเมนต์ในคอลเลกชัน Read-only int.

**คืนค่า:**
int

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

คัดลอกอิลิเมนต์ทั้งหมดของคอลเลกชันไปยังอาร์เรย์ที่กำหนด

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | อาร์เรย์เป้าหมาย |
| index | int | ดัชนีเริ่มต้นในอาร์เรย์ |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

คืนค่าที่บ่งชี้ว่าการเข้าถึง List ถูกซิงโครไนซ์ (ปลอดภัยต่อเธรด) Read-only boolean.

**คืนค่า:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

คืนออบเจกต์ที่สามารถใช้เพื่อซิงโครไนซ์การเข้าถึงคอลเลกชัน Read-only Object.

คืนรากการซิงโครไนซ์ Read-only Object.

**คืนค่า:**
java.lang.Object