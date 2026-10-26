---
title: SmartArtNodeCollection
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: เป็นตัวแทนของคอลเลกชันของโหนด SmartArt.
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

เป็นตัวแทนของคอลเลกชันของโหนด SmartArt.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | คืนค่าโหนดตามดัชนี |
| [size()](#size--) | คืนค่าจำนวนโหนดในคอลเลกชัน (อ่านอย่างเดียว) int |
| [addNode()](#addNode--) | เพิ่มโหนด SmartArt ใหม่หรือโหนดย่อย |
| [removeNode(int index)](#removeNode-int-) | ลบโหนดหรือโหนดย่อยตามดัชนี |
| [removeNode(ISmartArtNode node)](#removeNode-com.aspose.slides.ISmartArtNode-) | ลบโหนดหรือโหนดย่อย |
| [addNodeByPosition(int position)](#addNodeByPosition-int-) | เพิ่มโหนดใหม่ในตำแหน่งที่เลือกของคอลเลกชันโหนด |
| [iterator()](#iterator--) | คืนค่า enumerator ที่ทำการวนผ่านคอลเลกชัน |
| [iteratorJava()](#iteratorJava--) | คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | คัดลอกองค์ประกอบทั้งหมดจากคอลเลกชันไปยังอาเรย์ที่ระบุ |
| [isSynchronized()](#isSynchronized--) | คืนค่าที่ระบุว่าการเข้าถึงคอลเลกชันนี้เป็น synchronized (ปลอดภัยต่อเธรด) |
| [getSyncRoot()](#getSyncRoot--) | คืนค่า synchronization root |
### get_Item(int index) {#get-Item-int-}
```
public final ISmartArtNode get_Item(int index)
```

คืนค่าโหนดตามดัชนี

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีเริ่มจากศูนย์ของอิลิเมนต์ |

**ผลลัพธ์:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - โหนด SmartArt
### size() {#size--}
```
public final int size()
```

คืนค่าจำนวนโหนดในคอลเลกชัน (อ่านอย่างเดียว) int

**ผลลัพธ์:**
int
### addNode() {#addNode--}
```
public final ISmartArtNode addNode()
```

เพิ่มโหนด SmartArt ใหม่หรือโหนดย่อย

**ผลลัพธ์:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - โหนดที่เพิ่ม
### removeNode(int index) {#removeNode-int-}
```
public final void removeNode(int index)
```

ลบโหนดหรือโหนดย่อยตามดัชนี

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีเริ่มจากศูนย์ของโหนด |
### removeNode(ISmartArtNode node) {#removeNode-com.aspose.slides.ISmartArtNode-}
```
public final void removeNode(ISmartArtNode node)
```

ลบโหนดหรือโหนดย่อย

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| node | [ISmartArtNode](../../com.aspose.slides/ismartartnode) | โหนดที่จะลบ |
### addNodeByPosition(int position) {#addNodeByPosition-int-}
```
public final ISmartArtNode addNodeByPosition(int position)
```

เพิ่มโหนดใหม่ในตำแหน่งที่เลือกของคอลเลกชันโหนด

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| position | int | ตำแหน่งโหนดเริ่มจากศูนย์ |
**ผลลัพธ์:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - โหนดที่เพิ่ม
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtNode> iterator()
```

คืนค่า enumerator ที่ทำการวนผ่านคอลเลกชัน

**ผลลัพธ์:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtNode> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtNode> iteratorJava()
```

คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด

**ผลลัพธ์:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtNode> - An java.util.Iterator for the entire collection.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

คัดลอกองค์ประกอบทั้งหมดจากคอลเลกชันไปยังอาเรย์ที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | อาเรย์เป้าหมาย |
| index | int | ดัชนีเริ่มต้นในอาเรย์เป้าหมาย |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

คืนค่าที่ระบุว่าการเข้าถึงคอลเลกชันนี้เป็น synchronized (ปลอดภัยต่อเธรด) อ่านอย่างเดียว  boolean .

**ผลลัพธ์:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

คืนค่า synchronization root. อ่านอย่างเดียว Object.

**ผลลัพธ์:**
java.lang.Object