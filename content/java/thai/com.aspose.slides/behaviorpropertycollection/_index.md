---
title: BehaviorPropertyCollection
second_title: อ้างอิง API Aspose.Slides สำหรับ Java
description: เป็นตัวแทนของคุณสมบัติการกำหนดเวลาสำหรับพฤติกรรมเอฟเฟกต์.
type: docs
url: /th/com.aspose.slides/behaviorpropertycollection/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่ Implement ทั้งหมด:**
[com.aspose.slides.IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
```
public class BehaviorPropertyCollection implements IBehaviorPropertyCollection
```

เป็นตัวแทนของคุณสมบัติการกำหนดเวลา สำหรับพฤติกรรมเอฟเฟกต์.
## Methods

| เมธอด | คำอธิบาย |
| --- | --- |
| [size()](#size--) | คืนค่าจำนวนคุณสมบัติที่เก็บไว้ในคอลเลกชัน |
| [isReadOnly()](#isReadOnly--) | รับค่าที่บ่งบอกว่า [IGenericCollection](../../com.aspose.slides/igenericcollection) เป็นแบบอ่านอย่างเดียวหรือไม่ |
| [add(IBehaviorProperty item)](#add-com.aspose.slides.IBehaviorProperty-) | เพิ่มคุณสมบัติใหม่เข้าไปในคอลเลกชัน |
| [add(String propertyValue)](#add-java.lang.String-) | เพิ่มคุณสมบัติใหม่เข้าไปในคอลเลกชัน |
| [indexOf(IBehaviorProperty item)](#indexOf-com.aspose.slides.IBehaviorProperty-) | กำหนดตำแหน่งของรายการเฉพาะใน List |
| [indexOf(String propertyValue)](#indexOf-java.lang.String-) | กำหนดตำแหน่งของรายการเฉพาะโดยค่าคุณสมบัติใน List |
| [insert(int index, IBehaviorProperty item)](#insert-int-com.aspose.slides.IBehaviorProperty-) | แทรกคุณสมบัติใหม่เข้าไปในคอลเลกชันที่ตำแหน่งที่ระบุ |
| [insert(int index, String propertyValue)](#insert-int-java.lang.String-) | แทรกคุณสมบัติใหม่ (ด้วยค่าคุณสมบัติที่ระบุ) เข้าไปในคอลเลกชันที่ตำแหน่งที่ระบุ |
| [copyTo(IBehaviorProperty[] array, int arrayIndex)](#copyTo-com.aspose.slides.IBehaviorProperty---int-) | คัดลอกองค์ประกอบของ [IGenericCollection](../../com.aspose.slides/igenericcollection) ไปยังอาเรย์ เริ่มจากตำแหน่งอาเรย์ที่ระบุ |
| [remove(IBehaviorProperty item)](#remove-com.aspose.slides.IBehaviorProperty-) | ลบคุณสมบัติตามที่ระบุออกจากคอลเลกชัน |
| [remove(String propertyValue)](#remove-java.lang.String-) | ลบคุณสมบัติตามที่ระบุออกจากคอลเลกชัน |
| [removeAt(int index)](#removeAt-int-) | ลบคุณสมบัติที่ตำแหน่งที่ระบุ |
| [clear()](#clear--) | ลบคุณสมบัติทั้งหมดออกจากคอลเลกชัน |
| [contains(IBehaviorProperty item)](#contains-com.aspose.slides.IBehaviorProperty-) | ตรวจสอบว่า [IGenericCollection](../../com.aspose.slides/igenericcollection) มีค่าที่ระบุหรือไม่ |
| [contains(String propertyValue)](#contains-java.lang.String-) | ตรวจสอบว่า [IGenericCollection](../../com.aspose.slides/igenericcollection) มีค่าที่ระบุหรือไม่ |
| [get_Item(int index)](#get-Item-int-) | คืนค่าคุณสมบัติที่ตำแหน่งที่ระบุ |
| [set_Item(int index, IBehaviorProperty value)](#set-Item-int-com.aspose.slides.IBehaviorProperty-) | ตั้งค่าคุณสมบัติที่ตำแหน่งที่ระบุ |
| [iterator()](#iterator--) | คืนค่า enumerator ที่วนซ้ำผ่านคอลเลกชัน |
| [indexOfItem(IBehaviorProperty item)](#indexOfItem-com.aspose.slides.IBehaviorProperty-) |  |
| [insertItem(int index, IBehaviorProperty item)](#insertItem-int-com.aspose.slides.IBehaviorProperty-) |  |
| [addItem(IBehaviorProperty item)](#addItem-com.aspose.slides.IBehaviorProperty-) |  |
| [containsItem(IBehaviorProperty item)](#containsItem-com.aspose.slides.IBehaviorProperty-) |  |
| [copyToTArray(IBehaviorProperty[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IBehaviorProperty---int-) |  |
| [removeItem(IBehaviorProperty item)](#removeItem-com.aspose.slides.IBehaviorProperty-) |  |
| [iteratorJava()](#iteratorJava--) | คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด |
### size() {#size--}
```
public final int size()
```

คืนค่าจำนวนคุณสมบัติที่เก็บไว้ในคอลเลกชัน อ่านอย่างเดียว int.

**คืนค่า:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

รับค่าที่บ่งบอกว่า [IGenericCollection](../../com.aspose.slides/igenericcollection) เป็นแบบอ่านอย่างเดียวหรือไม่ อ่านอย่างเดียว boolean.

**คืนค่า:**
boolean - true หาก [IGenericCollection](../../com.aspose.slides/igenericcollection) เป็นแบบอ่านอย่างเดียว; มิฉะนั้น false.
### add(IBehaviorProperty item) {#add-com.aspose.slides.IBehaviorProperty-}
```
public final void add(IBehaviorProperty item)
```

เพิ่มคุณสมบัติใหม่เข้าไปในคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | คุณสมบัติที่ต้องการเพิ่ม |

### add(String propertyValue) {#add-java.lang.String-}
```
public final void add(String propertyValue)
```

เพิ่มคุณสมบัติใหม่เข้าไปในคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| propertyValue | java.lang.String | ค่าของคุณสมบัติที่ต้องการเพิ่ม |

### indexOf(IBehaviorProperty item) {#indexOf-com.aspose.slides.IBehaviorProperty-}
```
public final int indexOf(IBehaviorProperty item)
```

กำหนดตำแหน่งของรายการเฉพาะใน List

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | วัตถุที่ต้องการค้นหาใน List |

**คืนค่า:**
int - ตำแหน่งของ item หากพบในรายการ; มิฉะนั้น -1
### indexOf(String propertyValue) {#indexOf-java.lang.String-}
```
public final int indexOf(String propertyValue)
```

กำหนดตำแหน่งของรายการเฉพาะโดยค่าคุณสมบัติใน List

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| propertyValue | java.lang.String | ค่าของคุณสมบัติ |

**คืนค่า:**
int - ตำแหน่งของคุณสมบัติที่มีค่าตรงตามที่ระบุ
### insert(int index, IBehaviorProperty item) {#insert-int-com.aspose.slides.IBehaviorProperty-}
```
public final void insert(int index, IBehaviorProperty item)
```

แทรกคุณสมบัติใหม่เข้าไปในคอลเลกชันที่ตำแหน่งที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ตำแหน่งที่ต้องการแทรกคุณสมบัติใหม่ |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | คุณสมบัติที่ต้องการเพิ่ม |

### insert(int index, String propertyValue) {#insert-int-java.lang.String-}
```
public final void insert(int index, String propertyValue)
```

แทรกคุณสมบัติใหม่ (ด้วยค่าคุณสมบัติที่ระบุ) เข้าไปในคอลเลกชันที่ตำแหน่งที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ตำแหน่งที่ต้องการแทรกคุณสมบัติใหม่ |
| propertyValue | java.lang.String | ค่าของคุณสมบัติที่ต้องการเพิ่ม |

### copyTo(IBehaviorProperty[] array, int arrayIndex) {#copyTo-com.aspose.slides.IBehaviorProperty---int-}
```
public final void copyTo(IBehaviorProperty[] array, int arrayIndex)
```

คัดลอกองค์ประกอบของ [IGenericCollection](../../com.aspose.slides/igenericcollection) ไปยังอาเรย์ เริ่มจากตำแหน่งอาเรย์ที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| array | [IBehaviorProperty\[\]](../../com.aspose.slides/ibehaviorproperty) | อาเรย์มิติเดียวที่เป็นจุดหมายขององค์ประกอบที่คัดลอกจาก [IGenericCollection](../../com.aspose.slides/igenericcollection). อาเรย์ต้องใช้การจัดตำแหน่งแบบเริ่มจากศูนย์ |
| arrayIndex | int | ตำแหน่งเริ่มต้นในอาเรย์ที่เริ่มคัดลอก |

### remove(IBehaviorProperty item) {#remove-com.aspose.slides.IBehaviorProperty-}
```
public final boolean remove(IBehaviorProperty item)
```

ลบคุณสมบัติตามที่ระบุออกจากคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | คุณสมบัติที่ต้องการลบ |

**คืนค่า:**
boolean
### remove(String propertyValue) {#remove-java.lang.String-}
```
public final boolean remove(String propertyValue)
```

ลบคุณสมบัติตามที่ระบุออกจากคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| propertyValue | java.lang.String | ค่าของคุณสมบัติที่ต้องการลบ |

**คืนค่า:**
boolean
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

ลบคุณสมบัติที่ตำแหน่งที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ตำแหน่งของคุณสมบัติที่ต้องการลบ |

### clear() {#clear--}
```
public final void clear()
```

ลบคุณสมบัติทั้งหมดออกจากคอลเลกชัน
### contains(IBehaviorProperty item) {#contains-com.aspose.slides.IBehaviorProperty-}
```
public final boolean contains(IBehaviorProperty item)
```

ตรวจสอบว่า [IGenericCollection](../../com.aspose.slides/igenericcollection) มีค่าที่ระบุหรือไม่

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | คุณสมบัติที่ต้องการค้นหาใน [IGenericCollection](../../com.aspose.slides/igenericcollection) |

**คืนค่า:**
boolean - true หากพบ item ใน [IGenericCollection](../../com.aspose.slides/igenericcollection); มิฉะนั้น false
### contains(String propertyValue) {#contains-java.lang.String-}
```
public final boolean contains(String propertyValue)
```

ตรวจสอบว่า [IGenericCollection](../../com.aspose.slides/igenericcollection) มีค่าที่ระบุหรือไม่

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| propertyValue | java.lang.String | ค่าของคุณสมบัติที่ต้องการค้นหาใน [IGenericCollection](../../com.aspose.slides/igenericcollection) |

**คืนค่า:**
boolean - true หากพบ propertyValue ใน [IGenericCollection](../../com.aspose.slides/igenericcollection); มิฉะนั้น false
### get_Item(int index) {#get-Item-int-}
```
public final IBehaviorProperty get_Item(int index)
```

คืนค่าคุณสมบัติที่ตำแหน่งที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ตำแหน่งของคุณสมบัติที่ต้องการคืนค่า |

**คืนค่า:**
[IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) - Animation behavior property
### set_Item(int index, IBehaviorProperty value) {#set-Item-int-com.aspose.slides.IBehaviorProperty-}
```
public final void set_Item(int index, IBehaviorProperty value)
```

ตั้งค่าคุณสมบัติที่ตำแหน่งที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ตำแหน่งของคุณสมบัติที่ต้องการตั้งค่า |
| value | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehaviorProperty> iterator()
```

คืนค่า enumerator ที่วนซ้ำผ่านคอลเลกชัน

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehaviorProperty> - IGenericEnumerator ที่ใช้ในการวนซ้ำผ่านคอลเลกชัน
### indexOfItem(IBehaviorProperty item) {#indexOfItem-com.aspose.slides.IBehaviorProperty-}
```
public int indexOfItem(IBehaviorProperty item)
```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**คืนค่า:**
int
### insertItem(int index, IBehaviorProperty item) {#insertItem-int-com.aspose.slides.IBehaviorProperty-}
```
public void insertItem(int index, IBehaviorProperty item)
```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### addItem(IBehaviorProperty item) {#addItem-com.aspose.slides.IBehaviorProperty-}
```
public void addItem(IBehaviorProperty item)
```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### containsItem(IBehaviorProperty item) {#containsItem-com.aspose.slides.IBehaviorProperty-}
```
public boolean containsItem(IBehaviorProperty item)
```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**คืนค่า:**
boolean
### copyToTArray(IBehaviorProperty[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IBehaviorProperty---int-}
```
public void copyToTArray(IBehaviorProperty[] array, int arrayIndex)
```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| array | [IBehaviorProperty\[\]](../../com.aspose.slides/ibehaviorproperty) |  |
| arrayIndex | int |  |

### removeItem(IBehaviorProperty item) {#removeItem-com.aspose.slides.IBehaviorProperty-}
```
public boolean removeItem(IBehaviorProperty item)
```

**พารามิ터:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**คืนค่า:**
boolean
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehaviorProperty> iteratorJava()
```

คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehaviorProperty> - java.util.Iterator สำหรับคอลเลกชันทั้งหมด