---
title: PortionCollection
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: เป็นตัวแทนของคอลเลกชันของส่วน.
type: docs
url: /th/com.aspose.slides/portioncollection/
---
**Inheritance:**  
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**  
[com.aspose.slides.IPortionCollection](../../com.aspose.slides/iportioncollection)  
```
public final class PortionCollection extends DomObject<Paragraph> implements IPortionCollection
```

Represents a collection of portions.  
## เมธอด

| Method | Description |
| --- | --- |
| [getCount()](#getCount--) | รับจำนวนขององค์ประกอบที่มีจริงในคอลเลกชันนี้. |
| [isReadOnly()](#isReadOnly--) | รับค่าที่บ่งบอกว่า [IGenericCollection](../../com.aspose.slides/igenericcollection) เป็นแบบอ่านอย่างเดียวหรือไม่. |
| [get_Item(int index)](#get-Item-int-) | รับองค์ประกอบที่ตำแหน่งที่ระบุ. |
| [set_Item(int index, IPortion value)](#set-Item-int-com.aspose.slides.IPortion-) | รับองค์ประกอบที่ตำแหน่งที่ระบุ. |
| [add(IPortion value)](#add-com.aspose.slides.IPortion-) | เพิ่ม Portion ไปยังท้ายของคอลเลกชัน. |
| [indexOf(IPortion item)](#indexOf-com.aspose.slides.IPortion-) | กำหนดดัชนีของรายการที่ระบุใน List. |
| [insert(int index, IPortion value)](#insert-int-com.aspose.slides.IPortion-) | แทรก Portion ลงในคอลเลกชันที่ตำแหน่งที่ระบุ. |
| [clear()](#clear--) | ลบองค์ประกอบทั้งหมดจากคอลเลกชัน. |
| [contains(IPortion item)](#contains-com.aspose.slides.IPortion-) | กำหนดว่า [IGenericCollection](../../com.aspose.slides/igenericcollection) มีค่าที่ระบุหรือไม่. |
| [copyTo(IPortion[] array, int arrayIndex)](#copyTo-com.aspose.slides.IPortion---int-) | คัดลอกองค์ประกอบของ [IGenericCollection](../../com.aspose.slides/igenericcollection) ไปยัง Array โดยเริ่มที่ดัชนีของ Array ที่กำหนด. |
| [remove(IPortion item)](#remove-com.aspose.slides.IPortion-) | ลบการเกิดครั้งแรกของอ็อบเจกต์ที่ระบุจาก [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [removeAt(int index)](#removeAt-int-) | ลบองค์ประกอบที่ตำแหน่งที่ระบุของคอลเลกชัน. |
| [iterator()](#iterator--) | คืนค่า enumerator ที่วนผ่านคอลเลกชัน. |
| [iteratorJava()](#iteratorJava--) | คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด. |

### getCount() {#getCount--}
```
public final int getCount()
```

Gets the number of elements actually contained in the collection. Read-only int.

**คืนค่า:**  
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Gets a value indicating whether the [IGenericCollection](../../com.aspose.slides/igenericcollection) is read-only. Read-only boolean.

**คืนค่า:**  
boolean - true หาก [IGenericCollection](../../com.aspose.slides/igenericcollection) เป็นแบบอ่านอย่างเดียว; มิฉะนั้น, false.

### get_Item(int index) {#get-Item-int-}
```
public final IPortion get_Item(int index)
```

Gets the element at the specified index.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**คืนค่า:**  
[IPortion](../../com.aspose.slides/iportion)

### set_Item(int index, IPortion value) {#set-Item-int-com.aspose.slides.IPortion-}
```
public final void set_Item(int index, IPortion value)
```

Gets the element at the specified index.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |
| value | [IPortion](../../com.aspose.slides/iportion) |  |

### add(IPortion value) {#add-com.aspose.slides.IPortion-}
```
public final void add(IPortion value)
```

Adds a Portion to the end of collection.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IPortion](../../com.aspose.slides/iportion) | Portion ที่จะถูกเพิ่มไปยังท้ายของคอลเลกชัน. |

### indexOf(IPortion item) {#indexOf-com.aspose.slides.IPortion-}
```
public final int indexOf(IPortion item)
```

Determines the index of a specific item in the List.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | อ็อบเจกต์ที่ต้องการค้นหาใน List. |

**คืนค่า:**  
int - ดัชนีของ item หากพบในรายการ; มิฉะนั้น, -1.

### insert(int index, IPortion value) {#insert-int-com.aspose.slides.IPortion-}
```
public final void insert(int index, IPortion value)
```

Inserts a Portion into the collection at the specified index.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีที่เริ่มจาก 0 ที่ Portion ควรจะถูกแทรก. |
| value | [IPortion](../../com.aspose.slides/iportion) | Portion ที่จะถูกแทรก. |

### clear() {#clear--}
```
public final void clear()
```

Removes all elements from the collection.

### contains(IPortion item) {#contains-com.aspose.slides.IPortion-}
```
public final boolean contains(IPortion item)
```

Determines whether the [IGenericCollection](../../com.aspose.slides/igenericcollection) contains a specific value.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | อ็อบเจกต์ที่ต้องการค้นหาใน [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**คืนค่า:**  
boolean - true หากพบ item ใน [IGenericCollection](../../com.aspose.slides/igenericcollection); มิฉะนั้น, false.

### copyTo(IPortion[] array, int arrayIndex) {#copyTo-com.aspose.slides.IPortion---int-}
```
public final void copyTo(IPortion[] array, int arrayIndex)
```

Copies the elements of the [IGenericCollection](../../com.aspose.slides/igenericcollection) to an Array, starting at a particular Array index.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| array | [IPortion\[\]](../../com.aspose.slides/iportion) | Array มิติเดียวที่เป็นปลายทางขององค์ประกอบที่คัดลอกจาก [IGenericCollection](../../com.aspose.slides/igenericcollection). Array ต้องมีการจัดทำดัชนีเริ่มจาก 0. |
| arrayIndex | int | ดัชนีเริ่มจาก 0 ใน array ที่การคัดลอกเริ่มต้น. |

### remove(IPortion item) {#remove-com.aspose.slides.IPortion-}
```
public final boolean remove(IPortion item)
```

Removes the first occurrence of a specific object from the [IGenericCollection](../../com.aspose.slides/igenericcollection).

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | อ็อบเจกต์ที่ต้องการลบจาก [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**คืนค่า:**  
boolean - true หาก item ถูกลบสำเร็จจาก [IGenericCollection](../../com.aspose.slides/igenericcollection); มิฉะนั้น, false. วิธีนี้ยังคืนค่า false หากไม่พบ item ใน [IGenericCollection](../../com.aspose.slides/igenericcollection) ดั้งเดิม.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Removes the element at the specified index of the collection.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีที่เริ่มจาก 0 ขององค์ประกอบที่ต้องลบ. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPortion> iterator()
```

Returns an enumerator that iterates through the collection.

**คืนค่า:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPortion> - IGenericEnumerator ที่สามารถใช้วนผ่านคอลเลกชัน.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPortion> iteratorJava()
```

Returns a java iterator for the entire collection.

**คืนค่า:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPortion> - java.util.Iterator สำหรับคอลเลกชันทั้งหมด.