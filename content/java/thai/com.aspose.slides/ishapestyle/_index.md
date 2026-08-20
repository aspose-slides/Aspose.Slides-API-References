---
title: IShapeStyle
second_title: Aspose.Slides for Java API Reference
description: อ้างอิงสไตล์ของรูปร่าง
type: docs
url: /th/com.aspose.slides/ishapestyle/
---```
public interface IShapeStyle
```

อ้างอิงสไตล์ของรูปร่าง
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getLineColor()](#getLineColor--) | ส่งคืนสีโครงของรูปร่าง |
| [getLineStyleIndex()](#getLineStyleIndex--) | ส่งคืนหรือกำหนดดัชนีคอลัมน์ของเส้นในเมทริกซ์สไตล์ |
| [setLineStyleIndex(int value)](#setLineStyleIndex-int-) | ส่งคืนหรือกำหนดดัชนีคอลัมน์ของเส้นในเมทริกซ์สไตล์ |
| [getFillColor()](#getFillColor--) | ส่งคืนสีเติมของรูปร่าง |
| [getFillStyleIndex()](#getFillStyleIndex--) | ส่งคืนหรือกำหนดดัชนีคอลัมน์ของการเติมในเมทริกซ์สไตล์ |
| [setFillStyleIndex(short value)](#setFillStyleIndex-short-) | ส่งคืนหรือกำหนดดัชนีคอลัมน์ของการเติมในเมทริกซ์สไตล์ |
| [getEffectColor()](#getEffectColor--) | ส่งคืนสีเอฟเฟกต์ของรูปร่าง |
| [getEffectStyleIndex()](#getEffectStyleIndex--) | ส่งคืนหรือกำหนดดัชนีคอลัมน์ของเอฟเฟกต์ในเมทริกซ์สไตล์ |
| [setEffectStyleIndex(long value)](#setEffectStyleIndex-long-) | ส่งคืนหรือกำหนดดัชนีคอลัมน์ของเอฟเฟกต์ในเมทริกซ์สไตล์ |
| [getFontColor()](#getFontColor--) | ส่งคืนสีฟอนต์ของรูปร่าง |
| [getFontCollectionIndex()](#getFontCollectionIndex--) | ส่งคืนหรือกำหนดดัชนีฟอนต์ของรูปร่างในคอลเลกชันฟอนต์ |
| [setFontCollectionIndex(byte value)](#setFontCollectionIndex-byte-) | ส่งคืนหรือกำหนดดัชนีฟอนต์ของรูปร่างในคอลเลกชันฟอนต์ |
### getLineColor() {#getLineColor--}
```
public abstract IColorFormat getLineColor()
```


ส่งคืนสีโครงของรูปร่าง อ่านอย่างเดียว [IColorFormat](../../com.aspose.slides/icolorformat).

**ส่งคืน:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getLineStyleIndex() {#getLineStyleIndex--}
```
public abstract int getLineStyleIndex()
```


ส่งคืนหรือกำหนดดัชนีคอลัมน์ของเส้นในเมทริกซ์สไตล์ อ่าน/เขียน int.

**ส่งคืน:**
int
### setLineStyleIndex(int value) {#setLineStyleIndex-int-}
```
public abstract void setLineStyleIndex(int value)
```


ส่งคืนหรือกำหนดดัชนีคอลัมน์ของเส้นในเมทริกซ์สไตล์ อ่าน/เขียน int.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |
### getFillColor() {#getFillColor--}
```
public abstract IColorFormat getFillColor()
```


ส่งคืนสีเติมของรูปร่าง อ่านอย่างเดียว [IColorFormat](../../com.aspose.slides/icolorformat).

**ส่งคืน:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFillStyleIndex() {#getFillStyleIndex--}
```
public abstract short getFillStyleIndex()
```


ส่งคืนหรือกำหนดดัชนีคอลัมน์ของการเติมในเมทริกซ์สไตล์ 0 หมายถึงไม่มีการเติม, ค่าบวกคือดัชนีในสไตล์การเติมของธีม, ค่าลบคือดัชนีในสไตล์พื้นหลังของธีม อ่าน/เขียน short.

**ส่งคืน:**
short
### setFillStyleIndex(short value) {#setFillStyleIndex-short-}
```
public abstract void setFillStyleIndex(short value)
```


ส่งคืนหรือกำหนดดัชนีคอลัมน์ของการเติมในเมทริกซ์สไตล์ 0 หมายถึงไม่มีการเติม, ค่าบวกคือดัชนีในสไตล์การเติมของธีม, ค่าลบคือดัชนีในสไตล์พื้นหลังของธีม อ่าน/เขียน short.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | short |  |
### getEffectColor() {#getEffectColor--}
```
public abstract IColorFormat getEffectColor()
```


ส่งคืนสีเอฟเฟกต์ของรูปร่าง อ่านอย่างเดียว [IColorFormat](../../com.aspose.slides/icolorformat).

**ส่งคืน:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffectStyleIndex() {#getEffectStyleIndex--}
```
public abstract long getEffectStyleIndex()
```


ส่งคืนหรือกำหนดดัชนีคอลัมน์ของเอฟเฟกต์ในเมทริกซ์สไตล์ อ่าน/เขียน long.

**ส่งคืน:**
long
### setEffectStyleIndex(long value) {#setEffectStyleIndex-long-}
```
public abstract void setEffectStyleIndex(long value)
```


ส่งคืนหรือกำหนดดัชนีคอลัมน์ของเอฟเฟกต์ในเมทริกซ์สไตล์ อ่าน/เขียน long.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | long |  |
### getFontColor() {#getFontColor--}
```
public abstract IColorFormat getFontColor()
```


ส่งคืนสีฟอนต์ของรูปร่าง อ่านอย่างเดียว [IColorFormat](../../com.aspose.slides/icolorformat).

**ส่งคืน:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFontCollectionIndex() {#getFontCollectionIndex--}
```
public abstract byte getFontCollectionIndex()
```


ส่งคืนหรือกำหนดดัชนีฟอนต์ของรูปร่างในคอลเลกชันฟอนต์ อ่าน/เขียน [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex).

**ส่งคืน:**
byte
### setFontCollectionIndex(byte value) {#setFontCollectionIndex-byte-}
```
public abstract void setFontCollectionIndex(byte value)
```


ส่งคืนหรือกำหนดดัชนีฟอนต์ของรูปร่างในคอลเลกชันฟอนต์ อ่าน/เขียน [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |