---
title: IMathArray
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: ระบุอาเรย์แนวตั้งของสมการหรือวัตถุทางคณิตศาสตร์ใด ๆ
type: docs
url: /th/com.aspose.slides/imatharray/
---
**ส่วนติดต่อที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathArray extends IMathElement
```

ระบุอาเรย์แนวตั้งของสมการหรือวัตถุทางคณิตศาสตร์ใด ๆ

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getArguments()](#getArguments--) | ชุดของรายการในอาเรย์ |
| [getBaseJustification()](#getBaseJustification--) | ระบุการจัดแนวของอาเรย์สัมพันธ์กับข้อความโดยรอบ ข้อความนอกอาเรย์สามารถจัดแนวกับด้านล่าง ด้านบน หรือกึ่งกลางของวัตถุอาเรย์ได้ |
| [setBaseJustification(int value)](#setBaseJustification-int-) | ระบุการจัดแนวของอาเรย์สัมพันธ์กับข้อความโดยรอบ ข้อความนอกอาเรย์สามารถจัดแนวกับด้านล่าง ด้านบน หรือกึ่งกลางของวัตถุอาเรย์ได้ |
| [getMaximumDistribution()](#getMaximumDistribution--) | การจัดสรรสูงสุด เมื่อเป็นจริง อาเรย์จะเว้นระยะให้เต็มความกว้างสูงสุดขององค์ประกอบที่บรรจุ (หน้า, คอลัมน์, เซลล์ ฯลฯ) |
| [setMaximumDistribution(boolean value)](#setMaximumDistribution-boolean-) | การจัดสรรสูงสุด เมื่อเป็นจริง อาเรย์จะเว้นระยะให้เต็มความกว้างสูงสุดขององค์ประกอบที่บรรจุ (หน้า, คอลัมน์, เซลล์ ฯลฯ) |
| [getObjectDistribution()](#getObjectDistribution--) | การจัดสรรวัตถุ เมื่อเป็นจริง เนื้อหาของอาเรย์จะเว้นระยะให้เต็มความกว้างสูงสุดของวัตถุอาเรย์ |
| [setObjectDistribution(boolean value)](#setObjectDistribution-boolean-) | การจัดสรรวัตถุ เมื่อเป็นจริง เนื้อหาของอาเรย์จะเว้นระยะให้เต็มความกว้างสูงสุดของวัตถุอาเรย์ |
| [getRowSpacingRule()](#getRowSpacingRule--) | ประเภทของช่องว่างแนวตั้งระหว่างองค์ประกอบของอาเรย์ |
| [setRowSpacingRule(int value)](#setRowSpacingRule-int-) | ประเภทของช่องว่างแนวตั้งระหว่างองค์ประกอบของอาเรย์ |
| [getRowSpacing()](#getRowSpacing--) | การเว้นระยะระหว่างแถวของอาเรย์ ใช้เฉพาะเมื่อ RowSpacingRule ตั้งค่าเป็น 3 โดยที่หน่วยวัดเป็นจุดสำหรับแบบ Exact หรือเป็นครึ่งบรรทัดสำหรับแบบ Multiple |
| [setRowSpacing(long value)](#setRowSpacing-long-) | การเว้นระยะระหว่างแถวของอาเรย์ ใช้เฉพาะเมื่อ RowSpacingRule ตั้งค่าเป็น 3 โดยที่หน่วยวัดเป็นจุดสำหรับแบบ Exact หรือเป็นครึ่งบรรทัดสำหรับแบบ Multiple |

### getArguments() {#getArguments--}
```
public abstract IMathElementCollection getArguments()
```

ชุดของรายการในอาเรย์

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.getArguments().add(new MathematicalText("item2"));
> ```

**คืนค่า:**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBaseJustification() {#getBaseJustification--}
```
public abstract int getBaseJustification()
```

ระบุการจัดแนวของอาเรย์สัมพันธ์กับข้อความโดยรอบ ข้อความนอกอาเรย์สามารถจัดแนวกับด้านล่าง ด้านบน หรือกึ่งกลางของวัตถุอาเรย์ได้ ค่าเริ่มต้น: Center

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```

**คืนค่า:**
int
### setBaseJustification(int value) {#setBaseJustification-int-}
```
public abstract void setBaseJustification(int value)
```

ระบุการจัดแนวของอาเรย์สัมพันธ์กับข้อความโดยรอบ ข้อความนอกอาเรย์สามารถจัดแนวกับด้านล่าง ด้านบน หรือกึ่งกลางของวัตถุอาเรย์ได้ ค่าเริ่มต้น: Center

--------------------

> ```
> Example:
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
public abstract boolean getMaximumDistribution()
```

การจัดสรรสูงสุด เมื่อเป็นจริง อาเรย์จะเว้นระยะให้เต็มความกว้างสูงสุดขององค์ประกอบที่บรรจุ (หน้า, คอลัมน์, เซลล์ ฯลฯ)

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```

**คืนค่า:**
boolean
### setMaximumDistribution(boolean value) {#setMaximumDistribution-boolean-}
```
public abstract void setMaximumDistribution(boolean value)
```

การจัดสรรสูงสุด เมื่อเป็นจริง อาเรย์จะเว้นระยะให้เต็มความกว้างสูงสุดขององค์ประกอบที่บรรจุ (หน้า, คอลัมน์, เซลล์ ฯลฯ)

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
public abstract boolean getObjectDistribution()
```

การจัดสรรวัตถุ เมื่อเป็นจริง เนื้อหาของอาเรย์จะเว้นระยะให้เต็มความกว้างสูงสุดของวัตถุอาเรย์

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```

**คืนค่า:**
boolean
### setObjectDistribution(boolean value) {#setObjectDistribution-boolean-}
```
public abstract void setObjectDistribution(boolean value)
```

การจัดสรรวัตถุ เมื่อเป็นจริง เนื้อหาของอาเรย์จะเว้นระยะให้เต็มความกว้างสูงสุดของวัตถุอาเรย์

--------------------

> ```
> Example:
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
public abstract int getRowSpacingRule()
```

ประเภทของช่องว่างแนวตั้งระหว่างองค์ประกอบของอาเรย์

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
> ```

**คืนค่า:**
int
### setRowSpacingRule(int value) {#setRowSpacingRule-int-}
```
public abstract void setRowSpacingRule(int value)
```

ประเภทของช่องว่างแนวตั้งระหว่างองค์ประกอบของอาเรย์

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
public abstract long getRowSpacing()
```

การเว้นระยะระหว่างแถวของอาเรย์ ใช้เฉพาะเมื่อ RowSpacingRule ตั้งค่าเป็น 3 โดยที่หน่วยวัดเป็นจุดสำหรับแบบ Exact หรือเป็นครึ่งบรรทัดสำหรับแบบ Multiple ค่าเริ่มต้น: 0

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**คืนค่า:**
long
### setRowSpacing(long value) {#setRowSpacing-long-}
```
public abstract void setRowSpacing(long value)
```

การเว้นระยะระหว่างแถวของอาเรย์ ใช้เฉพาะเมื่อ RowSpacingRule ตั้งค่าเป็น 3 โดยที่หน่วยวัดเป็นจุดสำหรับแบบ Exact หรือเป็นครึ่งบรรทัดสำหรับแบบ Multiple ค่าเริ่มต้น: 0

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