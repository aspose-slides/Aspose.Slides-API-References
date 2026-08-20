---
title: IMathArray
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: ระบุอาเรย์แนวตั้งของสมการหรือวัตถุคณิตศาสตร์ใด ๆ
type: docs
url: /th/com.aspose.slides/imatharray/
---
**อินเทอร์เฟซที่ใช้งานทั้งหมด:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathArray extends IMathElement
```

ระบุอาเรย์แนวตั้งของสมการหรือวัตถุคณิตศาสตร์ใด ๆ

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getArguments()](#getArguments--) | ชุดของรายการของอาเรย์ |
| [getBaseJustification()](#getBaseJustification--) | ระบุการจัดแนวของอาเรย์สัมพันธ์กับข้อความโดยรอบ ข้อความที่อยู่นอกอาเรย์สามารถจัดแนวกับด้านล่าง ด้านบน หรือศูนย์กลางของอ็อบเจ็กต์อาเรย์ได้ |
| [setBaseJustification(int value)](#setBaseJustification-int-) | ระบุการจัดแนวของอาเรย์สัมพันธ์กับข้อความโดยรอบ ข้อความที่อยู่นอกอาเรย์สามารถจัดแนวกับด้านล่าง ด้านบน หรือศูนย์กลางของอ็อบเจ็กต์อาเรย์ได้ |
| [getMaximumDistribution()](#getMaximumDistribution--) | การกระจายสูงสุด เมื่อเป็นจริง อาเรย์จะถูกจัดช่องว่างให้เต็มความกว้างสูงสุดขององค์ประกอบที่บรรจุ (หน้า, คอลัมน์, เซลล์ ฯลฯ) |
| [setMaximumDistribution(boolean value)](#setMaximumDistribution-boolean-) | การกระจายสูงสุด เมื่อเป็นจริง อาเรย์จะถูกจัดช่องว่างให้เต็มความกว้างสูงสุดขององค์ประกอบที่บรรจุ (หน้า, คอลัมน์, เซลล์ ฯลฯ) |
| [getObjectDistribution()](#getObjectDistribution--) | การกระจายตามอ็อบเจ็กต์ เมื่อเป็นจริง เนื้อหาของอาเรย์จะถูกจัดช่องว่างให้เต็มความกว้างสูงสุดของอ็อบเจ็กต์อาเรย์ |
| [setObjectDistribution(boolean value)](#setObjectDistribution-boolean-) | การกระจายตามอ็อบเจ็กต์ เมื่อเป็นจริง เนื้อหาของอาเรย์จะถูกจัดช่องว่างให้เต็มความกว้างสูงสุดของอ็อบเจ็กต์อาเรย์ |
| [getRowSpacingRule()](#getRowSpacingRule--) | ประเภทของระยะห่างแนวตั้งระหว่างองค์ประกอบของอาเรย์ |
| [setRowSpacingRule(int value)](#setRowSpacingRule-int-) | ประเภทของระยะห่างแนวตั้งระหว่างองค์ประกอบของอาเรย์ |
| [getRowSpacing()](#getRowSpacing--) | ระยะห่างระหว่างแถวของอาเรย์ ใช้เฉพาะเมื่อ RowSpacingRule ถูกตั้งค่าเป็น 3 โดยหน่วยวัดจะเป็นจุด (Exact) หรือครึ่งบรรทัด (Multiple) |
| [setRowSpacing(long value)](#setRowSpacing-long-) | ระยะห่างระหว่างแถวของอาเรย์ ใช้เฉพาะเมื่อ RowSpacingRule ถูกตั้งค่าเป็น 3 โดยหน่วยวัดจะเป็นจุด (Exact) หรือครึ่งบรรทัด (Multiple) |
### getArguments() {#getArguments--}
```
public abstract IMathElementCollection getArguments()
```


ชุดของรายการของอาเรย์

--------------------

> ```
> ตัวอย่าง:
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


ระบุการจัดแนวของอาเรย์สัมพันธ์กับข้อความโดยรอบ ข้อความที่อยู่นอกอาเรย์สามารถจัดแนวกับด้านล่าง ด้านบน หรือศูนย์กลางของอ็อบเจ็กต์อาเรย์ได้ ค่าเริ่มต้น: Center

--------------------

> ```
> ตัวอย่าง:
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


ระบุการจัดแนวของอาเรย์สัมพันธ์กับข้อความโดยรอบ ข้อความที่อยู่นอกอาเรย์สามารถจัดแนวกับด้านล่าง ด้านบน หรือศูนย์กลางของอ็อบเจ็กต์อาเรย์ได้ ค่าเริ่มต้น: Center

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |
### getMaximumDistribution() {#getMaximumDistribution--}
```
public abstract boolean getMaximumDistribution()
```


การกระจายสูงสุด เมื่อเป็นจริง อาเรย์จะถูกจัดช่องว่างให้เต็มความกว้างสูงสุดขององค์ประกอบที่บรรจุ (หน้า, คอลัมน์, เซลล์ ฯลฯ)

--------------------

> ```
> ตัวอย่าง:
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


การกระจายสูงสุด เมื่อเป็นจริง อาเรย์จะถูกจัดช่องว่างให้เต็มความกว้างสูงสุดขององค์ประกอบที่บรรจุ (หน้า, คอลัมน์, เซลล์ ฯลฯ)

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getObjectDistribution() {#getObjectDistribution--}
```
public abstract boolean getObjectDistribution()
```


การกระจายตามอ็อบเจ็กต์ เมื่อเป็นจริง เนื้อหาของอาเรย์จะถูกจัดช่องว่างให้เต็มความกว้างสูงสุดของอ็อบเจ็กต์อาเรย์

--------------------

> ```
> ตัวอย่าง:
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


การกระจายตามอ็อบเจ็กต์ เมื่อเป็นจริง เนื้อหาของอาเรย์จะถูกจัดช่องว่างให้เต็มความกว้างสูงสุดของอ็อบเจ็กต์อาเรย์

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getRowSpacingRule() {#getRowSpacingRule--}
```
public abstract int getRowSpacingRule()
```


ประเภทของระยะห่างแนวตั้งระหว่างองค์ประกอบของอาเรย์

--------------------

> ```
> ตัวอย่าง:
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


ประเภทของระยะห่างแนวตั้งระหว่างองค์ประกอบของอาเรย์

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |
### getRowSpacing() {#getRowSpacing--}
```
public abstract long getRowSpacing()
```


ระยะห่างระหว่างแถวของอาเรย์ ใช้เฉพาะเมื่อ RowSpacingRule ถูกตั้งค่าเป็น 3 โดยหน่วยวัดจะเป็นจุด (Exact) หรือครึ่งบรรทัด (Multiple) ค่าเริ่มต้น: 0

--------------------

> ```
> ตัวอย่าง:
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


ระยะห่างระหว่างแถวของอาเรย์ ใช้เฉพาะเมื่อ RowSpacingRule ถูกตั้งค่าเป็น 3 โดยหน่วยวัดจะเป็นจุด (Exact) หรือครึ่งบรรทัด (Multiple) ค่าเริ่มต้น: 0

--------------------

> ```
> ตัวอย่าง:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | long |  |