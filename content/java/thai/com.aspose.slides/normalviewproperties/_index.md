---
title: NormalViewProperties
second_title: Aspose.Slides สำหรับ Java API Reference
description: เป็นตัวแทนของคุณสมบัติมุมมองปกติ.
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

เป็นตัวแทนของคุณสมบัติของมุมมองปกติ มุมมองปกติมีพื้นที่เนื้อหาทั้งหมดสามส่วน: สไลด์เอง, พื้นที่เนื้อหาด้านข้าง, และพื้นที่เนื้อหาด้านล่าง

--------------------

> ```
> The following example shows how to configure ViewProperties.NormalViewProperties properties of a PowerPoint Presentation.
>  
>  //สร้างอ็อบเจ็กต์ Presentation ที่เป็นตัวแทนของไฟล์การนำเสนอ
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

| เมธอด | คำอธิบาย |
| --- | --- |
| [getShowOutlineIcons()](#getShowOutlineIcons--) | ระบุว่าการประยุกต์ควรแสดงไอคอนหรือไม่เมื่อแสดงเนื้อหาโครงร่างในพื้นที่เนื้อหาใด ๆ ของโหมดมุมมองปกติ |
| [setShowOutlineIcons(boolean value)](#setShowOutlineIcons-boolean-) | ระบุว่าการประยุกต์ควรแสดงไอคอนหรือไม่เมื่อแสดงเนื้อหาโครงร่างในพื้นที่เนื้อหาใด ๆ ของโหมดมุมมองปกติ |
| [getSnapVerticalSplitter()](#getSnapVerticalSplitter--) | ระบุว่าตัวแบ่งแนวตั้งควรจดจำสถานะย่อเมื่อพื้นที่ด้านข้างมีขนาดเล็กพอหรือไม่ |
| [setSnapVerticalSplitter(boolean value)](#setSnapVerticalSplitter-boolean-) | ระบุว่าตัวแบ่งแนวตั้งควรจดจำสถานะย่อเมื่อพื้นที่ด้านข้างมีขนาดเล็กพอหรือไม่ |
| [getVerticalBarState()](#getVerticalBarState--) | ระบุสถานะที่แถบตัวแบ่งแนวตั้งควรจะแสดง |
| [setVerticalBarState(int value)](#setVerticalBarState-int-) | ระบุสถานะที่แถบตัวแบ่งแนวตั้งควรจะแสดง |
| [getHorizontalBarState()](#getHorizontalBarState--) | ระบุสถานะที่แถบตัวแบ่งแนวนอนควรจะแสดง |
| [setHorizontalBarState(int value)](#setHorizontalBarState-int-) | ระบุสถานะที่แถบตัวแบ่งแนวนอนควรจะแสดง |
| [getPreferSingleView()](#getPreferSingleView--) | ระบุว่าผู้ใช้ต้องการดูพื้นที่เนื้อหาเดียวเต็มหน้าต่างแทนมุมมองปกติมาตรฐานที่มีสามพื้นที่เนื้อหรือไม่ |
| [setPreferSingleView(boolean value)](#setPreferSingleView-boolean-) | ระบุว่าผู้ใช้ต้องการดูพื้นที่เนื้อหาเดียวเต็มหน้าต่างแทนมุมมองปกติมาตรฐานที่มีสามพื้นที่เนื้อหรือไม่ |
| [getRestoredLeft()](#getRestoredLeft--) | องค์ประกอบนี้ระบุขนาดของพื้นที่เนื้อหาด้านข้างของมุมมองปกติเมื่อพื้นที่นั้นมีขนาดที่กู้คืนได้ (ไม่ย่อและไม่ขยายเต็ม) |
| [getRestoredTop()](#getRestoredTop--) | องค์ประกอบนี้ระบุขนาดของพื้นที่สไลด์ด้านบนของมุมมองปกติเมื่อพื้นที่นั้นมีขนาดที่กู้คืนได้ (ไม่ย่อและไม่ขยายเต็ม) |
### getShowOutlineIcons() {#getShowOutlineIcons--}
```
public final boolean getShowOutlineIcons()
```


ระบุว่าการประยุกต์ควรแสดงไอคอนหรือไม่เมื่อแสดงเนื้อหาโครงร่างในพื้นที่เนื้อหาใด ๆ ของโหมดมุมมองปกติ อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setShowOutlineIcons(boolean value) {#setShowOutlineIcons-boolean-}
```
public final void setShowOutlineIcons(boolean value)
```


ระบุว่าการประยุกต์ควรแสดงไอคอนหรือไม่เมื่อแสดงเนื้อหาโครงร่างในพื้นที่เนื้อหาใด ๆ ของโหมดมุมมองปกติ อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getSnapVerticalSplitter() {#getSnapVerticalSplitter--}
```
public final boolean getSnapVerticalSplitter()
```


ระบุว่าตัวแบ่งแนวตั้งควรจดจำสถานะย่อเมื่อพื้นที่ด้านข้างมีขนาดเล็กพอหรือไม่ อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setSnapVerticalSplitter(boolean value) {#setSnapVerticalSplitter-boolean-}
```
public final void setSnapVerticalSplitter(boolean value)
```


ระบุว่าตัวแบ่งแนวตั้งควรจดจำสถานะย่อเมื่อพื้นที่ด้านข้างมีขนาดเล็กพอหรือไม่ อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBarState() {#getVerticalBarState--}
```
public final int getVerticalBarState()
```


ระบุสถานะที่แถบตัวแบ่งแนวตั้งควรจะแสดง แถบตัวแบ่งแนวตั้งแยกสไลด์ออกจากพื้นที่เนื้อหาด้านข้าง

**คืนค่า:**
int
### setVerticalBarState(int value) {#setVerticalBarState-int-}
```
public final void setVerticalBarState(int value)
```


ระบุสถานะที่แถบตัวแบ่งแนวตั้งควรจะแสดง แถบตัวแบ่งแนวตั้งแยกสไลด์ออกจากพื้นที่เนื้อหาด้านข้าง

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getHorizontalBarState() {#getHorizontalBarState--}
```
public final int getHorizontalBarState()
```


ระบุสถานะที่แถบตัวแบ่งแนวนอนควรจะแสดง แถบตัวแบ่งแนวนอนแยกสไลด์ออกจากพื้นที่เนื้อหาที่อยู่ด้านล่างสไลด์

**คืนค่า:**
int
### setHorizontalBarState(int value) {#setHorizontalBarState-int-}
```
public final void setHorizontalBarState(int value)
```


ระบุสถานะที่แถบตัวแบ่งแนวนอนควรจะแสดง แถบตัวแบ่งแนวนอนแยกสไลด์ออกจากพื้นที่เนื้อหาที่อยู่ด้านล่างสไลด์

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getPreferSingleView() {#getPreferSingleView--}
```
public final boolean getPreferSingleView()
```


ระบุว่าผู้ใช้ต้องการดูพื้นที่เนื้อหาเดียวเต็มหน้าต่างแทนมุมมองปกติมาตรฐานที่มีสามพื้นที่เนื้อหรือไม่ หากเปิดใช้งาน การประยุกต์อาจเลือกแสดงหนึ่งในพื้นที่เนื้อหาในหน้าต่างทั้งหมด อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setPreferSingleView(boolean value) {#setPreferSingleView-boolean-}
```
public final void setPreferSingleView(boolean value)
```


ระบุว่าผู้ใช้ต้องการดูพื้นที่เนื้อหาเดียวเต็มหน้าต่างแทนมุมมองปกติมาตรฐานที่มีสามพื้นที่เนื้อหรือไม่ หากเปิดใช้งาน การประยุกต์อาจเลือกแสดงหนึ่งในพื้นที่เนื้อหาในหน้าต่างทั้งหมด อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getRestoredLeft() {#getRestoredLeft--}
```
public final INormalViewRestoredProperties getRestoredLeft()
```


องค์ประกอบนี้ระบุขนาดของพื้นที่เนื้อหาด้านข้างของมุมมองปกติเมื่อพื้นที่นั้นมีขนาดที่กู้คืนได้ (ไม่ย่อและไม่ขยายเต็ม) อ่านอย่างเดียว [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**คืนค่า:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)
### getRestoredTop() {#getRestoredTop--}
```
public final INormalViewRestoredProperties getRestoredTop()
```


องค์ประกอบนี้ระบุขนาดของพื้นที่สไลด์ด้านบนของมุมมองปกติเมื่อพื้นที่นั้นมีขนาดที่กู้คืนได้ (ไม่ย่อและไม่ขยายเต็ม) อ่านอย่างเดียว [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**คืนค่า:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)