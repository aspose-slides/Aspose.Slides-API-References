---
title: IChartWall
second_title: Aspose.Slides for Java API Reference
description: แสดงผนังบนกราฟ 3 มิติ
type: docs
url: /th/com.aspose.slides/ichartwall/
---```
public interface IChartWall
```

แสดงผนังบนกราฟ 3 มิติ
## เมธอด

| Method | Description |
| --- | --- |
| [getThickness()](#getThickness--) | คืนค่า หรือ ตั้งค่าความหนาของผนังเป็นเปอร์เซ็นต์ของมิติที่ใหญ่ที่สุดของปริมาณกราฟ |
| [setThickness(int value)](#setThickness-int-) | คืนค่า หรือ ตั้งค่าความหนาของผนังเป็นเปอร์เซ็นต์ของมิติที่ใหญ่ที่สุดของปริมาณกราฟ |
| [getFormat()](#getFormat--) | คืนค่าการเติมสีผนัง, เส้น, เอฟเฟ็กต์, สไตล์ 3 มิติ |
| [getPictureType()](#getPictureType--) | คืนค่า หรือ ตั้งค่าประเภทรูปภาพ |
| [setPictureType(int value)](#setPictureType-int-) | คืนค่า หรือ ตั้งค่าประเภทรูปภาพ |
### getThickness() {#getThickness--}
```
public abstract int getThickness()
```


คืนค่า หรือ ตั้งค่าความหนาของผนังเป็นเปอร์เซ็นต์ของมิติที่ใหญ่ที่สุดของปริมาณกราฟ. อ่าน/เขียน int.

**คืนค่า:**
int
### setThickness(int value) {#setThickness-int-}
```
public abstract void setThickness(int value)
```


คืนค่า หรือ ตั้งค่าความหนาของผนังเป็นเปอร์เซ็นต์ของมิติที่ใหญ่ที่สุดของปริมาณกราฟ. อ่าน/เขียน int.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


คืนค่าการเติมสีผนัง, เส้น, เอฟเฟ็กต์, สไตล์ 3 มิติ. อ่านอย่างเดียว [IFormat](../../com.aspose.slides/iformat).

**คืนค่า:**
[IFormat](../../com.aspose.slides/iformat)
### getPictureType() {#getPictureType--}
```
public abstract int getPictureType()
```


คืนค่า หรือ ตั้งค่าประเภทรูปภาพ. อ่าน/เขียน [PictureType](../../com.aspose.slides/picturetype)(\#getPictureType.getPictureType/\#setPictureType(int).setPictureType(int)).

**คืนค่า:**
int
### setPictureType(int value) {#setPictureType-int-}
```
public abstract void setPictureType(int value)
```


คืนค่า หรือ ตั้งค่าประเภทรูปภาพ. อ่าน/เขียน [PictureType](../../com.aspose.slides/picturetype)(\#getPictureType.getPictureType/\#setPictureType(int).setPictureType(int)).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |