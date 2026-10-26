---
title: IUpDownBarsManager
second_title: Aspose.Slides for Android via Java API Reference
description: ให้เข้าถึงแถบขึ้น/ลงของกราฟเส้นหรือกราฟหุ้น.
type: docs
url: /th/com.aspose.slides/iupdownbarsmanager/
---```
public interface IUpDownBarsManager
```

ให้เข้าถึงแถบขึ้น/ลงของกราฟเส้นหรือกราฟหุ้น.
## เมธอด

| Method | Description |
| --- | --- |
| [getUpBarsFormat()](#getUpBarsFormat--) | คืนค่ารูปแบบของแถบขึ้น. |
| [getDownBarsFormat()](#getDownBarsFormat--) | คืนค่ารูปแบบของแถบลง. |
| [hasUpDownBars()](#hasUpDownBars--) | กำหนดว่าแผนภูมิมีแถบขึ้น/ลงหรือไม่. |
| [setUpDownBars(boolean value)](#setUpDownBars-boolean-) | กำหนดว่าแผนภูมิมีแถบขึ้น/ลงหรือไม่. |
| [getGapWidth()](#getGapWidth--) | คืนค่าหรือกำหนดความกว้างของช่องว่าง. |
| [setGapWidth(int value)](#setGapWidth-int-) | คืนค่าหรือกำหนดความกว้างของช่องว่าง. |
### getUpBarsFormat() {#getUpBarsFormat--}
```
public abstract IFormat getUpBarsFormat()
```

คืนค่ารูปแบบของแถบขึ้น. อ่านอย่างเดียว [IFormat](../../com.aspose.slides/iformat).

**คืนค่า:**
[IFormat](../../com.aspose.slides/iformat)
### getDownBarsFormat() {#getDownBarsFormat--}
```
public abstract IFormat getDownBarsFormat()
```

คืนค่ารูปแบบของแถบลง. อ่านอย่างเดียว [IFormat](../../com.aspose.slides/iformat).

**คืนค่า:**
[IFormat](../../com.aspose.slides/iformat)
### hasUpDownBars() {#hasUpDownBars--}
```
public abstract boolean hasUpDownBars()
```

กำหนดว่าแผนภูมิมีแถบขึ้น/ลงหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setUpDownBars(boolean value) {#setUpDownBars-boolean-}
```
public abstract void setUpDownBars(boolean value)
```

กำหนดว่าแผนภูมิมีแถบขึ้น/ลงหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

คืนค่าหรือกำหนดความกว้างของช่องว่าง. อ่าน/เขียน int.

**คืนค่า:**
int
### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```

คืนค่าหรือกำหนดความกว้างของช่องว่าง. อ่าน/เขียน int.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |