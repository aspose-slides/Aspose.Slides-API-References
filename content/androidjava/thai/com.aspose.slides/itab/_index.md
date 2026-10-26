---
title: ITab
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แสดงการจัดแท็บสำหรับข้อความ
type: docs
url: /th/com.aspose.slides/itab/
---
**อินเทอร์เฟซที่ดำเนินการทั้งหมด:**
java.lang.Comparable
```
public interface ITab extends Comparable
```

แสดงการจัดแท็บสำหรับข้อความ
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getPosition()](#getPosition--) | คืนหรือกำหนดตำแหน่งของแท็บ |
| [setPosition(double value)](#setPosition-double-) | คืนหรือกำหนดตำแหน่งของแท็บ |
| [getAlignment()](#getAlignment--) | คืนหรือกำหนดรูปแบบการจัดแนวของแท็บ |
| [setAlignment(int value)](#setAlignment-int-) | คืนหรือกำหนดรูปแบบการจัดแนวของแท็บ |
### getPosition() {#getPosition--}
```
public abstract double getPosition()
```

คืนหรือกำหนดตำแหน่งของแท็บ การตั้งค่าคุณสมบัตินี้อาจเปลี่ยนตำแหน่งของแท็บในคอลเลกชันและทำให้ Enumerator ไม่ถูกต้อง อ่าน/เขียน double

**คืนค่า:**
double
### setPosition(double value) {#setPosition-double-}
```
public abstract void setPosition(double value)
```

คืนหรือกำหนดตำแหน่งของแท็บ การตั้งค่าคุณสมบัตินี้อาจเปลี่ยนตำแหน่งของแท็บในคอลเลกชันและทำให้ Enumerator ไม่ถูกต้อง อ่าน/เขียน double

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```

คืนหรือกำหนดรูปแบบการจัดแนวของแท็บ อ่าน/เขียน [TabAlignment](../../com.aspose.slides/tabalignment)

**คืนค่า:**
int
### setAlignment(int value) {#setAlignment-int-}
```
public abstract void setAlignment(int value)
```

คืนหรือกำหนดรูปแบบการจัดแนวของแท็บ อ่าน/เขียน [TabAlignment](../../com.aspose.slides/tabalignment)

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |