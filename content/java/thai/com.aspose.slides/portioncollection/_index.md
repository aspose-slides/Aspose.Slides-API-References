---
title: PortionCollection
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ Java
description: แสดงคอลเล็กชันของ Portion.
type: docs
url: /th/com.aspose.slides/portioncollection/
---
**สืบทอด:**  
java.lang.Object, com.aspose.slides.DomObject

**อินเทอร์เฟซที่ทำการ Implement ทั้งหมด:**  
[com.aspose.slides.IPortionCollection](../../com.aspose.slides/iportioncollection)
```
public final class PortionCollection extends DomObject<Paragraph> implements IPortionCollection
```

แสดงถึงคอลเล็กชันของ Portion.

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getCount()](#getCount--) | รับจำนวนขององค์ประกอบที่จริงๆ อยู่ในคอลเล็กชัน |
| [isReadOnly()](#isReadOnly--) | รับค่าที่บ่งชี้ว่า [IGenericCollection](../../com.aspose.slides/igenericcollection) เป็นแบบอ่านอย่างเดียว |
| [get_Item(int index)](#get-Item-int-) | รับองค์ประกอบที่ตำแหน่งดัชนีที่ระบุ |
| [set_Item(int index, IPortion value)](#set-Item-int-com.aspose.slides.IPortion-) | รับองค์ประกอบที่ตำแหน่งดัชนีที่ระบุ |
| [add(IPortion value)](#add-com.aspose.slides.IPortion-) | เพิ่ม Portion ไปที่ท้ายของคอลเล็กชัน |
| [indexOf(IPortion item)](#indexOf-com.aspose.slides.IPortion-) | กำหนดดัชนีของ item เฉพาะใน List |
| [insert(int index, IPortion value)](#insert-int-com.aspose.slides.IPortion-) | แทรก Portion เข้าในคอลเล็กชันที่ตำแหน่งดัชนีที่ระบุ |
| [clear()](#clear--) | ลบทุกองค์ประกอบออกจากคอลเล็กชัน |
| [contains(IPortion item)](#contains-com.aspose.slides.IPortion-) | กำหนดว่า [IGenericCollection](../../com.aspose.slides/igenericcollection) มีค่าที่ระบุหรือไม่ |
| [copyTo(IPortion[] array, int arrayIndex)](#copyTo-com.aspose.slides.IPortion---int-) | คัดลอกองค์ประกอบของ [IGenericCollection](../../com.aspose.slides/igenericcollection) ไปยัง Array เริ่มจากตำแหน่งดัชนีของ Array ที่ระบุ |
| [remove(IPortion item)](#remove-com.aspose.slides.IPortion-) | ลบการเกิดครั้งแรกของอ็อบเจ็กต์ที่ระบุจาก [IGenericCollection](../../com.aspose.slides/igenericcollection) |
| [removeAt(int index)](#removeAt-int-) | ลบองค์ประกอบที่ตำแหน่งดัชนีที่ระบุในคอลเล็กชัน |
| [iterator()](#iterator--) | คืน enumerator ที่ทำการวนซ้ำผ่านคอลเล็กชัน |
| [iteratorJava()](#iteratorJava--) | คืน java iterator สำหรับคอลเล็กชันทั้งหมด |

### getCount() {#getCount--}
```
public final int getCount()
```

รับจำนวนขององค์ประกอบที่จริงๆ อยู่ในคอลเล็กชัน อ่านอย่างเดียว int.

**คืนค่า:**  
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

รับค่าที่บ่งชี้ว่า [IGenericCollection](../../com.aspose.slides/igenericcollection) เป็นแบบอ่านอย่างเดียว อ่านอย่างเดียว boolean.

**คืนค่า:**  
boolean - true หาก [IGenericCollection](../../com.aspose.slides/igenericcollection) เป็นแบบอ่านอย่างเดียว; มิฉะนั้น false.

### get_Item(int index) {#get-Item-int-}
```
public final IPortion get_Item(int index)
```

รับองค์ประกอบที่ตำแหน่งดัชนีที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| index | int |  |

**คืนค่า:**  
[IPortion](../../com.aspose.slides/iportion)

### set_Item(int index, IPortion value) {#set-Item-int-com.aspose.slides.IPortion-}
```
public final void set_Item(int index, IPortion value)
```

รับองค์ประกอบที่ตำแหน่งดัชนีที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| index | int |  |
| value | [IPortion](../../com.aspose.slides/iportion) |  |

### add(IPortion value) {#add-com.aspose.slides.IPortion-}
```
public final void add(IPortion value)
```

เพิ่ม Portion ไปที่ท้ายของคอลเล็กชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| value | [IPortion](../../com.aspose.slides/iportion) | Portion ที่จะถูกเพิ่มไปที่ท้ายของคอลเล็กชัน |

### indexOf(IPortion item) {#indexOf-com.aspose.slides.IPortion-}
```
public final int indexOf(IPortion item)
```

กำหนดดัชนีของ item เฉพาะใน List

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | อ็อบเจ็กต์ที่ต้องการค้นหาใน List |

**คืนค่า:**  
int - ดัชนีของ item หากพบในรายการ; มิฉะนั้น -1.

### insert(int index, IPortion value) {#insert-int-com.aspose.slides.IPortion-}
```
public final void insert(int index, IPortion value)
```

แทรก Portion เข้าในคอลเล็กชันที่ตำแหน่งดัชนีที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| index | int | ดัชนีแบบศูนย์ฐานที่ Portion ควรถูกแทรก |
| value | [IPortion](../../com.aspose.slides/iportion) | Portion ที่จะถูกแทรก |

### clear() {#clear--}
```
public final void clear()
```

ลบทุกองค์ประกอบออกจากคอลเล็กชัน

### contains(IPortion item) {#contains-com.aspose.slides.IPortion-}
```
public final boolean contains(IPortion item)
```

กำหนดว่า [IGenericCollection](../../com.aspose.slides/igenericcollection) มีค่าที่ระบุหรือไม่

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | อ็อบเจ็กต์ที่ต้องการค้นหาใน [IGenericCollection](../../com.aspose.slides/igenericcollection) |

**คืนค่า:**  
boolean - true หาก item พบใน [IGenericCollection](../../com.aspose.slides/igenericcollection); มิฉะนั้น false.

### copyTo(IPortion[] array, int arrayIndex) {#copyTo-com.aspose.slides.IPortion---int-}
```
public final void copyTo(IPortion[] array, int arrayIndex)
```

คัดลอกองค์ประกอบของ [IGenericCollection](../../com.aspose.slides/igenericcollection) ไปยัง Array เริ่มจากตำแหน่งดัชนีของ Array ที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| array | [IPortion\[\]](../../com.aspose.slides/iportion) | Array มิติเดียวที่เป็นปลายทางขององค์ประกอบที่คัดลอกจาก [IGenericCollection](../../com.aspose.slides/igenericcollection); Array ต้องใช้ดัชนีแบบศูนย์ฐาน |
| arrayIndex | int | ดัชนีแบบศูนย์ฐานใน array ที่การคัดลอกเริ่มต้น |

### remove(IPortion item) {#remove-com.aspose.slides.IPortion-}
```
public final boolean remove(IPortion item)
```

ลบการเกิดครั้งแรกของอ็อบเจ็กต์ที่ระบุจาก [IGenericCollection](../../com.aspose.slides/igenericcollection)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | อ็อบเจ็กต์ที่ต้องการลบจาก [IGenericCollection](../../com.aspose.slides/igenericcollection) |

**คืนค่า:**  
boolean - true หาก item ถูกลบสำเร็จจาก [IGenericCollection](../../com.aspose.slides/igenericcollection); มิฉะนั้น false. เมธอดนี้ยังคืนค่า false หากไม่พบ item ใน [IGenericCollection](../../com.aspose.slides/igenericcollection) ดั้งเดิม.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

ลบองค์ประกอบที่ตำแหน่งดัชนีที่ระบุในคอลเล็กชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| index | int | ดัชนีแบบศูนย์ฐานขององค์ประกอบที่ต้องลบ |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPortion> iterator()
```

คืน enumerator ที่ทำการวนซ้ำผ่านคอลเล็กชัน

**คืนค่า:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPortion> - IGenericEnumerator ที่สามารถใช้เพื่อวนผ่านคอลเล็กชัน

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPortion> iteratorJava()
```

คืน java iterator สำหรับคอลเล็กชันทั้งหมด

**คืนค่า:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPortion> - java.util.Iterator สำหรับคอลเล็กชันทั้งหมด