---
title: GradientStopCollection
second_title: Aspose.Slides สำหรับ Java API Reference
description: เป็นตัวแทนของคอลเลกชันของ gradient stop.
type: docs
url: /th/com.aspose.slides/gradientstopcollection/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**
[com.aspose.slides.IGradientStopCollection](../../com.aspose.slides/igradientstopcollection)
```
public final class GradientStopCollection extends PVIObject implements IGradientStopCollection
```

เป็นตัวแทนของคอลเลกชันของ gradient stop.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [size()](#size--) | คืนค่าจำนวน gradient stop ในคอลเลกชัน. |
| [get_Item(int index)](#get-Item-int-) | คืนค่า gradient stop ตามดัชนี. |
| [add(float position, Color color)](#add-float-java.awt.Color-) | สร้าง gradient stop ใหม่และเพิ่มลงท้ายคอลเลกชัน. |
| [addPresetColor(float position, int presetColor)](#addPresetColor-float-int-) | สร้าง gradient stop ใหม่และเพิ่มลงท้ายคอลเลกชัน. |
| [addSchemeColor(float position, int schemeColor)](#addSchemeColor-float-int-) | สร้าง gradient stop ใหม่และเพิ่มลงท้ายคอลเลกชัน. |
| [insert(int index, float position, Color color)](#insert-int-float-java.awt.Color-) | สร้าง gradient stop ใหม่และแทรกเข้าในคอลเลกชันที่ตำแหน่งที่ระบุ. |
| [insertPresetColor(int index, float position, int presetColor)](#insertPresetColor-int-float-int-) | สร้าง gradient stop ใหม่และแทรกเข้าในคอลเลกชันที่ตำแหน่งที่ระบุ. |
| [insertSchemeColor(int index, float position, int schemeColor)](#insertSchemeColor-int-float-int-) | สร้าง gradient stop ใหม่และแทรกเข้าในคอลเลกชันที่ตำแหน่งที่ระบุ. |
| [removeAt(int index)](#removeAt-int-) | ลบ gradient stop ที่ตำแหน่งที่ระบุ. |
| [clear()](#clear--) | ลบ gradient stop ทั้งหมดจากคอลเลกชัน. |
| [iterator()](#iterator--) | คืนค่า enumerator ที่วนซ้ำผ่านคอลเลกชัน. |
| [iteratorJava()](#iteratorJava--) | คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | คัดลอกทุกองค์ประกอบจากคอลเลกชันไปยังอาร์เรย์ที่ระบุ. |
| [isSynchronized()](#isSynchronized--) | คืนค่าที่บ่งบอกว่าการเข้าถึงคอลเลกชันได้รับการซิงโครไนซ์ (ปลอดภัยต่อเธรด). |
| [getSyncRoot()](#getSyncRoot--) | คืนค่า synchronization root. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


เวอร์ชัน. อ่านอย่างเดียว long.

**คืนค่า:**
long
### size() {#size--}
```
public final int size()
```


คืนค่าจำนวน gradient stop ในคอลเลกชัน. อ่านอย่างเดียว int .

**คืนค่า:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IGradientStop get_Item(int index)
```


คืนค่า gradient stop ตามดัชนี.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**คืนค่า:**
[IGradientStop](../../com.aspose.slides/igradientstop)
### add(float position, Color color) {#add-float-java.awt.Color-}
```
public final IGradientStop add(float position, Color color)
```


สร้าง gradient stop ใหม่และเพิ่มลงท้ายคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| position | float | ตำแหน่งของ gradient stop ใหม่. |
| color | java.awt.Color | สีของ gradient stop ใหม่. |

**คืนค่า:**
[IGradientStop](../../com.aspose.slides/igradientstop) - ดัชนีของ gradient stop ใหม่ในคอลเลกชัน.
### addPresetColor(float position, int presetColor) {#addPresetColor-float-int-}
```
public final IGradientStop addPresetColor(float position, int presetColor)
```


สร้าง gradient stop ใหม่และเพิ่มลงท้ายคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| position | float | ตำแหน่งของ gradient stop ใหม่. |
| presetColor | int | สีของ gradient stop ใหม่. |

**คืนค่า:**
[IGradientStop](../../com.aspose.slides/igradientstop) - ดัชนีของ gradient stop ใหม่ในคอลเลกชัน.
### addSchemeColor(float position, int schemeColor) {#addSchemeColor-float-int-}
```
public final IGradientStop addSchemeColor(float position, int schemeColor)
```


สร้าง gradient stop ใหม่และเพิ่มลงท้ายคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| position | float | ตำแหน่งของ gradient stop ใหม่. |
| schemeColor | int | สีของ gradient stop ใหม่. |

**คืนค่า:**
[IGradientStop](../../com.aspose.slides/igradientstop) - ดัชนีของ gradient stop ใหม่ในคอลเลกชัน.
### insert(int index, float position, Color color) {#insert-int-float-java.awt.Color-}
```
public final void insert(int index, float position, Color color)
```


สร้าง gradient stop ใหม่และแทรกเข้าในคอลเลกชันที่ตำแหน่งที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีในคอลเลกชันที่ gradient stop ใหม่จะถูกแทรก. |
| position | float | ตำแหน่งของ gradient stop ใหม่. |
| color | java.awt.Color | สีของ gradient stop ใหม่. |

### insertPresetColor(int index, float position, int presetColor) {#insertPresetColor-int-float-int-}
```
public final void insertPresetColor(int index, float position, int presetColor)
```


สร้าง gradient stop ใหม่และแทรกเข้าในคอลเลกชันที่ตำแหน่งที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีในคอลเลกชันที่ gradient stop ใหม่จะถูกแทรก. |
| position | float | ตำแหน่งของ gradient stop ใหม่. |
| presetColor | int | สีของ gradient stop ใหม่. |

### insertSchemeColor(int index, float position, int schemeColor) {#insertSchemeColor-int-float-int-}
```
public final void insertSchemeColor(int index, float position, int schemeColor)
```


สร้าง gradient stop ใหม่และแทรกเข้าในคอลเลกชันที่ตำแหน่งที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีในคอลเลกชันที่ gradient stop ใหม่จะถูกแทรก. |
| position | float | ตำแหน่งของ gradient stop ใหม่. |
| schemeColor | int | สีของ gradient stop ใหม่. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


ลบ gradient stop ที่ตำแหน่งที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของ gradient stop ที่จะถูกลบ. |

### clear() {#clear--}
```
public final void clear()
```


ลบ gradient stop ทั้งหมดจากคอลเลกชัน.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStop> iterator()
```


คืนค่า enumerator ที่วนซ้ำผ่านคอลเลกชัน.

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStop> - IGenericEnumerator ที่สามารถใช้วนซ้ำผ่านคอลเลกชัน
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStop> iteratorJava()
```


คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด.

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStop> - java.util.Iterator สำหรับคอลเลกชันทั้งหมด
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


คัดลอกทุกองค์ประกอบจากคอลเลกชันไปยังอาร์เรย์ที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | อาร์เรย์เป้าหมาย. |
| index | int | ดัชนีเริ่มต้นในอาร์เรย์เป้าหมาย. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


คืนค่าที่บ่งบอกว่าการเข้าถึงคอลเลกชันได้รับการซิงโครไนซ์ (ปลอดภัยต่อเธรด). อ่านอย่างเดียว boolean .

**คืนค่า:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


คืนค่า synchronization root. อ่านอย่างเดียว Object.

**คืนค่า:**
java.lang.Object