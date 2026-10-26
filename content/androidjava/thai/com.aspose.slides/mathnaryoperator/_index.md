---
title: MathNaryOperator
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API
description: ระบุวัตถุคณิตศาสตร์ N-ary เช่น Summation และ Integral.
type: docs
url: /th/com.aspose.slides/mathnaryoperator/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IMathNaryOperator](../../com.aspose.slides/imathnaryoperator), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathNaryOperator extends MathElementBase implements IMathNaryOperator, IHasControlCharacterProperties
```

ระบุวัตถุคณิตศาสตร์ N-ary เช่น Summation และ Integral ซึ่งประกอบด้วยเครื่องหมาย, ฐาน (หรือออพแรนด์) และขอบบนและขอบล่างที่เป็นตัวเลือก ตัวอย่างของเครื่องหมาย N-ary ได้แก่ Summation, Union, Intersection, Integral

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
> ```
## ตัวสร้าง

| ตัวสร้าง | คำอธิบาย |
| --- | --- |
| [MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)](#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Initialises a new instance of the MathNaryOperator class. |
| [MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)](#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Initialises a new instance of the MathNaryOperator class. |
| [MathNaryOperator(char operatorSymbol, IMathElement baseArgument)](#MathNaryOperator-char-com.aspose.slides.IMathElement-) | Initialises a new instance of the MathNaryOperator class. |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getBase()](#getBase--) | Base argument |
| [getSubscript()](#getSubscript--) | ระบุอาร์กิวเมนต์ตัวล่างที่ เช่น ในกรณีของอินทิกรัล จะกำหนดขอบล่าง |
| [getSuperscript()](#getSuperscript--) | ระบุอาร์กิวเมนต์ตัวบนที่ เช่น ในกรณีของอินทิกรัล จะกำหนดขอบบน |
| [getOperator()](#getOperator--) | Nary Operator Character ตัวอย่าง: '\\u2211', '\\u222b' |
| [setOperator(char value)](#setOperator-char-) | Nary Operator Character ตัวอย่าง: '\\u2211', '\\u222b' |
| [getLimitLocation()](#getLimitLocation--) | ตำแหน่งของขอบ (ตัวล่างและตัวบน) |
| [setLimitLocation(int value)](#setLimitLocation-int-) | ตำแหน่งของขอบ (ตัวล่างและตัวบน) |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | ตัวอักษรเครื่องหมายเติบโตในแนวตั้งเพื่อให้ตรงกับความสูงของออพแรนด์ |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | ตัวอักษรเครื่องหมายเติบโตในแนวตั้งเพื่อให้ตรงกับความสูงของออพแรนด์ |
| [getHideSubscript()](#getHideSubscript--) | ซ่อนตัวล่าง |
| [setHideSubscript(boolean value)](#setHideSubscript-boolean-) | ซ่อนตัวล่าง |
| [getHideSuperscript()](#getHideSuperscript--) | ซ่อนตัวบน |
| [setHideSuperscript(boolean value)](#setHideSuperscript-boolean-) | ซ่อนตัวบน |
| [getChildren()](#getChildren--) | ดึงองค์ประกอบลูก |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | คุณสมบัติตัวอักษรควบคุม |
### MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit) {#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)
```


Initialises a new instance of the MathNaryOperator class.

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathNaryOperator('\u2211', new MathematicalText("i"), new MathematicalText("i=0"), new MathematicalText("\ud835\udc5b"));
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| operatorSymbol | char | Nary operator symbol |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Base argument |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Lower limit |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Upper limit |

### MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit) {#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)
```


Initialises a new instance of the MathNaryOperator class.

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathNaryOperator('\u2211', new MathematicalText("i"), new MathematicalText("i"));
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| operatorSymbol | char | Nary operator symbol |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Base argument |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Lower limit |

### MathNaryOperator(char operatorSymbol, IMathElement baseArgument) {#MathNaryOperator-char-com.aspose.slides.IMathElement-}
```
public MathNaryOperator(char operatorSymbol, IMathElement baseArgument)
```


Initialises a new instance of the MathNaryOperator class.

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathNaryOperator('\u2211', new MathematicalText("i"));
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| operatorSymbol | char | Nary operator symbol |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Base argument |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```


Base argument

--------------------

> ```
> Example:
>  
>  IMMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMMathElement baseArg = naryOperator.getBase();
> ```

**ค่าที่ส่งกลับ:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public final IMathElement getSubscript()
```


ระบุอาร์กิวเมนต์ตัวล่างที่ เช่น ในกรณีของอินทิกรัล จะกำหนดขอบล่าง

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement subscriptArg = naryOperator.getSubscript();
> ```

**ค่าที่ส่งกลับ:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public final IMathElement getSuperscript()
```


ระบุอาร์กิวเมนต์ตัวบนที่ เช่น ในกรณีของอินทิกรัล จะกำหนดขอบบน

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement superscriptArg = naryOperator.getSuperscript();
> ```

**ค่าที่ส่งกลับ:**
[IMathElement](../../com.aspose.slides/imathelement)
### getOperator() {#getOperator--}
```
public final char getOperator()
```


Nary Operator Character ตัวอย่าง: '\\u2211', '\\u222b'

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```

**ค่าที่ส่งกลับ:**
char
### setOperator(char value) {#setOperator-char-}
```
public final void setOperator(char value)
```


Nary Operator Character ตัวอย่าง: '\\u2211', '\\u222b'

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | char |  |

### getLimitLocation() {#getLimitLocation--}
```
public final int getLimitLocation()
```


ตำแหน่งของขอบ (ตัวล่างและตัวบน)

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**ค่าที่ส่งกลับ:**
int
### setLimitLocation(int value) {#setLimitLocation-int-}
```
public final void setLimitLocation(int value)
```


ตำแหน่งของขอบ (ตัวล่างและตัวบน)

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public final boolean getGrowToMatchOperandHeight()
```


ตัวอักษรเครื่องหมายเติบโตในแนวตั้งเพื่อให้ตรงกับความสูงของออพแรนด์

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**ค่าที่ส่งกลับ:**
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public final void setGrowToMatchOperandHeight(boolean value)
```


ตัวอักษรเครื่องหมายเติบโตในแนวตั้งเพื่อให้ตรงกับความสูงของออพแรนด์

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
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

**ค่าที่ส่งกลับ:**
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
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getHideSuperscript() {#getHideSuperscript--}
```
public final boolean getHideSuperscript()
```


ซ่อนตัวบน

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**ค่าที่ส่งกลับ:**
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
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


ดึงองค์ประกอบลูก

**ค่าที่ส่งกลับ:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


คุณสมบัติตัวอักษรควบคุม

**ค่าที่ส่งกลับ:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps