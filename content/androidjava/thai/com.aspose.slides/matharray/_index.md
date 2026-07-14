---
title: MathArray
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API อ้างอิง
description: ระบุอาเรย์แนวตั้งของสมการหรือวัตถุทางคณิตศาสตร์ใด ๆ
type: docs
url: /th/com.aspose.slides/matharray/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**อินเทอร์เฟซที่ทำการ Implement ทั้งหมด:**
[com.aspose.slides.IMathArray](../../com.aspose.slides/imatharray)
```
public final class MathArray extends MathElementBase implements IMathArray
```

ระบุอาเรย์แนวตั้งของสมการหรือวัตถุทางคณิตศาสตร์ใด ๆ

--------------------

> ```
> Example:
>  
>  MathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```
## ตัวสร้าง

| ตัวสร้าง | คำอธิบาย |
| --- | --- |
| [MathArray(IMathElement element)](#MathArray-com.aspose.slides.IMathElement-) | สร้างอาเรย์ทางคณิตศาสตร์และวางองค์ประกอบที่ระบุไว้ในนั้น |
| [MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements)](#MathArray-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--) | สร้างอาเรย์ทางคณิตศาสตร์และวางองค์ประกอบที่ระบุไว้ในอาเรย์ |

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getArguments()](#getArguments--) | ชุดของรายการในอาเรย์ |
| [getBaseJustification()](#getBaseJustification--) | ระบุการจัดตำแหน่งของอาเรย์สัมพันธ์กับข้อความโดยรอบ ข้อความนอกอาเรย์สามารถจัดตำแหน่งกับด้านล่าง ด้านบน หรือศูนย์กลางของอ็อบเจ็กต์อาเรย์ |
| [setBaseJustification(int value)](#setBaseJustification-int-) | ระบุการจัดตำแหน่งของอาเรย์สัมพันธ์กับข้อความโดยรอบ ข้อความนอกอาเรย์สามารถจัดตำแหน่งกับด้านล่าง ด้านบน หรือศูนย์กลางของอ็อบเจ็กต์อาเรย์ |
| [getMaximumDistribution()](#getMaximumDistribution--) | การกระจายสูงสุด เมื่อเป็นจริง อาเรย์จะถูกจัดระยะห่างให้เต็มความกว้างสูงสุดขององค์ประกอบที่บรรจุ (หน้า, คอลัมน์, เซลล์ ฯลฯ) |
| [setMaximumDistribution(boolean value)](#setMaximumDistribution-boolean-) | การกระจายสูงสุด เมื่อเป็นจริง อาเรย์จะถูกจัดระยะห่างให้เต็มความกว้างสูงสุดขององค์ประกอบที่บรรจุ (หน้า, คอลัมน์, เซลล์ ฯลฯ) |
| [getObjectDistribution()](#getObjectDistribution--) | การกระจายอ็อบเจ็กต์ เมื่อเป็นจริง เนื้อหาของอาเรย์จะถูกจัดระยะห่างให้เต็มความกว้างสูงสุดของอ็อบเจ็กต์อาเรย์ |
| [setObjectDistribution(boolean value)](#setObjectDistribution-boolean-) | การกระจายอ็อบเจ็กต์ เมื่อเป็นจริง เนื้อหาของอาเรย์จะถูกจัดระยะห่างให้เต็มความกว้างสูงสุดของอ็อบเจ็กต์อาเรย์ |
| [getRowSpacingRule()](#getRowSpacingRule--) | ประเภทของการเว้นระยะแนวตั้งระหว่างองค์ประกอบของอาเรย์ ค่าเริ่มต้น: SingleLineGap |
| [setRowSpacingRule(int value)](#setRowSpacingRule-int-) | ประเภทของการเว้นระยะแนวตั้งระหว่างองค์ประกอบของอาเรย์ ค่าเริ่มต้น: SingleLineGap |
| [getRowSpacing()](#getRowSpacing--) | การเว้นระยะระหว่างแถวของอาเรย์ ใช้เฉพาะเมื่อ RowSpacingRule ถูกตั้งเป็น 3 ซึ่งหน่วยวัดจะเป็น points หรือ Multiple ซึ่งหน่วยวัดจะเป็น half-lines |
| [setRowSpacing(long value)](#setRowSpacing-long-) | การเว้นระยะระหว่างแถวของอาเรย์ ใช้เฉพาะเมื่อ RowSpacingRule ถูกตั้งเป็น 3 ซึ่งหน่วยวัดจะเป็น points หรือ Multiple ซึ่งหน่วยวัดจะเป็น half-lines |
| [getChildren()](#getChildren--) | ดึงองค์ประกอบลูก |

### MathArray(IMathElement element) {#MathArray-com.aspose.slides.IMathElement-}
```
public MathArray(IMathElement element)
```

สร้างอาเรย์ทางคณิตศาสตร์และวางองค์ประกอบที่ระบุไว้ในนั้น

--------------------

> ```
> Example:
>  
>  MathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | องค์ประกอบที่ต้องวางในอาเรย์ |

### MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements) {#MathArray-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--}
```
public MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements)
```

สร้างอาเรย์ทางคณิตศาสตร์และวางองค์ประกอบที่ระบุไว้ในอาเรย์

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| elements | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.IMathElement> | องค์ประกอบที่ต้องวางในอาเรย์ |

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

**ผลลัพธ์:**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBaseJustification() {#getBaseJustification--}
```
public final int getBaseJustification()
```

ระบุการจัดตำแหน่งของอาเรย์สัมพันธ์กับข้อความโดยรอบ ข้อความนอกอาเรย์สามารถจัดตำแหน่งกับด้านล่าง ด้านบน หรือศูนย์กลางของอาเรย์ ค่าเริ่มต้น: Center

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```

**ผลลัพธ์:**
int
### setBaseJustification(int value) {#setBaseJustification-int-}
```
public final void setBaseJustification(int value)
```

ระบุการจัดตำแหน่งของอาเรย์สัมพันธ์กับข้อความโดยรอบ ข้อความนอกอาเรย์สามารถจัดตำแหน่งกับด้านล่าง ด้านบน หรือศูนย์กลางของอาเรย์ ค่าเริ่มต้น: Center

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

การกระจายสูงสุด เมื่อเป็นจริง อาเรย์จะถูกจัดระยะห่างให้เต็มความกว้างสูงสุดขององค์ประกอบที่บรรจุ (หน้า, คอลัมน์, เซลล์ ฯลฯ)

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```

**ผลลัพธ์:**
boolean
### setMaximumDistribution(boolean value) {#setMaximumDistribution-boolean-}
```
public final void setMaximumDistribution(boolean value)
```

การกระจายสูงสุด เมื่อเป็นจริง อาเรย์จะถูกจัดระยะห่างให้เต็มความกว้างสูงสุดขององค์ประกอบที่บรรจุ (หน้า, คอลัมน์, เซลล์ ฯลฯ)

--------------------

> ```
> Example:
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

การกระจายอ็อบเจ็กต์ เมื่อเป็นจริง เนื้อหาของอาเรย์จะถูกจัดระยะห่างให้เต็มความกว้างสูงสุดของอ็อบเจ็กต์อาเรย์

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```

**ผลลัพธ์:**
boolean
### setObjectDistribution(boolean value) {#setObjectDistribution-boolean-}
```
public final void setObjectDistribution(boolean value)
```

การกระจายอ็อบเจ็กต์ เมื่อเป็นจริง เนื้อหาของอาเรย์จะถูกจัดระยะห่างให้เต็มความกว้างสูงสุดของอ็อบเจ็กต์อาเรย์

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

ประเภทของการเว้นระยะแนวตั้งระหว่างองค์ประกอบของอาเรย์ ค่าเริ่มต้น: SingleLineGap

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
> ```

**ผลลัพธ์:**
int
### setRowSpacingRule(int value) {#setRowSpacingRule-int-}
```
public final void setRowSpacingRule(int value)
```

ประเภทของการเว้นระยะแนวตั้งระหว่างองค์ประกอบของอาเรย์ ค่าเริ่มต้น: SingleLineGap

--------------------

> ```
> ตัวอย่าง:
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

การเว้นระยะระหว่างแถวของอาเรย์ ใช้เฉพาะเมื่อ RowSpacingRule ถูกตั้งเป็น 3 ซึ่งหน่วยวัดจะเป็น points หรือ Multiple ซึ่งหน่วยวัดจะเป็น half-lines ค่าเริ่มต้น: 0

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**ผลลัพธ์:**
long
### setRowSpacing(long value) {#setRowSpacing-long-}
```
public final void setRowSpacing(long value)
```

การเว้นระยะระหว่างแถวของอาเรย์ ใช้เฉพาะเมื่อ RowSpacingRule ถูกตั้งเป็น 3 ซึ่งหน่วยวัดจะเป็น points หรือ Multiple ซึ่งหน่วยวัดจะเป็น half-lines ค่าเริ่มต้น: 0

--------------------

> ```
> Example:
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

ดึงองค์ประกอบลูก

**ผลลัพธ์:**
com.aspose.slides.IMathElement[]