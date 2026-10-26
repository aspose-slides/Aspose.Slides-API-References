---
title: BehaviorCollection
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ Java
description: เป็นตัวแทนของคอลเลกชันของเอฟเฟกต์พฤติกรรม.
type: docs
url: /th/com.aspose.slides/behaviorcollection/
---
**การสืบทอด:**
java.lang.Object

**ส่วนต่อประสานที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)
```
public class BehaviorCollection implements IBehaviorCollection
```

แสดง collection ของพฤติกรรมที่ส่งผล.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getCount()](#getCount--) | Returns the number of behaviors in a collection. |
| [isReadOnly()](#isReadOnly--) | Gets a value indicating whether the [IGenericCollection](../../com.aspose.slides/igenericcollection) is read-only. |
| [add(IBehavior item)](#add-com.aspose.slides.IBehavior-) | Add new behavior to a collection. |
| [indexOf(IBehavior item)](#indexOf-com.aspose.slides.IBehavior-) | Determines the index of a specific item in the List. |
| [insert(int index, IBehavior item)](#insert-int-com.aspose.slides.IBehavior-) | Inserts new behavior to a collection at the specified index. |
| [copyTo(IBehavior[] array, int arrayIndex)](#copyTo-com.aspose.slides.IBehavior---int-) | Copies the elements of the [IGenericCollection](../../com.aspose.slides/igenericcollection) to an Array, starting at a particular Array index. |
| [remove(IBehavior item)](#remove-com.aspose.slides.IBehavior-) | Removes specified behavior from a collection. |
| [removeAt(int index)](#removeAt-int-) | Removes behavior from a collection at the specified index. |
| [clear()](#clear--) | Removes all behaviors from a collection. |
| [contains(IBehavior item)](#contains-com.aspose.slides.IBehavior-) | Determines whether the [IGenericCollection](../../com.aspose.slides/igenericcollection) contains a specific value. |
| [get_Item(int index)](#get-Item-int-) | Returns a behavior at the specified index. |
| [set_Item(int index, IBehavior value)](#set-Item-int-com.aspose.slides.IBehavior-) | Sets a behavior at the specified index. |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [iteratorJava()](#iteratorJava--) | Returns a java iterator for the entire collection. |
### getCount() {#getCount--}
```
public final int getCount()
```


คืนค่าจำนวนพฤติกรรมในคอลเลกชัน. อ่านอย่างเดียว int.

**คืนค่า:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```


รับค่าบ่งบอกว่า [IGenericCollection](../../com.aspose.slides/igenericcollection) เป็นแบบอ่านอย่างเดียว. อ่านอย่างเดียว boolean.

**คืนค่า:**
boolean - true if the [IGenericCollection](../../com.aspose.slides/igenericcollection) is read-only; otherwise, false.
### add(IBehavior item) {#add-com.aspose.slides.IBehavior-}
```
public final void add(IBehavior item)
```


เพิ่ม behavior ใหม่เข้าไปในคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Behavior to add. |

### indexOf(IBehavior item) {#indexOf-com.aspose.slides.IBehavior-}
```
public final int indexOf(IBehavior item)
```


กำหนดตำแหน่งของรายการเฉพาะใน List.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | The object to locate in the List. |

**คืนค่า:**
int - The index of item if found in the list; otherwise, -1.
### insert(int index, IBehavior item) {#insert-int-com.aspose.slides.IBehavior-}
```
public final void insert(int index, IBehavior item)
```


Inserts new behavior to a collection at the specified index.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | Index where new behavior should be inserted. |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Behavior to insert. |

### copyTo(IBehavior[] array, int arrayIndex) {#copyTo-com.aspose.slides.IBehavior---int-}
```
public final void copyTo(IBehavior[] array, int arrayIndex)
```


Copies the elements of the [IGenericCollection](../../com.aspose.slides/igenericcollection) to an Array, starting at a particular Array index.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| array | [IBehavior\[\]](../../com.aspose.slides/ibehavior) | Array แบบหนึ่งมิติที่เป็นตำแหน่งปลายทางขององค์ประกอบที่คัดลอกจาก [IGenericCollection](../../com.aspose.slides/igenericcollection). Array ต้องมีการจัดทำดัชนีเริ่มจากศูนย์. |
| arrayIndex | int | ดัชนีเริ่มจากศูนย์ใน array ที่การคัดลอกเริ่มต้น. |

### remove(IBehavior item) {#remove-com.aspose.slides.IBehavior-}
```
public final boolean remove(IBehavior item)
```


Removes specified behavior from a collection.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Behavior to remove. |

**คืนค่า:**
boolean
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Removes behavior from a collection at the specified index.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | Index of a behavior to remove. |

### clear() {#clear--}
```
public final void clear()
```


Removes all behaviors from a collection.

### contains(IBehavior item) {#contains-com.aspose.slides.IBehavior-}
```
public final boolean contains(IBehavior item)
```


กำหนดว่าที่ [IGenericCollection](../../com.aspose.slides/igenericcollection) มีค่าที่ระบุหรือไม่.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | The object to locate in the [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**คืนค่า:**
boolean - true if item is found in the [IGenericCollection](../../com.aspose.slides/igenericcollection); otherwise, false.
### get_Item(int index) {#get-Item-int-}
```
public final IBehavior get_Item(int index)
```


คืนค่า behavior ที่ตำแหน่งที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | Index of a behavior to return. |

**คืนค่า:**
[IBehavior](../../com.aspose.slides/ibehavior) - Animation behavior.
### set_Item(int index, IBehavior value) {#set-Item-int-com.aspose.slides.IBehavior-}
```
public final void set_Item(int index, IBehavior value)
```


Sets a behavior at the specified index.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | Index of a behavior to return. |
| value | [IBehavior](../../com.aspose.slides/ibehavior) |  |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehavior> iterator()
```


คืนค่า enumerator ที่วนซ้ำผ่านคอลเลกชัน.

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehavior> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehavior> iteratorJava()
```


คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด.

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehavior> - An java.util.Iterator for the entire collection.