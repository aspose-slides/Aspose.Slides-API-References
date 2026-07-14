---
title: IPortionCollection
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แสดงถึงคอลเลกชันของส่วนประกอบ
type: docs
url: /th/com.aspose.slides/iportioncollection/
---
**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IPortionCollection extends System.Collections.Generic.IGenericEnumerable<IPortion>
```

แสดงถึงคอลเลกชันของส่วนประกอบ
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | รับค่าองค์ประกอบที่ตำแหน่งที่ระบุ |
| [getCount()](#getCount--) | รับจำนวนขององค์ประกอบที่อยู่จริงในคอลเลกชัน |
| [add(IPortion value)](#add-com.aspose.slides.IPortion-) | เพิ่ม Portion ไปยังท้ายของคอลเลกชัน |
| [indexOf(IPortion item)](#indexOf-com.aspose.slides.IPortion-) | กำหนดตำแหน่งของ portion เฉพาะในคอลเลกชัน |
| [insert(int index, IPortion value)](#insert-int-com.aspose.slides.IPortion-) | แทรก Portion เข้าไปในคอลเลกชันที่ตำแหน่งที่ระบุ |
| [clear()](#clear--) | ลบองค์ประกอบทั้งหมดจากคอลเลกชัน |
| [contains(IPortion item)](#contains-com.aspose.slides.IPortion-) | กำหนดว่า [IGenericCollection](../../com.aspose.slides/igenericcollection) มีค่าที่ระบุหรือไม่ |
| [remove(IPortion item)](#remove-com.aspose.slides.IPortion-) | ลบการปรากฏตัวแรกของอ็อบเจกต์ที่ระบุจาก [IGenericCollection](../../com.aspose.slides/igenericcollection) |
| [removeAt(int index)](#removeAt-int-) | ลบองค์ประกอบที่ตำแหน่งที่ระบุของคอลเลกชัน |

### get_Item(int index) {#get-Item-int-}
```
public abstract IPortion get_Item(int index)
```

รับค่าองค์ประกอบที่ตำแหน่งที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**คืนค่า:**
[IPortion](../../com.aspose.slides/iportion)

### getCount() {#getCount--}
```
public abstract int getCount()
```

รับจำนวนขององค์ประกอบที่อยู่จริงในคอลเลกชัน. อ่านอย่างเดียว int.

**คืนค่า:**
int

### add(IPortion value) {#add-com.aspose.slides.IPortion-}
```
public abstract void add(IPortion value)
```

เพิ่ม Portion ไปยังท้ายของคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | [IPortion](../../com.aspose.slides/iportion) | Portion ที่จะถูกเพิ่มไปยังท้ายของคอลเลกชัน |

### indexOf(IPortion item) {#indexOf-com.aspose.slides.IPortion-}
```
public abstract int indexOf(IPortion item)
```

กำหนดตำแหน่งของ portion เฉพาะในคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | portion ที่จะค้นหาในคอลเลกชัน |

**คืนค่า:**
int - ดัชนีของ item หากพบในคอลเลกชัน; มิฉะนั้น, -1.

### insert(int index, IPortion value) {#insert-int-com.aspose.slides.IPortion-}
```
public abstract void insert(int index, IPortion value)
```

แทรก Portion เข้าไปในคอลเลกชันที่ตำแหน่งที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีที่เริ่มจากศูนย์ที่ Portion ควรจะถูกแทรก |
| value | [IPortion](../../com.aspose.slides/iportion) | Portion ที่จะทำการแทรก |

### clear() {#clear--}
```
public abstract void clear()
```

ลบองค์ประกอบทั้งหมดจากคอลเลกชัน

### contains(IPortion item) {#contains-com.aspose.slides.IPortion-}
```
public abstract boolean contains(IPortion item)
```

กำหนดว่า [IGenericCollection](../../com.aspose.slides/igenericcollection) มีค่าที่เฉพาะหรือไม่

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | อ็อบเจกต์ที่ค้นหาใน [IGenericCollection](../../com.aspose.slides/igenericcollection) |

**คืนค่า:**
boolean - true หากพบ item ใน [IGenericCollection](../../com.aspose.slides/igenericcollection); มิฉะนั้น, false.

### remove(IPortion item) {#remove-com.aspose.slides.IPortion-}
```
public abstract boolean remove(IPortion item)
```

ลบการปรากฏตัวแรกของอ็อบเจกต์เฉพาะจาก [IGenericCollection](../../com.aspose.slides/igenericcollection)

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | อ็อบเจกต์ที่ต้องการลบจาก [IGenericCollection](../../com.aspose.slides/igenericcollection) |

**คืนค่า:**
boolean - true หาก item ถูกลบสำเร็จจาก [IGenericCollection](../../com.aspose.slides/igenericcollection); มิฉะนั้น, false. วิธีการนี้ยังคืนค่า false หากไม่พบ item ใน [IGenericCollection](../../com.aspose.slides/igenericcollection) ดั้งเดิม

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

ลบองค์ประกอบที่ตำแหน่งที่ระบุของคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีที่เริ่มจากศูนย์ขององค์ประกอบที่ต้องการลบ |