---
title: IMathBlock
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: ระบุตัวอย่างของข้อความคณิตศาสตร์ที่อยู่ภายใน MathParagraph และเริ่มบรรทัดใหม่ของตนเอง.
type: docs
url: /th/com.aspose.slides/imathblock/
---
**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**  
[com.aspose.slides.IMathElementCollection](../../com.aspose.slides/imathelementcollection), [com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)  
```
public interface IMathBlock extends IMathElementCollection, IMathElement
```

ระบุตัวอย่างของข้อความคณิตศาสตร์ที่อยู่ภายใน MathParagraph และเริ่มบรรทัดใหม่ของตนเอง โซนคณิตศาสตร์ทั้งหมด ได้แก่ สมการ, นิพจน์, กลุ่มของสมการหรือ นิพจน์, และสูตร ถูกแทนด้วยบล็อกคณิตศาสตร์

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathBlock();
> ```
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [delimit(char separatorCharacter)](#delimit-char-) | แยกส่วนทุกองค์ประกอบย่อยด้วยอักขระตัวคั่น (โดยไม่รวมวงเล็บ) |
| [enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)](#enclose-char-char-char-) | หุ้มองค์ประกอบย่อยของบล็อกนี้ด้วยอักขระที่กำหนด เช่น วงเล็บ หรืออื่น ๆ เป็นกรอบและแยกด้วยอักขระตัวคั่น |
| [joinBlock(IMathBlock other)](#joinBlock-com.aspose.slides.IMathBlock-) | เชื่อมบล็อกคณิตศาสตร์อื่นกับบล็อกนี้ |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | บันทึกเนื้อหาของ [IMathBlock](../../com.aspose.slides/imathblock) นี้เป็น MathML |
### delimit(char separatorCharacter) {#delimit-char-}
```
public abstract IMathDelimiter delimit(char separatorCharacter)
```

แยกส่วนทุกองค์ประกอบย่อยด้วยอักขระตัวคั่น (โดยไม่รวมวงเล็บ)

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
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - อินสแตนซ์ของ IMathDelimiter

### enclose(char beginningCharacter, char endingCharacter, char separatorCharacter) {#enclose-char-char-char-}
```
public abstract IMathDelimiter enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)
```

หุ้มองค์ประกอบย่อยของบล็อกนี้ด้วยอักขระที่กำหนด เช่น วงเล็บ หรืออื่น ๆ เป็นกรอบและแยกด้วยอักขระตัวคั่น

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
| beginningCharacter | char | อักขระเริ่มต้น (โดยทั่วไปเป็นวงเล็บเปิด) |
| endingCharacter | char | อักขระสิ้นสุด (โดยทั่วไปเป็นวงเล็บปิด) |
| separatorCharacter | char | อักขระตัวคั่น |

**ผลลัพธ์:**  
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - อิลิเมนต์คณิตศาสตร์ประเภท [IMathDelimiter](../../com.aspose.slides/imathdelimiter) ที่รวมอักขระที่ระบุเป็นกรอบและตัวคั่น

### joinBlock(IMathBlock other) {#joinBlock-com.aspose.slides.IMathBlock-}
```
public abstract IMathBlock joinBlock(IMathBlock other)
```

เชื่อมบล็อกคณิตศาสตร์อื่นกับบล็อกนี้

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
| other | [IMathBlock](../../com.aspose.slides/imathblock) | บล็อกที่ต้องการเชื่อมต่อ |

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