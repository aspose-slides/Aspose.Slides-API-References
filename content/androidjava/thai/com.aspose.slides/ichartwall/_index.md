---
title: IChartWall
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แสดงกำแพงบนแผนภูมิ 3 มิติ.
type: docs
url: /th/com.aspose.slides/ichartwall/
---```
public interface IChartWall
```

แสดงกำแพงบนแผนภูมิ 3 มิติ.
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getThickness()](#getThickness--) | คืนค่า หรือกำหนดความหนาของกำแพงเป็นเปอร์เซ็นต์ของมิติที่ใหญ่ที่สุดของปริมาณพล็อต |
| [setThickness(int value)](#setThickness-int-) | คืนค่า หรือกำหนดความหนาของกำแพงเป็นเปอร์เซ็นต์ของมิติที่ใหญ่ที่สุดของปริมาณพล็อต |
| [getFormat()](#getFormat--) | คืนค่าการเติมกำแพง, เส้น, เอฟเฟ็กต์, สไตล์ 3 มิติ |
| [getPictureType()](#getPictureType--) | คืนค่า หรือกำหนดประเภทของรูปภาพ |
| [setPictureType(int value)](#setPictureType-int-) | คืนค่า หรือกำหนดประเภทของรูปภาพ |
### getThickness() {#getThickness--}
```
public abstract int getThickness()
```

คืนค่า หรือกำหนดความหนาของกำแพงเป็นเปอร์เซ็นต์ของมิติที่ใหญ่ที่สุดของปริมาณพล็อต. อ่าน/เขียน int.

**ผลลัพธ์:**
int
### setThickness(int value) {#setThickness-int-}
```
public abstract void setThickness(int value)
```

คืนค่า หรือกำหนดความหนาของกำแพงเป็นเปอร์เซ็นต์ของมิติที่ใหญ่ที่สุดของปริมาณพล็อต. อ่าน/เขียน int.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

คืนค่าการเติมกำแพง, เส้น, เอฟเฟ็กต์, สไตล์ 3 มิติ. อ่านอย่างเดียว [IFormat](../../com.aspose.slides/iformat).

**ผลลัพธ์:**
[IFormat](../../com.aspose.slides/iformat)
### getPictureType() {#getPictureType--}
```
public abstract int getPictureType()
```

คืนค่า หรือกำหนดประเภทของรูปภาพ. อ่าน/เขียน [PictureType](../../com.aspose.slides/picturetype)(\#getPictureType.getPictureType/\#setPictureType(int).setPictureType(int)).

**ผลลัพธ์:**
int
### setPictureType(int value) {#setPictureType-int-}
```
public abstract void setPictureType(int value)
```

คืนค่า หรือกำหนดประเภทของรูปภาพ. อ่าน/เขียน [PictureType](../../com.aspose.slides/picturetype)(\#getPictureType.getPictureType/\#setPictureType(int).setPictureType(int)).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |