---
title: MathNaryOperator
second_title: Aspose.Slides สำหรับ Java – เอกสารอ้างอิง API
description: ระบุวัตถุคณิตศาสตร์แบบ N-ary เช่น การบวกและอินทิกรัล.
type: docs
url: /th/com.aspose.slides/mathnaryoperator/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**
[com.aspose.slides.IMathNaryOperator](../../com.aspose.slides/imathnaryoperator), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathNaryOperator extends MathElementBase implements IMathNaryOperator, IHasControlCharacterProperties
```

ระบุวัตถุคณิตศาสตร์แบบ N-ary เช่น การบวกและอินทิกรัล ประกอบด้วยตัวดำเนินการ ฐาน (หรือ operand) และขีดบนและขีดล่างที่เป็นตัวเลือก ตัวอย่างของตัวดำเนินการ N-ary ได้แก่ การบวก, ยูเนียน, อินเตอร์เซคชัน, อินทิกรัล

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
> ```
## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)](#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | เริ่มต้นอินสแตนซ์ใหม่ของคลาส MathNaryOperator |
| [MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)](#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | เริ่มต้นอินสแตนซ์ใหม่ของคลาส MathNaryOperator |
| [MathNaryOperator(char operatorSymbol, IMathElement baseArgument)](#MathNaryOperator-char-com.aspose.slides.IMathElement-) | เริ่มต้นอินสแตนซ์ใหม่ของคลาส MathNaryOperator |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getBase()](#getBase--) | อาร์กิวเมนต์ฐาน |
| [getSubscript()](#getSubscript--) | ระบุอาร์กิวเมนต์ตัวล่างที่, ตัวอย่างเช่น ในกรณีของอินทิกรัล, ตั้งค่าขีดล่าง |
| [getSuperscript()](#getSuperscript--) | ระบุอาร์กิวเมนต์ตัวบนที่, ตัวอย่างเช่น ในกรณีของอินทิกรัล, ตั้งค่าขีดบน |
| [getOperator()](#getOperator--) | อักขระตัวดำเนินการ Nary ตัวอย่างเช่น: '\\u2211', '\\u222b' |
| [setOperator(char value)](#setOperator-char-) | อักขระตัวดำเนินการ Nary ตัวอย่างเช่น: '\\u2211', '\\u222b' |
| [getLimitLocation()](#getLimitLocation--) | ตำแหน่งของขีด (ตัวล่างและตัวบน) |
| [setLimitLocation(int value)](#setLimitLocation-int-) | ตำแหน่งของขีด (ตัวล่างและตัวบน) |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | ตัวอักษรตัวดำเนินการขยายตามแนวตั้งให้ตรงกับความสูงของ operand |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | ตัวอักษรตัวดำเนินการขยายตามแนวตั้งให้ตรงกับความสูงของ operand |
| [getHideSubscript()](#getHideSubscript--) | ซ่อนตัวล่าง |
| [setHideSubscript(boolean value)](#setHideSubscript-boolean-) | ซ่อนตัวล่าง |
| [getHideSuperscript()](#getHideSuperscript--) | ซ่อนตัวบน |
| [setHideSuperscript(boolean value)](#setHideSuperscript-boolean-) | ซ่อนตัวบน |
| [getChildren()](#getChildren--) | รับองค์ประกอบลูก |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | คุณสมบัติตัวอักษรควบคุม |
### MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit) {#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)
```

เริ่มต้นอินสแตนซ์ใหม่ของคลาส MathNaryOperator

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathNaryOperator('\u2211', new MathematicalText("i"), new MathematicalText("i=0"), new MathematicalText("\ud835\udc5b"));
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| operatorSymbol | char | สัญลักษณ์ตัวดำเนินการ Nary |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | อาร์กิวเมนต์ฐาน |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | ขีดล่าง |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | ขีดบน |

### MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit) {#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)
```

เริ่มต้นอินสแตนซ์ใหม่ของคลาส MathNaryOperator

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathNaryOperator('\u2211', new MathematicalText("i"), new MathematicalText("i"));
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| operatorSymbol | char | สัญลักษณ์ตัวดำเนินการ Nary |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | อาร์กิวเมนต์ฐาน |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | ขีดล่าง |

### MathNaryOperator(char operatorSymbol, IMathElement baseArgument) {#MathNaryOperator-char-com.aspose.slides.IMathElement-}
```
public MathNaryOperator(char operatorSymbol, IMathElement baseArgument)
```

เริ่มต้นอินสแตนซ์ใหม่ของคลาส MathNaryOperator

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathNaryOperator('\u2211', new MathematicalText("i"));
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| operatorSymbol | char | สัญลักษณ์ตัวดำเนินการ Nary |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | อาร์กิวเมนต์ฐาน |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

อาร์กิวเมนต์ฐาน

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement baseArg = naryOperator.getBase();
> ```

**คืนค่า:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public final IMathElement getSubscript()
```

ระบุอาร์กิวเมนต์ตัวล่างที่, ตัวอย่างเช่น ในกรณีของอินทิกรัล, ตั้งค่าขีดล่าง

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement subscriptArg = naryOperator.getSubscript();
> ```

**คืนค่า:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public final IMathElement getSuperscript()
```

ระบุอาร์กิวเมนต์ตัวบนที่, ตัวอย่างเช่น ในกรณีของอินทิกรัล, ตั้งค่าขีดบน

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement superscriptArg = naryOperator.getSuperscript();
> ```

**คืนค่า:**
[IMathElement](../../com.aspose.slides/imathelement)
### getOperator() {#getOperator--}
```
public final char getOperator()
```

อักขระตัวดำเนินการ Nary ตัวอย่างเช่น: '\\u2211', '\\u222b'

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```

**คืนค่า:**
char
### setOperator(char value) {#setOperator-char-}
```
public final void setOperator(char value)
```

อักขระตัวดำเนินการ Nary ตัวอย่างเช่น: '\\u2211', '\\u222b'

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | char |  |

### getLimitLocation() {#getLimitLocation--}
```
public final int getLimitLocation()
```

ตำแหน่งของขีด (ตัวล่างและตัวบน)

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**คืนค่า:**
int
### setLimitLocation(int value) {#setLimitLocation-int-}
```
public final void setLimitLocation(int value)
```

ตำแหน่งของขีด (ตัวล่างและตัวบน)

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public final boolean getGrowToMatchOperandHeight()
```

ตัวอักษรตัวดำเนินการขยายตามแนวตั้งให้ตรงกับความสูงของ operand

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**คืนค่า:**
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public final void setGrowToMatchOperandHeight(boolean value)
```

ตัวอักษรตัวดำเนินการขยายตามแนวตั้งให้ตรงกับความสูงของ operand

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getHideSubscript() {#getHideSubscript--}
```
public final boolean getHideSubscript()
```

ซ่อนตัวล่าง

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**คืนค่า:**
boolean
### setHideSubscript(boolean value) {#setHideSubscript-boolean-}
```
public final void setHideSubscript(boolean value)
```

ซ่อนตัวล่าง

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getHideSuperscript() {#getHideSuperscript--}
```
public final boolean getHideSuperscript()
```

ซ่อนตัวบน

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**คืนค่า:**
boolean
### setHideSuperscript(boolean value) {#setHideSuperscript-boolean-}
```
public final void setHideSuperscript(boolean value)
```

ซ่อนตัวบน

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

รับองค์ประกอบลูก

**คืนค่า:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

คุณสมบัติตัวอักษรควบคุม

**คืนค่า:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps