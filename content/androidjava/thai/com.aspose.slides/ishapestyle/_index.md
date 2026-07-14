---
title: IShapeStyle
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: อ้างอิงสไตล์ของรูปร่าง
type: docs
url: /th/com.aspose.slides/ishapestyle/
---```
public interface IShapeStyle
```

อ้างอิงสไตล์ของรูปร่าง
## เมธอด

| Method | คำอธิบาย |
| --- | --- |
| [getLineColor()](#getLineColor--) | คืนค่าสีขอบของ shape |
| [getLineStyleIndex()](#getLineStyleIndex--) | คืนค่า หรือ ตั้งค่าดัชนีคอลัมน์ของเส้นในเมทริกซ์สไตล์ |
| [setLineStyleIndex(int value)](#setLineStyleIndex-int-) | คืนค่า หรือ ตั้งค่าดัชนีคอลัมน์ของเส้นในเมทริกซ์สไตล์ |
| [getFillColor()](#getFillColor--) | คืนค่าสีเติมของ shape |
| [getFillStyleIndex()](#getFillStyleIndex--) | คืนค่า หรือ ตั้งค่าดัชนีคอลัมน์การเติมของ shape ในเมทริกซ์สไตล์ |
| [setFillStyleIndex(short value)](#setFillStyleIndex-short-) | คืนค่า หรือ ตั้งค่าดัชนีคอลัมน์การเติมของ shape ในเมทริกซ์สไตล์ |
| [getEffectColor()](#getEffectColor--) | คืนค่าสีเอฟเฟกต์ของ shape |
| [getEffectStyleIndex()](#getEffectStyleIndex--) | คืนค่า หรือ ตั้งค่าดัชนีคอลัมน์เอฟเฟกต์ของ shape ในเมทริกซ์สไตล์ |
| [setEffectStyleIndex(long value)](#setEffectStyleIndex-long-) | คืนค่า หรือ ตั้งค่าดัชนีคอลัมน์เอฟเฟกต์ของ shape ในเมทริกซ์สไตล์ |
| [getFontColor()](#getFontColor--) | คืนค่าสีฟอนต์ของ shape |
| [getFontCollectionIndex()](#getFontCollectionIndex--) | คืนค่า หรือ ตั้งค่าดัชนีฟอนต์ของ shape ในคอลเลกชันฟอนต์ |
| [setFontCollectionIndex(byte value)](#setFontCollectionIndex-byte-) | คืนค่า หรือ ตั้งค่าดัชนีฟอนต์ของ shape ในคอลเลกชันฟอนต์ |
### getLineColor() {#getLineColor--}
```
public abstract IColorFormat getLineColor()
```


คืนค่าสีขอบของ shape. อ่านอย่างเดียว [IColorFormat](../../com.aspose.slides/icolorformat).

**คืนค่า:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getLineStyleIndex() {#getLineStyleIndex--}
```
public abstract int getLineStyleIndex()
```


คืนค่า หรือ ตั้งค่าดัชนีคอลัมน์ของเส้นในเมทริกซ์สไตล์. อ่าน/เขียน int.

**คืนค่า:**
int
### setLineStyleIndex(int value) {#setLineStyleIndex-int-}
```
public abstract void setLineStyleIndex(int value)
```


คืนค่า หรือ ตั้งค่าดัชนีคอลัมน์ของเส้นในเมทริกซ์สไตล์. อ่าน/เขียน int.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getFillColor() {#getFillColor--}
```
public abstract IColorFormat getFillColor()
```


คืนค่าสีเติมของ shape. อ่านอย่างเดียว [IColorFormat](../../com.aspose.slides/icolorformat).

**คืนค่า:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFillStyleIndex() {#getFillStyleIndex--}
```
public abstract short getFillStyleIndex()
```


คืนค่า หรือ ตั้งค่าดัชนีคอลัมน์การเติมของ shape ในเมทริกซ์สไตล์. 0 หมายถึงไม่มีการเติม, ค่าบวก - ดัชนีในสไตล์การเติมของ theme, ค่าลบ - ดัชนีในสไตล์พื้นหลังของ theme. อ่าน/เขียน short.

**คืนค่า:**
short
### setFillStyleIndex(short value) {#setFillStyleIndex-short-}
```
public abstract void setFillStyleIndex(short value)
```


คืนค่า หรือ ตั้งค่าดัชนีคอลัมน์การเติมของ shape ในเมทริกซ์สไตล์. 0 หมายถึงไม่มีการเติม, ค่าบวก - ดัชนีในสไตล์การเติมของ theme, ค่าลบ - ดัชนีในสไตล์พื้นหลังของ theme. อ่าน/เขียน short.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |
### getEffectColor() {#getEffectColor--}
```
public abstract IColorFormat getEffectColor()
```


คืนค่าสีเอฟเฟกต์ของ shape. อ่านอย่างเดียว [IColorFormat](../../com.aspose.slides/icolorformat).

**คืนค่า:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffectStyleIndex() {#getEffectStyleIndex--}
```
public abstract long getEffectStyleIndex()
```


คืนค่า หรือ ตั้งค่าดัชนีคอลัมน์เอฟเฟกต์ของ shape ในเมทริกซ์สไตล์. อ่าน/เขียน long.

**คืนค่า:**
long
### setEffectStyleIndex(long value) {#setEffectStyleIndex-long-}
```
public abstract void setEffectStyleIndex(long value)
```


คืนค่า หรือ ตั้งค่าดัชนีคอลัมน์เอฟเฟกต์ของ shape ในเมทริกซ์สไตล์. อ่าน/เขียน long.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |
### getFontColor() {#getFontColor--}
```
public abstract IColorFormat getFontColor()
```


คืนค่าสีฟอนต์ของ shape. อ่านอย่างเดียว [IColorFormat](../../com.aspose.slides/icolorformat).

**คืนค่า:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFontCollectionIndex() {#getFontCollectionIndex--}
```
public abstract byte getFontCollectionIndex()
```


คืนค่า หรือ ตั้งค่าดัชนีฟอนต์ของ shape ในคอลเลกชันฟอนต์. อ่าน/เขียน [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex).

**คืนค่า:**
byte
### setFontCollectionIndex(byte value) {#setFontCollectionIndex-byte-}
```
public abstract void setFontCollectionIndex(byte value)
```


คืนค่า หรือ ตั้งค่าดัชนีฟอนต์ของ shape ในคอลเลกชันฟอนต์. อ่าน/เขียน [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex).

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |