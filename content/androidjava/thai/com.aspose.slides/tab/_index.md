---
title: Tab
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แสดงการจัดแท็บสำหรับข้อความ.
type: docs
url: /th/com.aspose.slides/tab/
---
**การสืบทอด:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**อินเทอร์เฟสที่ทำการ Implement ทั้งหมด:**  
[com.aspose.slides.ITab](../../com.aspose.slides/itab)
```
public final class Tab extends PVIObject implements ITab
```

แสดงการจัดแท็บสำหรับข้อความ.

## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [Tab(double position, int align)](#Tab-double-int-) | สร้าง Tab ใหม่ |

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getPosition()](#getPosition--) | คืนค่า หรือ ตั้งค่าตำแหน่งของแท็บ. |
| [setPosition(double value)](#setPosition-double-) | คืนค่า หรือ ตั้งค่าตำแหน่งของแท็บ. |
| [getAlignment()](#getAlignment--) | คืนค่า หรือ ตั้งค่าสไตล์การจัดแนวของแท็บ. |
| [setAlignment(int value)](#setAlignment-int-) | คืนค่า หรือ ตั้งค่าสไตล์การจัดแนวของแท็บ. |
| [compareTo(Object obj)](#compareTo-java.lang.Object-) | เปรียบเทียบอินสแทนซ์ปัจจุบันกับอ็อบเจ็กต์อื่นของประเภทเดียวกัน. |

### Tab(double position, int align) {#Tab-double-int-}
```
public Tab(double position, int align)
```

สร้าง Tab ใหม่

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| position | double | ตำแหน่งของ Tab. |
| align | int | การจัดแนว. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

เวอร์ชัน. อ่านอย่างเดียว long.

**คืนค่า:**
long

### getPosition() {#getPosition--}
```
public final double getPosition()
```

คืนค่า หรือ ตั้งค่าตำแหน่งของแท็บ. การกำหนดค่าคุณสมบัตินี้อาจเปลี่ยนดัชนีของแท็บในคอลเลกชันและทำให้ Enumerator ไม่ใช้งานได้. อ่าน/เขียน double.

**คืนค่า:**
double

### setPosition(double value) {#setPosition-double-}
```
public final void setPosition(double value)
```

คืนค่า หรือ ตั้งค่าตำแหน่งของแท็บ. การกำหนดค่าคุณสมบัตินี้อาจเปลี่ยนดัชนีของแท็บในคอลเลกชันและทำให้ Enumerator ไม่ใช้งานได้. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```

คืนค่า หรือ ตั้งค่าสไตล์การจัดแนวของแท็บ. อ่าน/เขียน [TabAlignment](../../com.aspose.slides/tabalignment).

**คืนค่า:**
int

### setAlignment(int value) {#setAlignment-int-}
```
public final void setAlignment(int value)
```

คืนค่า หรือ ตั้งค่าสไตล์การจัดแนวของแท็บ. อ่าน/เขียน [TabAlignment](../../com.aspose.slides/tabalignment).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### compareTo(Object obj) {#compareTo-java.lang.Object-}
```
public final int compareTo(Object obj)
```

เปรียบเทียบอินสแทนซ์ปัจจุบันกับอ็อบเจ็กต์อื่นของประเภทเดียวกัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| obj | java.lang.Object | อ็อบเจ็กต์เพื่อเปรียบเทียบกับอินสแทนซ์นี้. |

**คืนค่า:**
int - จำนวนเต็ม 32-บิตที่บ่งบอกลำดับสัมพัทธ์ของค่าที่เปรียบเทียบ ค่าที่คืนมีความหมายดังนี้: 

 * < 0 - อินสแทนซ์นี้น้อยกว่า obj.
 * = 0 - อินสแทนซ์นี้เท่ากับ obj.
 * > 0 - อินสแทนซ์นี้มากกว่า obj.