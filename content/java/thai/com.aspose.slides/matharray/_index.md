---
title: MathArray
second_title: Aspose.Slides สำหรับเอกสารอ้างอิง API ของ Java
description: ระบุอาเรย์แนวตั้งของสมการหรือวัตถุคณิตศาสตร์ใด ๆ
type: docs
url: /th/com.aspose.slides/matharray/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**ทุกอินเทอร์เฟซที่นำไปใช้:**
[com.aspose.slides.IMathArray](../../com.aspose.slides/imatharray)
```
public final class MathArray extends MathElementBase implements IMathArray
```

ระบุอาเรย์แนวตั้งของสมการหรือวัตถุคณิตศาสตร์ใด ๆ

--------------------

> ```
> Example:
>  
>  MathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```
## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [MathArray(IMathElement element)](#MathArray-com.aspose.slides.IMathElement-) | สร้างอาเรย์คณิตศาสตร์และวางองค์ประกอบที่ระบุไว้ในอาเรย์ |
| [MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements)](#MathArray-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--) | สร้างอาเรย์คณิตศาสตร์และวางองค์ประกอบที่ระบุไว้ในอาเรย์ |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getArguments()](#getArguments--) | ชุดของรายการในอาเรย์ |
| [getBaseJustification()](#getBaseJustification--) | ระบุการจัดแนวของอาเรย์สัมพันธ์กับข้อความรอบข้าง ข้อความนอกอาเรย์สามารถจัดแนวกับด้านล่าง, ด้านบน หรือกึ่งกลางของวัตถุอาเรย์ |
| [setBaseJustification(int value)](#setBaseJustification-int-) | ระบุการจัดแนวของอาเรย์สัมพันธ์กับข้อความรอบข้าง ข้อความนอกอาเรย์สามารถจัดแนวกับด้านล่าง, ด้านบน หรือกึ่งกลางของวัตถุอาเรย์ |
| [getMaximumDistribution()](#getMaximumDistribution--) | การกระจายสูงสุด เมื่อเป็นจริง, อาเรย์จะถูกจัดเว้นระยะให้เต็มความกว้างสูงสุดขององค์ประกอบที่บรรจุ (หน้า, คอลัมน์, เซลล์ ฯลฯ) |
| [setMaximumDistribution(boolean value)](#setMaximumDistribution-boolean-) | การกระจายสูงสุด เมื่อเป็นจริง, อาเรย์จะถูกจัดเว้นระยะให้เต็มความกว้างสูงสุดขององค์ประกอบที่บรรจุ (หน้า, คอลัมน์, เซลล์ ฯลฯ) |
| [getObjectDistribution()](#getObjectDistribution--) | การกระจายอ็อบเจกต์ เมื่อเป็นจริง, เนื้อหาของอาเรย์จะถูกจัดเว้นระยะให้เต็มความกว้างสูงสุดของวัตถุอาเรย์ |
| [setObjectDistribution(boolean value)](#setObjectDistribution-boolean-) | การกระจายอ็อบเจกต์ เมื่อเป็นจริง, เนื้อหาของอาเรย์จะถูกจัดเว้นระยะให้เต็มความกว้างสูงสุดของวัตถุอาเรย์ |
| [getRowSpacingRule()](#getRowSpacingRule--) | ประเภทของการเว้นระยะแนวตั้งระหว่างองค์ประกอบอาเรย์ ค่าเริ่มต้น: SingleLineGap |
| [setRowSpacingRule(int value)](#setRowSpacingRule-int-) | ประเภทของการเว้นระยะแนวตั้งระหว่างองค์ประกอบอาเรย์ ค่าเริ่มต้น: SingleLineGap |
| [getRowSpacing()](#getRowSpacing--) | การเว้นระยะระหว่างแถวของอาเรย์ ใช้เฉพาะเมื่อ RowSpacingRule ตั้งเป็น 3 โดยหน่วยวัดจะเป็นจุด หรือหลายเมื่อหน่วยวัดเป็นครึ่งบรรทัด |
| [setRowSpacing(long value)](#setRowSpacing-long-) | การเว้นระยะระหว่างแถวของอาเรย์ ใช้เฉพาะเมื่อ RowSpacingRule ตั้งเป็น 3 โดยหน่วยวัดจะเป็นจุด หรือหลายเมื่อหน่วยวัดเป็นครึ่งบรรทัด |
| [getChildren()](#getChildren--) | รับองค์ประกอบลูก |
### MathArray(IMathElement element) {#MathArray-com.aspose.slides.IMathElement-}
```
public MathArray(IMathElement element)
```

สร้างอาเรย์คณิตศาสตร์และวางองค์ประกอบที่ระบุไว้ในอาเรย์

--------------------

> ```
> Example:
>  
>  MathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | องค์ประกอบที่จะวางในอาเรย์ |

### MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements) {#MathArray-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--}
```
public MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements)
```

สร้างอาเรย์คณิตศาสตร์และวางองค์ประกอบที่ระบุไว้ในอาเรย์

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| elements | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.IMathElement> | องค์ประกอบที่จะวางในอาเรย์ |

### getArguments() {#getArguments--}
```
public final IMathElementCollection getArguments()
```

ชุดของรายการในอาเรย์

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.getArguments().add(new MathematicalText("item2"));
> ```

**ค่าที่ส่งกลับ:**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBaseJustification() {#getBaseJustification--}
```
public final int getBaseJustification()
```

ระบุการจัดแนวของอาเรย์สัมพันธ์กับข้อความรอบข้าง ข้อความนอกอาเรย์สามารถจัดแนวกับด้านล่าง, ด้านบน หรือกึ่งกลางของวัตถุอาเรย์ ค่าเริ่มต้น: Center

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```

**ค่าที่ส่งกลับ:**
int
### setBaseJustification(int value) {#setBaseJustification-int-}
```
public final void setBaseJustification(int value)
```

ระบุการจัดแนวของอาเรย์สัมพันธ์กับข้อความรอบข้าง ข้อความนอกอาเรย์สามารถจัดแนวกับด้านล่าง, ด้านบน หรือกึ่งกลางของวัตถุอาเรย์ ค่าเริ่มต้น: Center

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getMaximumDistribution() {#getMaximumDistribution--}
```
public final boolean getMaximumDistribution()
```

การกระจายสูงสุด เมื่อเป็นจริง, อาเรย์จะถูกจัดเว้นระยะให้เต็มความกว้างสูงสุดขององค์ประกอบที่บรรจุ (หน้า, คอลัมน์, เซลล์ ฯลฯ)

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```

**ค่าที่ส่งกลับ:**
boolean
### setMaximumDistribution(boolean value) {#setMaximumDistribution-boolean-}
```
public final void setMaximumDistribution(boolean value)
```

การกระจายสูงสุด เมื่อเป็นจริง, อาเรย์จะถูกจัดเว้นระยะให้เต็มความกว้างสูงสุดขององค์ประกอบที่บรรจุ (หน้า, คอลัมน์, เซลล์ ฯลฯ)

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getObjectDistribution() {#getObjectDistribution--}
```
public final boolean getObjectDistribution()
```

การกระจายอ็อบเจกต์ เมื่อเป็นจริง, เนื้อหาของอาเรย์จะถูกจัดเว้นระยะให้เต็มความกว้างสูงสุดของวัตถุอาเรย์

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```

**ค่าที่ส่งกลับ:**
boolean
### setObjectDistribution(boolean value) {#setObjectDistribution-boolean-}
```
public final void setObjectDistribution(boolean value)
```

การกระจายอ็อบเจกต์ เมื่อเป็นจริง, เนื้อหาของอาเรย์จะถูกจัดเว้นระยะให้เต็มความกว้างสูงสุดของวัตถุอาเรย์

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getRowSpacingRule() {#getRowSpacingRule--}
```
public final int getRowSpacingRule()
```

ประเภทของการเว้นระยะแนวตั้งระหว่างองค์ประกอบอาเรย์ ค่าเริ่มต้น: SingleLineGap

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
> ```

**ค่าที่ส่งกลับ:**
int
### setRowSpacingRule(int value) {#setRowSpacingRule-int-}
```
public final void setRowSpacingRule(int value)
```

ประเภทของการเว้นระยะแนวตั้งระหว่างองค์ประกอบอาเรย์ ค่าเริ่มต้น: SingleLineGap

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getRowSpacing() {#getRowSpacing--}
```
public final long getRowSpacing()
```

การเว้นระยะระหว่างแถวของอาเรย์ ใช้เฉพาะเมื่อ RowSpacingRule ตั้งเป็น 3 โดยหน่วยวัดจะเป็นจุด หรือหลายเมื่อหน่วยวัดเป็นครึ่งบรรทัด ค่าเริ่มต้น: 0

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**ค่าที่ส่งกลับ:**
long
### setRowSpacing(long value) {#setRowSpacing-long-}
```
public final void setRowSpacing(long value)
```

การเว้นระยะระหว่างแถวของอาเรย์ ใช้เฉพาะเมื่อ RowSpacingRule ตั้งเป็น 3 โดยหน่วยวัดจะเป็นจุด หรือหลายเมื่อหน่วยวัดเป็นครึ่งบรรทัด ค่าเริ่มต้น: 0

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | long |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

รับองค์ประกอบลูก

**ค่าที่ส่งกลับ:**
com.aspose.slides.IMathElement[]