---
title: BehaviorPropertyCollection
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API Java
description: แทนคุณสมบัติการจับเวลาสำหรับพฤติกรรมเอฟเฟ็กต์.
type: docs
url: /th/com.aspose.slides/behaviorpropertycollection/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่นำมาใช้ทั้งหมด:**
[com.aspose.slides.IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
```
public class BehaviorPropertyCollection implements IBehaviorPropertyCollection
```

แทนคุณสมบัติการจับเวลาสำหรับพฤติกรรมเอฟเฟ็กต์.
## เมธอด

| Method | Description |
| --- | --- |
| [size()](#size--) | ส่งคืนจำนวนคุณสมบัติที่จัดเก็บในคอลเลกชัน |
| [isReadOnly()](#isReadOnly--) | รับค่าที่บ่งชี้ว่า [IGenericCollection](../../com.aspose.slides/igenericcollection) เป็นอ่านอย่างเดียว |
| [add(IBehaviorProperty item)](#add-com.aspose.slides.IBehaviorProperty-) | เพิ่มคุณสมบัติใหม่ลงในคอลเลกชัน |
| [add(String propertyValue)](#add-java.lang.String-) | เพิ่มคุณสมบัติใหม่ลงในคอลเลกชัน |
| [indexOf(IBehaviorProperty item)](#indexOf-com.aspose.slides.IBehaviorProperty-) | กำหนดดัชนีของรายการที่ระบุใน List |
| [indexOf(String propertyValue)](#indexOf-java.lang.String-) | กำหนดดัชนีของรายการที่ระบุโดยค่าคุณสมบัติใน List |
| [insert(int index, IBehaviorProperty item)](#insert-int-com.aspose.slides.IBehaviorProperty-) | แทรกคุณสมบัติใหม่ลงในคอลเลกชันที่ดัชนีที่ระบุ |
| [insert(int index, String propertyValue)](#insert-int-java.lang.String-) | แทรกคุณสมบัติใหม่ (พร้อมค่าคุณสมบัติที่ระบุ) ลงในคอลเลกชันที่ดัชนีที่ระบุ |
| [copyTo(IBehaviorProperty[] array, int arrayIndex)](#copyTo-com.aspose.slides.IBehaviorProperty---int-) | คัดลอกองค์ประกอบของ [IGenericCollection](../../com.aspose.slides/igenericcollection) ไปยังอาร์เรย์ เริ่มที่ดัชนีอาร์เรย์ที่ระบุ |
| [remove(IBehaviorProperty item)](#remove-com.aspose.slides.IBehaviorProperty-) | ลบคุณสมบัตที่ระบุออกจากคอลเลกชัน |
| [remove(String propertyValue)](#remove-java.lang.String-) | ลบคุณสมบัตที่ระบุออกจากคอลเลกชัน |
| [removeAt(int index)](#removeAt-int-) | ลบคุณสมบัติที่ดัชนีที่ระบุ |
| [clear()](#clear--) | ลบคุณสมบัติทั้งหมดออกจากคอลเลกชัน |
| [contains(IBehaviorProperty item)](#contains-com.aspose.slides.IBehaviorProperty-) | กำหนดว่่า [IGenericCollection](../../com.aspose.slides/igenericcollection) มีค่าที่ระบุหรือไม่ |
| [contains(String propertyValue)](#contains-java.lang.String-) | กำหนดว่่า [IGenericCollection](../../com.aspose.slides/igenericcollection) มีค่าที่ระบุหรือไม่ |
| [get_Item(int index)](#get-Item-int-) | ส่งคืนคุณสมบัติที่ดัชนีที่ระบุ |
| [set_Item(int index, IBehaviorProperty value)](#set-Item-int-com.aspose.slides.IBehaviorProperty-) | ตั้งค่าคุณสมบัติที่ดัชนีที่ระบุ |
| [iterator()](#iterator--) | ส่งคืน enumerator ที่วนซ้ำผ่านคอลเลกชัน |
| [indexOfItem(IBehaviorProperty item)](#indexOfItem-com.aspose.slides.IBehaviorProperty-) |  |
| [insertItem(int index, IBehaviorProperty item)](#insertItem-int-com.aspose.slides.IBehaviorProperty-) |  |
| [addItem(IBehaviorProperty item)](#addItem-com.aspose.slides.IBehaviorProperty-) |  |
| [containsItem(IBehaviorProperty item)](#containsItem-com.aspose.slides.IBehaviorProperty-) |  |
| [copyToTArray(IBehaviorProperty[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IBehaviorProperty---int-) |  |
| [removeItem(IBehaviorProperty item)](#removeItem-com.aspose.slides.IBehaviorProperty-) |  |
| [iteratorJava()](#iteratorJava--) | ส่งคืน java iterator สำหรับคอลเลกชันทั้งหมด |

### size() {#size--}
```
public final int size()
```

ส่งคืนจำนวนคุณสมบัติที่จัดเก็บในคอลเลกชัน. int (อ่านอย่างเดียว)

**ผลลัพธ์:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

รับค่าที่บ่งชี้ว่า [IGenericCollection](../../com.aspose.slides/igenericcollection) เป็นอ่านอย่างเดียว. boolean (อ่านอย่างเดียว)

**ผลลัพธ์:**
boolean - true หาก [IGenericCollection](../../com.aspose.slides/igenericcollection) เป็นอ่านอย่างเดียว; มิฉะนั้น false.
### add(IBehaviorProperty item) {#add-com.aspose.slides.IBehaviorProperty-}
```
public final void add(IBehaviorProperty item)
```

เพิ่มคุณสมบัติใหม่ลงในคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | คุณสมบัติที่จะเพิ่ม. |

### add(String propertyValue) {#add-java.lang.String-}
```
public final void add(String propertyValue)
```

เพิ่มคุณสมบัติใหม่ลงในคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| propertyValue | java.lang.String | ค่าของคุณสมบัติที่จะเพิ่ม. |

### indexOf(IBehaviorProperty item) {#indexOf-com.aspose.slides.IBehaviorProperty-}
```
public final int indexOf(IBehaviorProperty item)
```

กำหนดดัชนีของรายการที่ระบุใน List.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | อ็อบเจ็กต์ที่จะค้นหาใน List. |

**ผลลัพธ์:**
int - ดัชนีของรายการหากพบใน List; มิฉะนั้น -1.
### indexOf(String propertyValue) {#indexOf-java.lang.String-}
```
public final int indexOf(String propertyValue)
```

กำหนดดัชนีของรายการที่ระบุโดยค่าคุณสมบัติใน List.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| propertyValue | java.lang.String | ค่าของคุณสมบัติ |

**ผลลัพธ์:**
int - ดัชนีของคุณสมบัติที่มีค่าที่ระบุ
### insert(int index, IBehaviorProperty item) {#insert-int-com.aspose.slides.IBehaviorProperty-}
```
public final void insert(int index, IBehaviorProperty item)
```

แทรกคุณสมบัติใหม่ลงในคอลเลกชันที่ดัชนีที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีที่ต้องการแทรกคุณสมบัติใหม่ |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | คุณสมบัติที่จะเพิ่ม. |

### insert(int index, String propertyValue) {#insert-int-java.lang.String-}
```
public final void insert(int index, String propertyValue)
```

แทรกคุณสมบัติใหม่ (พร้อมค่าคุณสมบัติที่ระบุ) ลงในคอลเลกชันที่ดัชนีที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีที่ต้องการแทรกคุณสมบัติใหม่ |
| propertyValue | java.lang.String | ค่าของคุณสมบัติที่จะเพิ่ม. |

### copyTo(IBehaviorProperty[] array, int arrayIndex) {#copyTo-com.aspose.slides.IBehaviorProperty---int-}
```
public final void copyTo(IBehaviorProperty[] array, int arrayIndex)
```

คัดลอกองค์ประกอบของ [IGenericCollection](../../com.aspose.slides/igenericcollection) ไปยังอาร์เรย์ เริ่มที่ดัชนีอาร์เรย์ที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| array | [IBehaviorProperty[]](../../com.aspose.slides/ibehaviorproperty) | อาร์เรย์หนึ่งมิติที่เป็นจุดหมายปลายทางขององค์ประกอบที่คัดลอกจาก [IGenericCollection](../../com.aspose.slides/igenericcollection). อาร์เรย์ต้องใช้การจัดทำดัชนีแบบเริ่มต้นที่ 0. |
| arrayIndex | int | ดัชนีเริ่มต้นในอาร์เรย์ที่เริ่มการคัดลอก. |

### remove(IBehaviorProperty item) {#remove-com.aspose.slides.IBehaviorProperty-}
```
public final boolean remove(IBehaviorProperty item)
```

ลบคุณสมบัตที่ระบุออกจากคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | คุณสมบัติที่จะลบ. |

**ผลลัพธ์:**
boolean
### remove(String propertyValue) {#remove-java.lang.String-}
```
public final boolean remove(String propertyValue)
```

ลบคุณสมบัตที่ระบุออกจากคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| propertyValue | java.lang.String | ค่าของคุณสมบัติที่จะลบ. |

**ผลลัพธ์:**
boolean
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

ลบคุณสมบัติที่ดัชนีที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของคุณสมบัติที่ต้องการลบ. |

### clear() {#clear--}
```
public final void clear()
```

ลบคุณสมบัติทั้งหมดออกจากคอลเลกชัน.

### contains(IBehaviorProperty item) {#contains-com.aspose.slides.IBehaviorProperty-}
```
public final boolean contains(IBehaviorProperty item)
```

กำหนดว่่า [IGenericCollection](../../com.aspose.slides/igenericcollection) มีค่าที่ระบุหรือไม่.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | คุณสมบัติที่จะค้นหาใน [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**ผลลัพธ์:**
boolean - true หากพบ item ใน [IGenericCollection](../../com.aspose.slides/igenericcollection); มิฉะนั้น false.
### contains(String propertyValue) {#contains-java.lang.String-}
```
public final boolean contains(String propertyValue)
```

กำหนดว่่า [IGenericCollection](../../com.aspose.slides/igenericcollection) มีค่าที่ระบุหรือไม่.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| propertyValue | java.lang.String | ค่าของคุณสมบัติที่จะค้นหาใน [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**ผลลัพธ์:**
boolean - true หากพบ propertyValue ใน [IGenericCollection](../../com.aspose.slides/igenericcollection); มิฉะนั้น false.
### get_Item(int index) {#get-Item-int-}
```
public final IBehaviorProperty get_Item(int index)
```

ส่งคืนคุณสมบัติที่ดัชนีที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของคุณสมบัติที่ต้องการส่งคืน. |

**ผลลัพธ์:**
[IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) - Animation behavior property.
### set_Item(int index, IBehaviorProperty value) {#set-Item-int-com.aspose.slides.IBehaviorProperty-}
```
public final void set_Item(int index, IBehaviorProperty value)
```

ตั้งค่าคุณสมบัติที่ดัชนีที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของคุณสมบัติที่ต้องการตั้งค่า. |
| value | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehaviorProperty> iterator()
```

ส่งคืน enumerator ที่วนซ้ำผ่านคอลเลกชัน.

**ผลลัพธ์:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehaviorProperty> - A IGenericEnumerator that can be used to iterate through the collection.
### indexOfItem(IBehaviorProperty item) {#indexOfItem-com.aspose.slides.IBehaviorProperty-}
```
public int indexOfItem(IBehaviorProperty item)
```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**ผลลัพธ์:**
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

**ผลลัพธ์:**
boolean
### copyToTArray(IBehaviorProperty[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IBehaviorProperty---int-}
```
public void copyToTArray(IBehaviorProperty[] array, int arrayIndex)
```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| array | [IBehaviorProperty[]](../../com.aspose.slides/ibehaviorproperty) |  |
| arrayIndex | int |  |

### removeItem(IBehaviorProperty item) {#removeItem-com.aspose.slides.IBehaviorProperty-}
```
public boolean removeItem(IBehaviorProperty item)
```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**ผลลัพธ์:**
boolean
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehaviorProperty> iteratorJava()
```

ส่งคืน java iterator สำหรับคอลเลกชันทั้งหมด.

**ผลลัพธ์:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehaviorProperty> - An java.util.Iterator for the entire collection.