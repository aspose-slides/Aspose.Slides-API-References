---
title: PointCollection
second_title: Aspose.Slides สำหรับ Java API Reference
description: เป็นคอลเลกชันของจุดแอนิเมชัน.
type: docs
url: /th/com.aspose.slides/pointcollection/
---
**การสืบทอด:**  
java.lang.Object

**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**  
[com.aspose.slides.IPointCollection](../../com.aspose.slides/ipointcollection)  
```
public class PointCollection implements IPointCollection
```

เป็นคอลเลกชันของจุดแอนิเมชัน.

## ตัวสร้าง

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [PointCollection()](#PointCollection--) |  |

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getCount()](#getCount--) | ส่งคืนจำนวนจุดในคอลเลกชัน |
| [get_Item(int index)](#get-Item-int-) | ส่งคืนจุดที่ตำแหน่งที่ระบุ |
| [iterator()](#iterator--) | ส่งคืน enumerator ที่ทำการวนซ้ำผ่านคอลเลกชัน |
| [iteratorJava()](#iteratorJava--) | ส่งคืน java iterator สำหรับคอลเลกชันทั้งหมด |

### PointCollection() {#PointCollection--}
```
public PointCollection()
```

### getCount() {#getCount--}
```
public final int getCount()
```

ส่งคืนจำนวนจุดในคอลเลกชัน. อ่านอย่างเดียว int.

**คืนค่า:**  
int

### get_Item(int index) {#get-Item-int-}
```
public final IPoint get_Item(int index)
```

ส่งคืนจุดที่ตำแหน่งที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีขององค์ประกอบ |

**คืนค่า:**  
[IPoint](../../com.aspose.slides/ipoint) - วัตถุ [IPoint](../../com.aspose.slides/ipoint)

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPoint> iterator()
```

ส่งคืน enumerator ที่ทำการวนซ้ำผ่านคอลเลกชัน.

**คืนค่า:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPoint> - IGenericEnumerator ที่สามารถใช้เพื่อวนซ้ำผ่านคอลเลกชัน

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPoint> iteratorJava()
```

ส่งคืน java iterator สำหรับคอลเลกชันทั้งหมด.

**คืนค่า:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPoint> - java.util.Iterator สำหรับคอลเลกชันทั้งหมด