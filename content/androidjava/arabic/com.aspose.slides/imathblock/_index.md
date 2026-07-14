---
title: IMathBlock
second_title: Aspose.Slides للـ Android عبر مرجع API جافا
description: يحدد نموذجًا لنص رياضي موجود داخل MathParagraph ويبدأ على سطر منفصل.
type: docs
url: /ar/com.aspose.slides/imathblock/
---
**كل الواجهات المنفذة:**
[com.aspose.slides.IMathElementCollection](../../com.aspose.slides/imathelementcollection), [com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBlock extends IMathElementCollection, IMathElement
```

يحدد نموذجًا لنص رياضي موجود داخل MathParagraph ويبدأ على سطر منفصل. جميع مناطق الرياضيات، بما في ذلك المعادلات، التعابير، مصفوفات المعادلات أو التعابير، والصيغ، يتم تمثيلها بواسطة كتلة رياضية.

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathBlock();
> ```
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [delimit(char separatorCharacter)](#delimit-char-) | يفصل جميع العناصر الفرعية بالحرف الفاصل (بدون الأقواس) |
| [enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)](#enclose-char-char-char-) | يحيط العناصر الفرعية لهذه الكتلة بأحرف محددة مثل الأقواس أو غيرها كإطار ويفصلها بحرف فاصل |
| [joinBlock(IMathBlock other)](#joinBlock-com.aspose.slides.IMathBlock-) | يجمع كتلة رياضية أخرى مع هذه الكتلة |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | يحفظ محتوى هذا [IMathBlock](../../com.aspose.slides/imathblock) كـ MathML |
### delimit(char separatorCharacter) {#delimit-char-}
```
public abstract IMathDelimiter delimit(char separatorCharacter)
```

يفصل جميع العناصر الفرعية بالحرف الفاصل (بدون الأقواس)

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.delimit('|');
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| separatorCharacter | char | الحرف المستخدم كفاصل |

**الإرجاع:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - نسخة من عنصر IMathDelimiter
### enclose(char beginningCharacter, char endingCharacter, char separatorCharacter) {#enclose-char-char-char-}
```
public abstract IMathDelimiter enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)
```

يحيط العناصر الفرعية لهذه الكتلة بأحرف محددة مثل الأقواس أو غيرها كإطار ويفصلها بحرف فاصل

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.enclose('{', '}', '%');
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| beginningCharacter | char | حرف البداية (عادة القوس الأيسر) |
| endingCharacter | char | حرف النهاية (عادة القوس الأيمن) |
| separatorCharacter | char | حرف الفاصل |

**الإرجاع:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - العنصر الرياضي من النوع [IMathDelimiter](../../com.aspose.slides/imathdelimiter) الذي يتضمن الأحرف المحددة كإطار ومحدد
### joinBlock(IMathBlock other) {#joinBlock-com.aspose.slides.IMathBlock-}
```
public abstract IMathBlock joinBlock(IMathBlock other)
```

يجمع كتلة رياضية أخرى مع هذه الكتلة

--------------------

> ```
> Example:
>  
>  IMathBlock block1 = new MathSuperscriptElement(new MathematicalText("c"), new MathematicalText("2")).join(new MathematicalText("="));
>  IMathBlock block2 = new MathSuperscriptElement(new MathematicalText("a"), new MathematicalText("2")).join(new MathematicalText("+"))
>  .join(new MathSuperscriptElement(new MathematicalText("b"), new MathematicalText("2")));
>  IMathBlock block3 = block1.joinBlock(block2);
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| other | [IMathBlock](../../com.aspose.slides/imathblock) | الكتلة المُضمَّنة |

**الإرجاع:**
[IMathBlock](../../com.aspose.slides/imathblock) - هذه الكتلة الرياضية بعد الجمع
### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public abstract void writeAsMathMl(OutputStream stream)
```

يحفظ محتوى هذا [IMathBlock](../../com.aspose.slides/imathblock) كـ MathML

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.OutputStream | دفق الهدف |