---
title: TabCollection
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แสดงถึงคอลเลกชันของแท็บ.
type: docs
url: /th/com.aspose.slides/tabcollection/
---
**การสืบทอด:**  
java.lang.Object

**อินเทอร์เฟซที่ใช้งานทั้งหมด:**  
[com.aspose.slides.ITabCollection](../../com.aspose.slides/itabcollection), com.aspose.slides.IDOMObject  
```
public final class TabCollection implements ITabCollection, IDOMObject
```

แสดงถึงคอลเลกชันของแท็บ.

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [size()](#size--) | รับจำนวนขององค์ประกอบที่มีอยู่จริงในคอลเลกชัน. |
| [get_Item(int index)](#get-Item-int-) | รับองค์ประกอบที่ตำแหน่งที่ระบุ. |
| [add(double position, int align)](#add-double-int-) | เพิ่ม Tab ลงในคอลเลกชัน. |
| [add(ITab value)](#add-com.aspose.slides.ITab-) | เพิ่ม Tab ลงในคอลเลกชัน. |
| [clear()](#clear--) | ลบองค์ประกอบทั้งหมดจากคอลเลกชัน. |
| [removeAt(int index)](#removeAt-int-) | ลบองค์ประกอบที่ตำแหน่งที่ระบุของคอลเลกชัน. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | ตรวจสอบว่าตัวอย่าง TabsEx สองตัวเท่ากันหรือไม่. |
| [iterator()](#iterator--) | คืนค่า enumerator ที่วนซ้ำผ่านคอลเลกชัน. |
| [iteratorJava()](#iteratorJava--) | คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | คัดลอกองค์ประกอบทั้งหมดจากคอลเลกชันไปยังอาร์เรย์ที่ระบุ. |
| [isSynchronized()](#isSynchronized--) | คืนค่าที่ระบุว่าการเข้าถึงคอลเลกชันเป็นแบบซิงโครไนซ์ (ปลอดภัยต่อเธรด) หรือไม่. |
| [getSyncRoot()](#getSyncRoot--) | คืนค่ารากฐานการซิงโครไนซ์. |

### size() {#size--}
```
public final int size()
```

รับจำนวนขององค์ประกอบที่มีอยู่จริงในคอลเลกชัน. อ่านอย่างเดียว int.

**คืนค่า:**  
int

### get_Item(int index) {#get-Item-int-}
```
public final ITab get_Item(int index)
```

รับองค์ประกอบที่ตำแหน่งที่ระบุ. อ่านอย่างเดียว [Tab](../../com.aspose.slides/tab).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**คืนค่า:**  
[ITab](../../com.aspose.slides/itab)

### add(double position, int align) {#add-double-int-}
```
public final ITab add(double position, int align)
```

เพิ่ม Tab ลงในคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| position | double |  |
| align | int |  |

**คืนค่า:**  
[ITab](../../com.aspose.slides/itab) - แท็บที่เพิ่ม

### add(ITab value) {#add-com.aspose.slides.ITab-}
```
public final int add(ITab value)
```

เพิ่ม Tab ลงในคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [ITab](../../com.aspose.slides/itab) | วัตถุ Tab ที่จะเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชัน. |

**คืนค่า:**  
int - ดัชนีที่แท็บถูกเพิ่ม

### clear() {#clear--}
```
public final void clear()
```

ลบองค์ประกอบทั้งหมดจากคอลเลกชัน.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

ลบองค์ประกอบที่ตำแหน่งที่ระบุของคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีเริ่มต้นจากศูนย์ขององค์ประกอบที่จะลบ. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

คืนค่า Parent_Immediate object. อ่านอย่างเดียว IDOMObject.

**คืนค่า:**  
com.aspose.slides.IDOMObject

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

ตรวจสอบว่าตัวอย่าง TabsEx สองตัวเท่ากันหรือไม่.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| obj | java.lang.Object | TabsEx ที่จะเปรียบเทียบกับ TabsEx ปัจจุบัน. |

**คืนค่า:**  
boolean - **true** หาก TabsEx ที่ระบุเท่ากับ TabsEx ปัจจุบัน; หากไม่เช่นนั้น **false**.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ITab> iterator()
```

คืนค่า enumerator ที่วนซ้ำผ่านคอลเลกชัน.

**คืนค่า:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITab> - IGenericEnumerator ที่สามารถใช้วนซ้ำผ่านคอลเลกชัน

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ITab> iteratorJava()
```

คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด.

**คืนค่า:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITab> - java.util.Iterator สำหรับคอลเลกชันทั้งหมด

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

คัดลอกองค์ประกอบทั้งหมดจากคอลเลกชันไปยังอาร์เรย์ที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | อาร์เรย์เป้าหมาย. |
| index | int | ดัชนีเริ่มต้นในอาร์เรย์เป้าหมาย. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

คืนค่าที่ระบุว่าการเข้าถึงคอลเลกชันเป็นแบบซิงโครไนซ์ (ปลอดภัยต่อเธรด) หรือไม่. อ่านอย่างเดียว boolean.

**คืนค่า:**  
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

คืนค่ารากฐานการซิงโครไนซ์. อ่านอย่างเดียว Object.

**คืนค่า:**  
java.lang.Object