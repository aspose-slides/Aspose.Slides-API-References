---
title: ShapeStyle
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: อ้างอิงสไตล์ของรูปร่าง
type: docs
url: /th/com.aspose.slides/shapestyle/
---
**การสืบทอด:**  
java.lang.Object, com.aspose.slides.DomObject

**ทุกอินเทอร์เฟซที่ใช้งาน:**  
[com.aspose.slides.IShapeStyle](../../com.aspose.slides/ishapestyle)
```
public class ShapeStyle extends DomObject<Shape> implements IShapeStyle
```

อ้างอิงสไตล์ของรูปทรง.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getLineColor()](#getLineColor--) | คืนค่าสีเส้นขอบของรูปร่าง. |
| [getLineStyleIndex()](#getLineStyleIndex--) | คืนหรือกำหนดดัชนีคอลัมน์ของเส้นในเมทริกซ์สไตล์. |
| [setLineStyleIndex(int value)](#setLineStyleIndex-int-) | คืนหรือกำหนดดัชนีคอลัมน์ของเส้นในเมทริกซ์สไตล์. |
| [getFillColor()](#getFillColor--) | คืนค่าสีเติมของรูปร่าง. |
| [getFillStyleIndex()](#getFillStyleIndex--) | คืนหรือกำหนดดัชนีคอลัมน์การเติมของรูปร่างในเมทริกซ์สไตล์. |
| [setFillStyleIndex(short value)](#setFillStyleIndex-short-) | คืนหรือกำหนดดัชนีคอลัมน์การเติมของรูปร่างในเมทริกซ์สไตล์. |
| [getEffectColor()](#getEffectColor--) | คืนค่าสีเอฟเฟกต์ของรูปร่าง. |
| [getEffectStyleIndex()](#getEffectStyleIndex--) | คืนหรือกำหนดดัชนีคอลัมน์เอฟเฟกต์ของรูปร่างในเมทริกซ์สไตล์. |
| [setEffectStyleIndex(long value)](#setEffectStyleIndex-long-) | คืนหรือกำหนดดัชนีคอลัมน์เอฟเฟกต์ของรูปร่างในเมทริกซ์สไตล์. |
| [getFontColor()](#getFontColor--) | คืนค่าสีฟอนต์ของรูปร่าง. |
| [getFontCollectionIndex()](#getFontCollectionIndex--) | คืนหรือกำหนดดัชนีฟอนต์ของรูปร่างในคอลเลกชันฟอนต์. |
| [setFontCollectionIndex(byte value)](#setFontCollectionIndex-byte-) | คืนหรือกำหนดดัชนีฟอนต์ของรูปร่างในคอลเลกชันฟอนต์. |

### getLineColor() {#getLineColor--}
```
public final IColorFormat getLineColor()
```

คืนค่าสีเส้นขอบของรูปร่าง. อ่านอย่างเดียว [IColorFormat](../../com.aspose.slides/icolorformat).

**คืนค่า:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getLineStyleIndex() {#getLineStyleIndex--}
```
public final int getLineStyleIndex()
```

คืนหรือกำหนดดัชนีคอลัมน์ของเส้นในเมทริกซ์สไตล์. อ่าน/เขียน int.

**คืนค่า:**
int

### setLineStyleIndex(int value) {#setLineStyleIndex-int-}
```
public final void setLineStyleIndex(int value)
```

คืนหรือกำหนดดัชนีคอลัมน์ของเส้นในเมทริกซ์สไตล์. อ่าน/เขียน int.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getFillColor() {#getFillColor--}
```
public final IColorFormat getFillColor()
```

คืนค่าสีเติมของรูปร่าง. อ่านอย่างเดียว [IColorFormat](../../com.aspose.slides/icolorformat).

**คืนค่า:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getFillStyleIndex() {#getFillStyleIndex--}
```
public final short getFillStyleIndex()
```

คืนหรือกำหนดดัชนีคอลัมน์การเติมของรูปร่างในเมทริกซ์สไตล์. 0 หมายถึงไม่มีการเติม, ค่าเชิงบวก - ดัชนีในสไตล์การเติมของธีม, ค่าเชิงลบ - ดัชนีในสไตล์พื้นหลังของธีม. อ่าน/เขียน short.

**คืนค่า:**
short

### setFillStyleIndex(short value) {#setFillStyleIndex-short-}
```
public final void setFillStyleIndex(short value)
```

คืนหรือกำหนดดัชนีคอลัมน์การเติมของรูปร่างในเมทริกซ์สไตล์. 0 หมายถึงไม่มีการเติม, ค่าเชิงบวก - ดัชนีในสไตล์การเติมของธีม, ค่าเชิงลบ - ดัชนีในสไตล์พื้นหลังของธีม. อ่าน/เขียน short.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | short |  |

### getEffectColor() {#getEffectColor--}
```
public final IColorFormat getEffectColor()
```

คืนค่าสีเอฟเฟกต์ของรูปร่าง. อ่านอย่างเดียว [IColorFormat](../../com.aspose.slides/icolorformat).

**คืนค่า:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getEffectStyleIndex() {#getEffectStyleIndex--}
```
public final long getEffectStyleIndex()
```

คืนหรือกำหนดดัชนีคอลัมน์เอฟเฟกต์ของรูปร่างในเมทริกซ์สไตล์. อ่าน/เขียน long.

**คืนค่า:**
long

### setEffectStyleIndex(long value) {#setEffectStyleIndex-long-}
```
public final void setEffectStyleIndex(long value)
```

คืนหรือกำหนดดัชนีคอลัมน์เอฟเฟกต์ของรูปร่างในเมทริกซ์สไตล์. อ่าน/เขียน long.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | long |  |

### getFontColor() {#getFontColor--}
```
public final IColorFormat getFontColor()
```

คืนค่าสีฟอนต์ของรูปร่าง. อ่านอย่างเดียว [IColorFormat](../../com.aspose.slides/icolorformat).

**คืนค่า:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getFontCollectionIndex() {#getFontCollectionIndex--}
```
public final byte getFontCollectionIndex()
```

คืนหรือกำหนดดัชนีฟอนต์ของรูปร่างในคอลเลกชันฟอนต์. อ่าน/เขียน [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex).

**คืนค่า:**
byte

### setFontCollectionIndex(byte value) {#setFontCollectionIndex-byte-}
```
public final void setFontCollectionIndex(byte value)
```

คืนหรือกำหนดดัชนีฟอนต์ของรูปร่างในคอลเลกชันฟอนต์. อ่าน/เขียน [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |