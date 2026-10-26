---
title: IMathBlock
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ Java
description: ระบุอินสแตนซ์ของข้อความคณิตศาสตร์ที่อยู่ภายใน MathParagraph และเริ่มต้นในบรรทัดของมันเอง.
type: docs
url: /th/com.aspose.slides/imathblock/
---
**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**
[com.aspose.slides.IMathElementCollection](../../com.aspose.slides/imathelementcollection), [com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBlock extends IMathElementCollection, IMathElement
```

กำหนดอินสแตนซ์ของข้อความคณิตศาสตร์ที่อยู่ภายใน MathParagraph และเริ่มต้นในบรรทัดของมันเอง ทุกโซนคณิตศาสตร์ รวมถึงสมการ, นิพจน์, อาเรย์ของสมการหรือ นิพจน์, และสูตร ถูกแทนด้วยบล็อกคณิตศาสตร์

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathBlock();
> ```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [delimit(char separatorCharacter)](#delimit-char-) | จำกัดองค์ประกอบลูกทั้งหมดด้วยอักขระตัวคั่น (โดยไม่รวมวงเล็บ) |
| [enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)](#enclose-char-char-char-) | ล้อมรอบองค์ประกอบลูกของบล็อกนี้ด้วยอักขระที่กำหนดเช่นวงเล็บหรืออักขระอื่นเป็นกรอบและจำกัดด้วยอักขระตัวคั่น |
| [joinBlock(IMathBlock other)](#joinBlock-com.aspose.slides.IMathBlock-) | เชื่อมต่อบล็อกคณิตศาสตร์อื่นกับบล็อกนี้ |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | บันทึกเนื้อหาของ [IMathBlock](../../com.aspose.slides/imathblock) นี้เป็น MathML |
### delimit(char separatorCharacter) {#delimit-char-}
```
public abstract IMathDelimiter delimit(char separatorCharacter)
```

จำกัดองค์ประกอบลูกทั้งหมดด้วยอักขระตัวคั่น (โดยไม่รวมวงเล็บ)

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.delimit('|');
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| separatorCharacter | char | อักขระที่ใช้เป็นตัวคั่น |

**ผลลัพธ์:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - อินสแตนซ์ของอีลิเมนต์ IMathDelimiter

### enclose(char beginningCharacter, char endingCharacter, char separatorCharacter) {#enclose-char-char-char-}
```
public abstract IMathDelimiter enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)
```

ล้อมรอบองค์ประกอบลูกของบล็อกนี้ด้วยอักขระที่กำหนดเช่นวงเล็บหรืออักขระอื่นเป็นกรอบและจำกัดด้วยอักขระตัวคั่น

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.enclose('{', '}', '%');
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| beginningCharacter | char | อักขระเริ่มต้น (โดยทั่วไปคือวงเล็บซ้าย) |
| endingCharacter | char | อักขระสิ้นสุด (โดยทั่วไปคือวงเล็บขวา) |
| separatorCharacter | char | อักขระตัวคั่น |

**ผลลัพธ์:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - องค์ประกอบคณิตศาสตร์ประเภท [IMathDelimiter](../../com.aspose.slides/imathdelimiter) ที่รวมอักขระที่ระบุเป็นกรอบและตัวคั่น

### joinBlock(IMathBlock other) {#joinBlock-com.aspose.slides.IMathBlock-}
```
public abstract IMathBlock joinBlock(IMathBlock other)
```

เชื่อมต่อบล็อกคณิตศาสตร์อื่นกับบล็อกนี้

--------------------

> ```
> Example:
>  
>  IMathBlock block1 = new MathSuperscriptElement(new MathematicalText("c"), new MathematicalText("2")).join(new MathematicalText("="));
>  IMathBlock block2 = new MathSuperscriptElement(new MathematicalText("a"), new MathematicalText("2")).join(new MathematicalText("+"))
>  .join(new MathSuperscriptElement(new MathematicalText("b"), new MathematicalText("2")));
>  IMathBlock block3 = block1.joinBlock(block2);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| other | [IMathBlock](../../com.aspose.slides/imathblock) | บล็อกที่เชื่อมต่อ |

**ผลลัพธ์:**
[IMathBlock](../../com.aspose.slides/imathblock) - บล็อกคณิตศาสตร์นี้หลังจากการเชื่อมต่อ

### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public abstract void writeAsMathMl(OutputStream stream)
```

บันทึกเนื้อหาของ [IMathBlock](../../com.aspose.slides/imathblock) นี้เป็น MathML

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| stream | java.io.OutputStream | สตรีมเป้าหมาย |