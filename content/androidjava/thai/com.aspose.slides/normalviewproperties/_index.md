---
title: NormalViewProperties
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แทนคุณสมบัติของมุมมองปกติ.
type: docs
url: /th/com.aspose.slides/normalviewproperties/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**
[com.aspose.slides.INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
```
public class NormalViewProperties implements INormalViewProperties
```

แทนคุณสมบัติของมุมมองปกติ มุมมองปกติประกอบด้วยพื้นที่เนื้อหา three ส่วน: สไลด์เอง, พื้นที่เนื้อหาด้านข้าง, และพื้นที่เนื้อหาด้านล่าง.

--------------------

> ```
> The following example shows how to configure ViewProperties.NormalViewProperties properties of a PowerPoint Presentation.
>  
>  //สร้างอ็เจกต์ Presentation ที่แสดงไฟล์การนำเสนอ
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      pres.getViewProperties().getNormalViewProperties().setHorizontalBarState(SplitterBarStateType.Restored);
>      pres.getViewProperties().getNormalViewProperties().setVerticalBarState(SplitterBarStateType.Maximized);
>      pres.getViewProperties().getNormalViewProperties().getRestoredTop().setAutoAdjust(true);
>      pres.getViewProperties().getNormalViewProperties().getRestoredTop().setDimensionSize(80);
>      pres.getViewProperties().getNormalViewProperties().setShowOutlineIcons(true);
>      pres.save("presentation_normal_view_state.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## วิธีการ

| Method | Description |
| --- | --- |
| [getShowOutlineIcons()](#getShowOutlineIcons--) | ระบุว่าการประยุกต์ควรแสดงไอคอนหรือไม่เมื่อแสดงเนื้อหาเค้าโครงในพื้นที่เนื้อหาใด ๆ ของโหมดมุมมองปกติ. |
| [setShowOutlineIcons(boolean value)](#setShowOutlineIcons-boolean-) | ระบุว่าการประยุกต์ควรแสดงไอคอนหรือไม่เมื่อแสดงเนื้อหาเค้าโครงในพื้นที่เนื้อหาใด ๆ ของโหมดมุมมองปกติ. |
| [getSnapVerticalSplitter()](#getSnapVerticalSplitter--) | ระบุว่าตัวแบ่งแนวตั้งควรล็อคเข้าสู่สถานะย่อเมื่อพื้นที่ด้านข้างเล็กพอ. |
| [setSnapVerticalSplitter(boolean value)](#setSnapVerticalSplitter-boolean-) | ระบุว่าตัวแบ่งแนวตั้งควรล็อคเข้าสู่สถานะย่อเมื่อพื้นที่ด้านข้างเล็กพอ. |
| [getVerticalBarState()](#getVerticalBarState--) | ระบุสถานะที่ต้องการให้แถบตัวแบ่งแนวตั้งแสดง. |
| [setVerticalBarState(int value)](#setVerticalBarState-int-) | ระบุสถานะที่ต้องการให้แถบตัวแบ่งแนวตั้งแสดง. |
| [getHorizontalBarState()](#getHorizontalBarState--) | ระบุสถานะที่ต้องการให้แถบตัวแบ่งแนวนอนแสดง. |
| [setHorizontalBarState(int value)](#setHorizontalBarState-int-) | ระบุสถานะที่ต้องการให้แถบตัวแบ่งแนวนอนแสดง. |
| [getPreferSingleView()](#getPreferSingleView--) | ระบุว่าผู้ใช้ต้องการดูพื้นที่เนื้อหาเดียวเต็มหน้าต่างเหนือมุมมองปกติที่มีพื้นที่เนื้อหา three ส่วนหรือไม่. |
| [setPreferSingleView(boolean value)](#setPreferSingleView-boolean-) | ระบุว่าผู้ใช้ต้องการดูพื้นที่เนื้อหาเดียวเต็มหน้าต่างเหนือมุมมองปกติที่มีพื้นที่เนื้อหา three ส่วนหรือไม่. |
| [getRestoredLeft()](#getRestoredLeft--) | รายการนี้ระบุขนาดของพื้นที่เนื้อหาด้านข้างของมุมมองปกติเมื่อพื้นที่อยู่ในขนาดคืนค่าแบบแปรผัน (ไม่ได้ย่อหรือขยาย). |
| [getRestoredTop()](#getRestoredTop--) | รายการนี้ระบุขนาดของพื้นที่สไลด์บนของมุมมองปกติเมื่อพื้นที่อยู่ในขนาดคืนค่าแบบแปรผัน (ไม่ได้ย่อหรือขยาย). |
### getShowOutlineIcons() {#getShowOutlineIcons--}
```
public final boolean getShowOutlineIcons()
```

ระบุว่าการประยุกต์ควรแสดงไอคอนหรือไม่เมื่อแสดงเนื้อหาเค้าโครงในพื้นที่เนื้อหาใด ๆ ของโหมดมุมมองปกติ อ่าน/เขียน boolean.

**ผลลัพธ์:**
boolean
### setShowOutlineIcons(boolean value) {#setShowOutlineIcons-boolean-}
```
public final void setShowOutlineIcons(boolean value)
```

ระบุว่าการประยุกต์ควรแสดงไอคอนหรือไม่เมื่อแสดงเนื้อหาเค้าโครงในพื้นที่เนื้อหาใด ๆ ของโหมดมุมมองปกติ อ่าน/เขียน boolean.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getSnapVerticalSplitter() {#getSnapVerticalSplitter--}
```
public final boolean getSnapVerticalSplitter()
```

ระบุว่าตัวแบ่งแนวตั้งควรล็อคเข้าสู่สถานะย่อเมื่อพื้นที่ด้านข้างเล็กพอ อ่าน/เขียน boolean.

**ผลลัพธ์:**
boolean
### setSnapVerticalSplitter(boolean value) {#setSnapVerticalSplitter-boolean-}
```
public final void setSnapVerticalSplitter(boolean value)
```

ระบุว่าตัวแบ่งแนวตั้งควรล็อคเข้าสู่สถานะย่อเมื่อพื้นที่ด้านข้างเล็กพอ อ่าน/เขียน boolean.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getVerticalBarState() {#getVerticalBarState--}
```
public final int getVerticalBarState()
```

ระบุสถานะที่ต้องการให้แถบตัวแบ่งแนวตั้งแสดง. ตัวแบ่งแนวตั้งแยกสไลด์จากพื้นที่เนื้อหาด้านข้าง.

**ผลลัพธ์:**
int
### setVerticalBarState(int value) {#setVerticalBarState-int-}
```
public final void setVerticalBarState(int value)
```

ระบุสถานะที่ต้องการให้แถบตัวแบ่งแนวตั้งแสดง. ตัวแบ่งแนวตั้งแยกสไลด์จากพื้นที่เนื้อหาด้านข้าง.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getHorizontalBarState() {#getHorizontalBarState--}
```
public final int getHorizontalBarState()
```

ระบุสถานะที่ต้องการให้แถบตัวแบ่งแนวนอนแสดง. ตัวแบ่งแนวนอนแยกสไลด์จากพื้นที่เนื้อหาด้านล่างสไลด์.

**ผลลัพธ์:**
int
### setHorizontalBarState(int value) {#setHorizontalBarState-int-}
```
public final void setHorizontalBarState(int value)
```

ระบุสถานะที่ต้องการให้แถบตัวแบ่งแนวนอนแสดง. ตัวแบ่งแนวนอนแยกสไลด์จากพื้นที่เนื้อหาด้านล่างสไลด์.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getPreferSingleView() {#getPreferSingleView--}
```
public final boolean getPreferSingleView()
```

ระบุว่าผู้ใช้ต้องการดูพื้นที่เนื้อหาเดียวเต็มหน้าต่างเหนือมุมมองปกติที่มีพื้นที่เนื้อหา three ส่วนหรือไม่ หากเปิดใช้งาน การประยุกต์อาจเลือกแสดงหนึ่งในพื้นที่เนื้อหาในหน้าต่างทั้งหมด อ่าน/เขียน boolean.

**ผลลัพธ์:**
boolean
### setPreferSingleView(boolean value) {#setPreferSingleView-boolean-}
```
public final void setPreferSingleView(boolean value)
```

ระบุว่าผู้ใช้ต้องการดูพื้นที่เนื้อหาเดียวเต็มหน้าต่างเหนือมุมมองปกติที่มีพื้นที่เนื้อหา three ส่วนหรือไม่ หากเปิดใช้งาน การประยุกต์อาจเลือกแสดงหนึ่งในพื้นที่เนื้อหาในหน้าต่างทั้งหมด อ่าน/เขียน boolean.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getRestoredLeft() {#getRestoredLeft--}
```
public final INormalViewRestoredProperties getRestoredLeft()
```

รายการนี้ระบุขนาดของพื้นที่เนื้อหาด้านข้างของมุมมองปกติเมื่อพื้นที่อยู่ในขนาดคืนค่าแบบแปรผัน (ไม่ได้ย่อหรือขยาย). อ่านอย่างเดียว [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**ผลลัพธ์:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)
### getRestoredTop() {#getRestoredTop--}
```
public final INormalViewRestoredProperties getRestoredTop()
```

รายการนี้ระบุขนาดของพื้นที่สไลด์บนของมุมมองปกติเมื่อพื้นที่อยู่ในขนาดคืนค่าแบบแปรผัน (ไม่ได้ย่อหรือขยาย). อ่านอย่างเดียว [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**ผลลัพธ์:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)