---
title: SmartArtNodeCollection
second_title: Aspose.Slides สำหรับ Java เอกสารอ้างอิง API
description: แสดงถึงคอลเลกชันของโหนด SmartArt.
type: docs
url: /th/com.aspose.slides/smartartnodecollection/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่ใช้งานทั้งหมด:**
[com.aspose.slides.ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
```
public final class SmartArtNodeCollection implements ISmartArtNodeCollection
```

แสดงถึงคอลเลกชันของโหนด SmartArt
## เมธอด

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | คืนค่าโหนดตามดัชนี |
| [size()](#size--) | คืนค่าจำนวนโหนดในคอลเลกชัน อ่านอย่างเดียว int อ่านอย่างเดียว int |
| [addNode()](#addNode--) | เพิ่มโหนด smart art ใหม่หรือโหนดย่อย |
| [removeNode(int index)](#removeNode-int-) | ลบโหนดหรือโหนดย่อยตามดัชนี |
| [removeNode(ISmartArtNode node)](#removeNode-com.aspose.slides.ISmartArtNode-) | ลบโหนดหรือโหนดย่อย |
| [addNodeByPosition(int position)](#addNodeByPosition-int-) | เพิ่มโหนดใหม่ในตำแหน่งที่เลือกของคอลเลกชันโหนด |
| [iterator()](#iterator--) | คืนค่า enumerator ที่วนผ่านคอลเลกชัน |
| [iteratorJava()](#iteratorJava--) | คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | คัดลอกทุกองค์ประกอบจากคอลเลกชันไปยังอาเรย์ที่ระบุ |
| [isSynchronized()](#isSynchronized--) | คืนค่าที่บ่งชี้ว่าการเข้าถึงคอลเลกชันเป็นแบบ synchronized (thread-safe) |
| [getSyncRoot()](#getSyncRoot--) | คืนค่า synchronization root |
### get_Item(int index) {#get-Item-int-}
```
public final ISmartArtNode get_Item(int index)
```

คืนค่าโหนดตามดัชนี

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีเริ่มต้นจากศูนย์ขององค์ประกอบ |

**คืนค่า:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - โหนด SmartArt
### size() {#size--}
```
public final int size()
```

คืนค่าจำนวนโหนดในคอลเลกชัน อ่านอย่างเดียว int อ่านอย่างเดียว int

**คืนค่า:**
int
### addNode() {#addNode--}
```
public final ISmartArtNode addNode()
```

เพิ่มโหนด smart art ใหม่หรือโหนดย่อย

**คืนค่า:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - โหนดที่เพิ่ม
### removeNode(int index) {#removeNode-int-}
```
public final void removeNode(int index)
```

ลบโหนดหรือโหนดย่อยตามดัชนี

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีเริ่มต้นจากศูนย์ของโหนด |

### removeNode(ISmartArtNode node) {#removeNode-com.aspose.slides.ISmartArtNode-}
```
public final void removeNode(ISmartArtNode node)
```

ลบโหนดหรือโหนดย่อย

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| node | [ISmartArtNode](../../com.aspose.slides/ismartartnode) | โหนดที่ต้องการลบ |

### addNodeByPosition(int position) {#addNodeByPosition-int-}
```
public final ISmartArtNode addNodeByPosition(int position)
```

เพิ่มโหนดใหม่ในตำแหน่งที่เลือกของคอลเลกชันโหนด

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| position | int | ตำแหน่งโหนดเริ่มต้นจากศูนย์ |

**คืนค่า:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - โหนดที่เพิ่ม
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtNode> iterator()
```

คืนค่า enumerator ที่วนผ่านคอลเลกชัน

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtNode> - IGenericEnumerator ที่สามารถใช้วนผ่านคอลเลกชัน
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtNode> iteratorJava()
```

คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtNode> - java.util.Iterator สำหรับคอลเลกชันทั้งหมด
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

คัดลอกทุกองค์ประกอบจากคอลเลกชันไปยังอาเรย์ที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | อาเรย์เป้าหมาย |
| index | int | ดัชนีเริ่มต้นในอาเรย์เป้าหมาย |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

คืนค่าที่บ่งชี้ว่าการเข้าถึงคอลเลกชันเป็นแบบ synchronized (thread-safe) อ่านอย่างเดียว boolean

**คืนค่า:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

คืนค่า synchronization root อ่านอย่างเดียว Object

**คืนค่า:**
java.lang.Object