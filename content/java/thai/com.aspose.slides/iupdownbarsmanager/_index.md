---
title: IUpDownBarsManager
second_title: Aspose.Slides for Java API Reference
description: ให้การเข้าถึงแถบขึ้น/ลงของแผนภูมิแบบเส้นหรือแบบหุ้น
type: docs
url: /th/com.aspose.slides/iupdownbarsmanager/
---```
public interface IUpDownBarsManager
```

ให้การเข้าถึงแถบขึ้น/ลงของแผนภูมิแบบเส้นหรือแบบหุ้น.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getUpBarsFormat()](#getUpBarsFormat--) | คืนรูปแบบของแถบขึ้น |
| [getDownBarsFormat()](#getDownBarsFormat--) | คืนรูปแบบของแถบลง |
| [hasUpDownBars()](#hasUpDownBars--) | กำหนดว่ากราฟมีแถบขึ้น/ลงหรือไม่ |
| [setUpDownBars(boolean value)](#setUpDownBars-boolean-) | กำหนดว่ากราฟมีแถบขึ้น/ลงหรือไม่ |
| [getGapWidth()](#getGapWidth--) | คืนค่าหรือกำหนดความกว้างของช่องว่าง |
| [setGapWidth(int value)](#setGapWidth-int-) | คืนค่าหรือกำหนดความกว้างของช่องว่าง |
### getUpBarsFormat() {#getUpBarsFormat--}
```
public abstract IFormat getUpBarsFormat()
```

คืนรูปแบบของแถบขึ้น อ่านอย่างเดียว [IFormat](../../com.aspose.slides/iformat).

**คืนค่า:**
[IFormat](../../com.aspose.slides/iformat)
### getDownBarsFormat() {#getDownBarsFormat--}
```
public abstract IFormat getDownBarsFormat()
```

คืนรูปแบบของแถบลง อ่านอย่างเดียว [IFormat](../../com.aspose.slides/iformat).

**คืนค่า:**
[IFormat](../../com.aspose.slides/iformat)
### hasUpDownBars() {#hasUpDownBars--}
```
public abstract boolean hasUpDownBars()
```

กำหนดว่ากราฟมีแถบขึ้น/ลงหรือไม่ อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setUpDownBars(boolean value) {#setUpDownBars-boolean-}
```
public abstract void setUpDownBars(boolean value)
```

กำหนดว่ากราฟมีแถบขึ้น/ลงหรือไม่ อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

คืนค่าหรือกำหนดความกว้างของช่องว่าง อ่าน/เขียน int.

**คืนค่า:**
int
### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```

คืนค่าหรือกำหนดความกว้างของช่องว่าง อ่าน/เขียน int.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |