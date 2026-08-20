---
title: INormalViewProperties
second_title: Aspose.Slides for Java API Reference
description: Represents normal view properties.
type: docs
url: /th/com.aspose.slides/inormalviewproperties/
---```
public interface INormalViewProperties
```

แสดงคุณสมบัติของมุมมองปกติ. มุมมองปกติมีสามเขตเนื้อหา: สไลด์เอง, เขตเนื้อหาด้านข้าง, และเขตเนื้อหาด้านล่าง.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getShowOutlineIcons()](#getShowOutlineIcons--) | ระบุว่าแอปพลิเคชันควรแสดงไอคอนหรือไม่เมื่อแสดงเนื้อหาโครงร่างในเขตเนื้อหาใดๆ ของโหมดมุมมองปกติ. |
| [setShowOutlineIcons(boolean value)](#setShowOutlineIcons-boolean-) | ระบุว่าแอปพลิเคชันควรแสดงไอคอนหรือไม่เมื่อแสดงเนื้อหาโครงร่างในเขตเนื้อหาใดๆ ของโหมดมุมมองปกติ. |
| [getSnapVerticalSplitter()](#getSnapVerticalSplitter--) | ระบุว่าตัวแบ่งแนวตั้งควรล็อคให้อยู่ในสถานะย่อเมื่อเขตด้านข้างมีขนาดเล็กพอ. |
| [setSnapVerticalSplitter(boolean value)](#setSnapVerticalSplitter-boolean-) | ระบุว่าตัวแบ่งแนวตั้งควรล็อคให้อยู่ในสถานะย่อเมื่อเขตด้านข้างมีขนาดเล็กพอ. |
| [getVerticalBarState()](#getVerticalBarState--) | ระบุสถานะที่แถบแบ่งแนวตั้งควรแสดง. |
| [setVerticalBarState(int value)](#setVerticalBarState-int-) | ระบุสถานะที่แถบแบ่งแนวตั้งควรแสดง. |
| [getHorizontalBarState()](#getHorizontalBarState--) | ระบุสถานะที่แถบแบ่งแนวนอนควรแสดง. |
| [setHorizontalBarState(int value)](#setHorizontalBarState-int-) | ระบุสถานะที่แถบแบ่งแนวนอนควรแสดง. |
| [getPreferSingleView()](#getPreferSingleView--) | ระบุว่าผู้ใช้ต้องการเห็นเขตเนื้อหาเดียวเต็มหน้าต่างแทนมุมมองปกติแบบมาตรฐานที่มีสามเขตเนื้อหรือไม่. |
| [setPreferSingleView(boolean value)](#setPreferSingleView-boolean-) | ระบุว่าผู้ใช้ต้องการเห็นเขตเนื้อหาเดียวเต็มหน้าต่างแทนมุมมองปกติแบบมาตรฐานที่มีสามเขตเนื้อหรือไม่. |
| [getRestoredLeft()](#getRestoredLeft--) | องค์ประกอบนี้ระบุการกำหนดขนาดของเขตเนื้อหาด้านข้างของมุมมองปกติเมื่อเขตนั้นอยู่ในขนาดที่ฟื้นคืนตัวได้ (ไม่ย่อและไม่ขยายเต็ม). |
| [getRestoredTop()](#getRestoredTop--) | องค์ประกอบนี้ระบุการกำหนดขนาดของเขตสไลด์ด้านบนของมุมมองปกติเมื่อเขตนั้นอยู่ในขนาดที่ฟื้นคืนตัวได้ (ไม่ย่อและไม่ขยายเต็ม). |
### getShowOutlineIcons() {#getShowOutlineIcons--}
```
public abstract boolean getShowOutlineIcons()
```

ระบุว่าแอปพลิเคชันควรแสดงไอคอนเมื่อแสดงเนื้อหาโครงร่างในเขตเนื้อหาใดๆ ของโหมดมุมมองปกติ. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setShowOutlineIcons(boolean value) {#setShowOutlineIcons-boolean-}
```
public abstract void setShowOutlineIcons(boolean value)
```

ระบุว่าแอปพลิเคชันควรแสดงไอคอนเมื่อแสดงเนื้อหาโครงร่างในเขตเนื้อหาใดๆ ของโหมดมุมมองปกติ. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getSnapVerticalSplitter() {#getSnapVerticalSplitter--}
```
public abstract boolean getSnapVerticalSplitter()
```

ระบุว่าตัวแบ่งแนวตั้งควรล็อคให้อยู่ในสถานะย่อเมื่อเขตด้านข้างมีขนาดเล็กพอ. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setSnapVerticalSplitter(boolean value) {#setSnapVerticalSplitter-boolean-}
```
public abstract void setSnapVerticalSplitter(boolean value)
```

ระบุว่าตัวแบ่งแนวตั้งควรล็อคให้อยู่ในสถานะย่อเมื่อเขตด้านข้างมีขนาดเล็กพอ. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getVerticalBarState() {#getVerticalBarState--}
```
public abstract int getVerticalBarState()
```

ระบุสถานะที่แถบแบ่งแนวตั้งควรแสดง. แถบแบ่งแนวตั้งแยกสไลด์ออกจากเขตเนื้อหาด้านข้าง.

**คืนค่า:**
int
### setVerticalBarState(int value) {#setVerticalBarState-int-}
```
public abstract void setVerticalBarState(int value)
```

ระบุสถานะที่แถบแบ่งแนวตั้งควรแสดง. แถบแบ่งแนวตั้งแยกสไลด์ออกจากเขตเนื้อหาด้านข้าง.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |
### getHorizontalBarState() {#getHorizontalBarState--}
```
public abstract int getHorizontalBarState()
```

ระบุสถานะที่แถบแบ่งแนวนอนควรแสดง. แถบแบ่งแนวนอนแยกสไลด์ออกจากเขตเนื้อหาด้านล่างสไลด์.

**คืนค่า:**
int
### setHorizontalBarState(int value) {#setHorizontalBarState-int-}
```
public abstract void setHorizontalBarState(int value)
```

ระบุสถานะที่แถบแบ่งแนวนอนควรแสดง. แถบแบ่งแนวนอนแยกสไลด์ออกจากเขตเนื้อหาด้านล่างสไลด์.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |
### getPreferSingleView() {#getPreferSingleView--}
```
public abstract boolean getPreferSingleView()
```

ระบุว่าผู้ใช้ต้องการเห็นเขตเนื้อหาเดียวเต็มหน้าต่างแทนมุมมองปกติแบบมาตรฐานที่มีสามเขตเนื้อหรือไม่. หากเปิดใช้, แอปพลิเคชันอาจแสดงหนึ่งในเขตเนื้อหาเต็มหน้าต่าง. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setPreferSingleView(boolean value) {#setPreferSingleView-boolean-}
```
public abstract void setPreferSingleView(boolean value)
```

ระบุว่าผู้ใช้ต้องการเห็นเขตเนื้อหาเดียวเต็มหน้าต่างแทนมุมมองปกติแบบมาตรฐานที่มีสามเขตเนื้อหรือไม่. หากเปิดใช้, แอปพลิเคชันอาจแสดงหนึ่งในเขตเนื้อหาเต็มหน้าต่าง. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getRestoredLeft() {#getRestoredLeft--}
```
public abstract INormalViewRestoredProperties getRestoredLeft()
```

องค์ประกอบนี้ระบุการกำหนดขนาดของเขตเนื้อหาด้านข้างของมุมมองปกติเมื่อเขตนั้นอยู่ในขนาดที่ฟื้นคืนตัวได้ (ไม่ย่อและไม่ขยายเต็ม). อ่านอย่างเดียว [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**คืนค่า:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)
### getRestoredTop() {#getRestoredTop--}
```
public abstract INormalViewRestoredProperties getRestoredTop()
```

องค์ประกอบนี้ระบุการกำหนดขนาดของเขตสไลด์ด้านบนของมุมมองปกติเมื่อเขตนั้นอยู่ในขนาดที่ฟื้นคืนตัวได้ (ไม่ย่อและไม่ขยายเต็ม). อ่านอย่างเดียว [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**คืนค่า:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)