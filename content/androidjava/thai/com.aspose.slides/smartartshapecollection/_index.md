---
title: SmartArtShapeCollection
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: เป็นคอลเลกชันของรูปร่าง SmartArt
type: docs
url: /th/com.aspose.slides/smartartshapecollection/
---
**การสืบทอด:**  
java.lang.Object

**อินเทอร์เฟซที่ทำไว้ทั้งหมด:**  
[com.aspose.slides.ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)
```
public class SmartArtShapeCollection implements ISmartArtShapeCollection
```

เป็นคอลเลกชันของรูปร่าง SmartArt
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [size()](#size--) | รับจำนวนขององค์ประกอบที่อยู่จริงในคอลเลกชัน. |
| [get_Item(int index)](#get-Item-int-) | รับองค์ประกอบที่ตำแหน่งที่ระบุ. |
| [isSynchronized()](#isSynchronized--) | คืนค่าที่บ่งบอกว่าการเข้าถึงคอลเลกชันเป็นแบบซิงโครไนซ์ (ปลอดภัยต่อเธรด). |
| [getSyncRoot()](#getSyncRoot--) | คืนรากของการซิงโครไนซ์. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | คัดลอกองค์ประกอบทั้งหมดจากคอลเลกชันไปยังอาร์เรย์ที่ระบุ. |
| [iterator()](#iterator--) | คืน enumerator ที่ทำการวนผ่านคอลเลกชัน. |
| [iteratorJava()](#iteratorJava--) | คืน java iterator สำหรับคอลเลกชันทั้งหมด. |
### size() {#size--}
```
public final int size()
```

รับจำนวนขององค์ประกอบที่อยู่จริงในคอลเลกชัน. อ่านอย่างเดียว int.

**คืนค่า:**  
int
### get_Item(int index) {#get-Item-int-}
```
public final ISmartArtShape get_Item(int index)
```

รับองค์ประกอบที่ตำแหน่งที่ระบุ. อ่านอย่างเดียว [SmartArtShape](../../com.aspose.slides/smartartshape).

**พารามิเตอร์:**  
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของรูปร่าง |

**คืนค่า:**  
[ISmartArtShape](../../com.aspose.slides/ismartartshape) - รูปแบบ SmartArt
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

คืนค่าที่บ่งบอกว่าการเข้าถึงคอลเลกชันเป็นแบบซิงโครไนซ์ (ปลอดภัยต่อเธรด). อ่านอย่างเดียว boolean.

**คืนค่า:**  
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

คืนรากของการซิงโครไนซ์. อ่านอย่างเดียว Object.

**คืนค่า:**  
java.lang.Object
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

คัดลอกองค์ประกอบทั้งหมดจากคอลเลกชันไปยังอาร์เรย์ที่ระบุ.

**พารามิเตอร์:**  
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | อาร์เรย์เป้าหมาย. |
| index | int | ดัชนีเริ่มต้นในอาร์เรย์เป้าหมาย. |
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtShape> iterator()
```

คืน enumerator ที่วนผ่านคอลเลกชัน.

**คืนค่า:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtShape> - IGenericEnumerator ที่สามารถใช้เพื่อวนผ่านคอลเลกชัน
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtShape> iteratorJava()
```

คืน java iterator สำหรับคอลเลกชันทั้งหมด.

**คืนค่า:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtShape> - java.util.Iterator สำหรับคอลเลกชันทั้งหมด