---
title: ITab
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ Java
description: เป็นการแท็บสำหรับข้อความ.
type: docs
url: /th/com.aspose.slides/itab/
---
**อินเทอร์เฟซทั้งหมดที่ทำงาน:**
java.lang.Comparable
```
public interface ITab extends Comparable
```

เป็นการแท็บสำหรับข้อความ.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getPosition()](#getPosition--) | คืนค่า หรือ ตั้งค่าตำแหน่งของแท็บ. |
| [setPosition(double value)](#setPosition-double-) | คืนค่า หรือ ตั้งค่าตำแหน่งของแท็บ. |
| [getAlignment()](#getAlignment--) | คืนค่า หรือ ตั้งค่าสไตล์การจัดแนวของแท็บ. |
| [setAlignment(int value)](#setAlignment-int-) | คืนค่า หรือ ตั้งค่าสไตล์การจัดแนวของแท็บ. |
### getPosition() {#getPosition--}
```
public abstract double getPosition()
```


คืนค่า หรือ ตั้งค่าตำแหน่งของแท็บ. การกำหนดค่าคุณสมบัตินี้อาจเปลี่ยนตำแหน่งของแท็บในคอลเลกชันและทำให้ Enumerator ไม่ถูกต้อง. อ่าน/เขียน double.

**คืนค่า:**
double
### setPosition(double value) {#setPosition-double-}
```
public abstract void setPosition(double value)
```


คืนค่า หรือ ตั้งค่าตำแหน่งของแท็บ. การกำหนดค่าคุณสมบัตินี้อาจเปลี่ยนตำแหน่งของแท็บในคอลเลกชันและทำให้ Enumerator ไม่ถูกต้อง. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```


คืนค่า หรือ ตั้งค่าสไตล์การจัดแนวของแท็บ. อ่าน/เขียน [TabAlignment](../../com.aspose.slides/tabalignment).

**คืนค่า:**
int
### setAlignment(int value) {#setAlignment-int-}
```
public abstract void setAlignment(int value)
```


คืนค่า หรือ ตั้งค่าสไตล์การจัดแนวของแท็บ. อ่าน/เขียน [TabAlignment](../../com.aspose.slides/tabalignment).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |