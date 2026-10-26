---
title: IBehaviorCollection
second_title: Aspose.Slides สำหรับ Java API Reference
description: แสดงถึงคอลเลกชันของพฤติกรรมเอฟเฟกต์.
type: docs
url: /th/com.aspose.slides/ibehaviorcollection/
---
**ส่วนต่อประสานที่นำไปใช้ทั้งหมด:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IBehaviorCollection extends System.Collections.Generic.IGenericEnumerable<IBehavior>
```

แสดงถึงคอลเล็กชันของเอฟเฟกต์พฤติกรรม.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | คืนพฤติกรรมที่ตำแหน่งที่กำหนด. |
| [set_Item(int index, IBehavior value)](#set-Item-int-com.aspose.slides.IBehavior-) | คืนพฤติกรรมที่ตำแหน่งที่กำหนด. |
| [getCount()](#getCount--) | คืนจำนวนพฤติกรรมในคอลเล็กชัน. |
| [add(IBehavior item)](#add-com.aspose.slides.IBehavior-) | เพิ่มพฤติกรรมใหม่ลงในคอลเล็กชัน. |
| [indexOf(IBehavior item)](#indexOf-com.aspose.slides.IBehavior-) | กำหนดดัชนีของรายการเฉพาะใน List. |
| [insert(int index, IBehavior item)](#insert-int-com.aspose.slides.IBehavior-) | แทรกพฤติกรรมใหม่ลงในคอลเล็กชันที่ตำแหน่งที่กำหนด. |
| [remove(IBehavior item)](#remove-com.aspose.slides.IBehavior-) | ลบพฤติกรรมที่ระบุออกจากคอลเล็กชัน. |
| [removeAt(int index)](#removeAt-int-) | ลบพฤติกรรมจากคอลเล็กชันที่ตำแหน่งที่กำหนด. |
| [clear()](#clear--) | ลบพฤติกรรมทั้งหมดออกจากคอลเล็กชัน. |
| [contains(IBehavior item)](#contains-com.aspose.slides.IBehavior-) | กำหนดว่าค่า [IGenericCollection](../../com.aspose.slides/igenericcollection) มีค่าที่ระบุหรือไม่. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IBehavior get_Item(int index)
```


คืนพฤติกรรมที่ตำแหน่งที่กำหนด.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของพฤติกรรมที่จะคืน. |

**คืนค่า:**
[IBehavior](../../com.aspose.slides/ibehavior) - พฤติกรรมแอนิเมชัน.
### set_Item(int index, IBehavior value) {#set-Item-int-com.aspose.slides.IBehavior-}
```
public abstract void set_Item(int index, IBehavior value)
```


คืนพฤติกรรมที่ตำแหน่งที่กำหนด.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของพฤติกรรมที่จะคืน. |
| value | [IBehavior](../../com.aspose.slides/ibehavior) |  |

### getCount() {#getCount--}
```
public abstract int getCount()
```


คืนจำนวนพฤติกรรมในคอลเล็กชัน. อ่านอย่างเดียว int.

**คืนค่า:**
int
### add(IBehavior item) {#add-com.aspose.slides.IBehavior-}
```
public abstract void add(IBehavior item)
```


เพิ่มพฤติกรรมใหม่ลงในคอลเล็กชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | พฤติกรรมที่จะเพิ่ม. |

### indexOf(IBehavior item) {#indexOf-com.aspose.slides.IBehavior-}
```
public abstract int indexOf(IBehavior item)
```


กำหนดดัชนีของรายการเฉพาะใน List.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | วัตถุที่จะค้นหาใน List. |

**คืนค่า:**
int - ดัชนีของรายการหากพบในรายการ; มิฉะนั้น, -1.
### insert(int index, IBehavior item) {#insert-int-com.aspose.slides.IBehavior-}
```
public abstract void insert(int index, IBehavior item)
```


แทรกพฤติกรรมใหม่ลงในคอลเล็กชันที่ตำแหน่งที่กำหนด.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีที่พฤติกรรมใหม่ควรถูกแทรก. |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | พฤติกรรมที่จะแทรก. |

### remove(IBehavior item) {#remove-com.aspose.slides.IBehavior-}
```
public abstract boolean remove(IBehavior item)
```


ลบพฤติกรรมที่ระบุออกจากคอลเล็กชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | พฤติกรรมที่จะลบ. |

**คืนค่า:**
boolean - true หากพฤติกรรมถูกลบสำเร็จ boolean
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


ลบพฤติกรรมจากคอลเล็กชันที่ตำแหน่งที่กำหนด.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของพฤติกรรมที่จะลบ. |

### clear() {#clear--}
```
public abstract void clear()
```


ลบพฤติกรรมทั้งหมดออกจากคอลเล็กชัน.

### contains(IBehavior item) {#contains-com.aspose.slides.IBehavior-}
```
public abstract boolean contains(IBehavior item)
```


กำหนดว่าค่า [IGenericCollection](../../com.aspose.slides/igenericcollection) มีค่าที่ระบุหรือไม่.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | วัตถุที่จะค้นหาใน [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**คืนค่า:**
boolean - true หากพบรายการใน [IGenericCollection](../../com.aspose.slides/igenericcollection); มิฉะนั้น, false.