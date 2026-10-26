---
title: INormalViewProperties
second_title: Aspose.Slides for Android via Java API Reference
description: Represents normal view properties.
type: docs
url: /th/com.aspose.slides/inormalviewproperties/
---```
public interface INormalViewProperties
```

แสดงคุณสมบัติวิวแบบปกติ. วิวแบบปกติมีพื้นที่เนื้อหาอยู่สามส่วน: สไลด์เอง, พื้นที่เนื้อหาแบบข้าง, และพื้นที่เนื้อหาแบบล่าง.
## Methods

| Method | Description |
| --- | --- |
| [getShowOutlineIcons()](#getShowOutlineIcons--) | ระบุว่าผู้ประยุกต์ควรแสดงไอคอนหรือไม่เมื่อแสดงเนื้อหาโครงร่างในพื้นที่เนื้อหาใด ๆ ของโหมดวิวแบบปกติ |
| [setShowOutlineIcons(boolean value)](#setShowOutlineIcons-boolean-) | ระบุว่าผู้ประยุกต์ควรแสดงไอคอนหรือไม่เมื่อแสดงเนื้อหาโครงร่างในพื้นที่เนื้อหาใด ๆ ของโหมดวิวแบบปกติ |
| [getSnapVerticalSplitter()](#getSnapVerticalSplitter--) | ระบุว่าตัวแบ่งแนวตั้งควรดึงกลับไปสู่สถานะย่อเมื่อพื้นที่ด้านข้างเล็กพอหรือไม่ |
| [setSnapVerticalSplitter(boolean value)](#setSnapVerticalSplitter-boolean-) | ระบุว่าตัวแบ่งแนวตั้งควรดึงกลับไปสู่สถานะย่อเมื่อพื้นที่ด้านข้างเล็กพอหรือไม่ |
| [getVerticalBarState()](#getVerticalBarState--) | ระบุสถานะที่แถบแบ่งแนวตั้งควรแสดง |
| [setVerticalBarState(int value)](#setVerticalBarState-int-) | ระบุสถานะที่แถบแบ่งแนวตั้งควรแสดง |
| [getHorizontalBarState()](#getHorizontalBarState--) | ระบุสถานะที่แถบแบ่งแนวนอนควรแสดง |
| [setHorizontalBarState(int value)](#setHorizontalBarState-int-) | ระบุสถานะที่แถบแบ่งแนวนอนควรแสดง |
| [getPreferSingleView()](#getPreferSingleView--) | ระบุว่าผู้ใช้ต้องการดูพื้นที่เนื้อหาเดี่ยวเต็มหน้าต่างแทนวิวแบบปกติมาตรฐานที่มีสามพื้นที่เนื้อหรือไม่ |
| [setPreferSingleView(boolean value)](#setPreferSingleView-boolean-) | ระบุว่าผู้ใช้ต้องการดูพื้นที่เนื้อหาเดี่ยวเต็มหน้าต่างแทนวิวแบบปกติมาตรฐานที่มีสามพื้นที่เนื้อหรือไม่ |
| [getRestoredLeft()](#getRestoredLeft--) | องค์ประกอบนี้ระบุขนาดของพื้นที่เนื้อหาแบบข้างของวิวแบบปกติ เมื่อพื้นที่มีขนาดที่คืนค่าได้แบบผันแปร (ไม่ย่อและไม่ขยายเต็ม) |
| [getRestoredTop()](#getRestoredTop--) | องค์ประกอบนี้ระบุขนาดของพื้นที่สไลด์ด้านบนของวิวแบบปกติ เมื่อพื้นที่มีขนาดที่คืนค่าได้แบบผันแปร (ไม่ย่อและไม่ขยายเต็ม) |
### getShowOutlineIcons() {#getShowOutlineIcons--}
```
public abstract boolean getShowOutlineIcons()
```


ระบุว่าผู้ประยุกต์ควรแสดงไอคอนหรือไม่เมื่อแสดงเนื้อหาโครงร่างในพื้นที่เนื้อหาใด ๆ ของโหมดวิวแบบปกติ. อ่าน/เขียน boolean.

**Returns:**
boolean
### setShowOutlineIcons(boolean value) {#setShowOutlineIcons-boolean-}
```
public abstract void setShowOutlineIcons(boolean value)
```


ระบุว่าผู้ประยุกต์ควรแสดงไอคอนหรือไม่เมื่อแสดงเนื้อหาโครงร่างในพื้นที่เนื้อหาใด ๆ ของโหมดวิวแบบปกติ. อ่าน/เขียน boolean.

**Parameters:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getSnapVerticalSplitter() {#getSnapVerticalSplitter--}
```
public abstract boolean getSnapVerticalSplitter()
```


ระบุว่าตัวแบ่งแนวตั้งควรดึงกลับไปสู่สถานะย่อเมื่อพื้นที่ด้านข้างเล็กพอหรือไม่. อ่าน/เขียน boolean.

**Returns:**
boolean
### setSnapVerticalSplitter(boolean value) {#setSnapVerticalSplitter-boolean-}
```
public abstract void setSnapVerticalSplitter(boolean value)
```


ระบุว่าตัวแบ่งแนวตั้งควรดึงกลับไปสู่สถานะย่อเมื่อพื้นที่ด้านข้างเล็กพอหรือไม่. อ่าน/เขียน boolean.

**Parameters:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBarState() {#getVerticalBarState--}
```
public abstract int getVerticalBarState()
```


ระบุสถานะที่แถบแบ่งแนวตั้งควรแสดง. แถบแบ่งแนวตั้งแยกสไลด์จากพื้นที่เนื้อหาแบบข้าง.

**Returns:**
int
### setVerticalBarState(int value) {#setVerticalBarState-int-}
```
public abstract void setVerticalBarState(int value)
```


ระบุสถานะที่แถบแบ่งแนวตั้งควรแสดง. แถบแบ่งแนวตั้งแยกสไลด์จากพื้นที่เนื้อหาแบบข้าง.

**Parameters:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getHorizontalBarState() {#getHorizontalBarState--}
```
public abstract int getHorizontalBarState()
```


ระบุสถานะที่แถบแบ่งแนวนอนควรแสดง. แถบแบ่งแนวนอนแยกสไลด์จากพื้นที่เนื้อหาที่ยังอยู่ด้านล่างของสไลด์.

**Returns:**
int
### setHorizontalBarState(int value) {#setHorizontalBarState-int-}
```
public abstract void setHorizontalBarState(int value)
```


ระบุสถานะที่แถบแบ่งแนวนอนควรแสดง. แถบแบ่งแนวนอนแยกสไลด์จากพื้นที่เนื้อหาที่ยังอยู่ด้านล่างของสไลด์.

**Parameters:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getPreferSingleView() {#getPreferSingleView--}
```
public abstract boolean getPreferSingleView()
```


ระบุว่าผู้ใช้ต้องการดูพื้นที่เนื้อหาเดี่ยวเต็มหน้าต่างแทนวิวแบบปกติมาตรฐานที่มีสามพื้นที่เนื้อหรือไม่ หากเปิดใช้งาน แอปพลิเคชันอาจเลือกแสดงหนึ่งในพื้นที่เนื้อหาเต็มหน้าต่าง. อ่าน/เขียน boolean.

**Returns:**
boolean
### setPreferSingleView(boolean value) {#setPreferSingleView-boolean-}
```
public abstract void setPreferSingleView(boolean value)
```


ระบุว่าผู้ใช้ต้องการดูพื้นที่เนื้อหาเดี่ยวเต็มหน้าต่างแทนวิวแบบปกติมาตรฐานที่มีสามพื้นที่เนื้อหรือไม่ หากเปิดใช้งาน แอปพลิเคชันอาจเลือกแสดงหนึ่งในพื้นที่เนื้อหาเต็มหน้าต่าง. อ่าน/เขียน boolean.

**Parameters:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getRestoredLeft() {#getRestoredLeft--}
```
public abstract INormalViewRestoredProperties getRestoredLeft()
```


องค์ประกอบนี้ระบุขนาดของพื้นที่เนื้อหาแบบข้างของวิวแบบปกติ เมื่อพื้นที่มีขนาดที่คืนค่าได้แบบผันแปร (ไม่ย่อและไม่ขยายเต็ม). อ่านเท่านั้น [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Returns:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)
### getRestoredTop() {#getRestoredTop--}
```
public abstract INormalViewRestoredProperties getRestoredTop()
```


องค์ประกอบนี้ระบุขนาดของพื้นที่สไลด์ด้านบนของวิวแบบปกติ เมื่อพื้นที่มีขนาดที่คืนค่าได้แบบผันแปร (ไม่ย่อและไม่ขยายเต็ม). อ่านเท่านั้น [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Returns:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)