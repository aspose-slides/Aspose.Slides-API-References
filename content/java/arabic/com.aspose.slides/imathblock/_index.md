---
title: IMathBlock
second_title: مرجع API Aspose.Slides للـ Java
description: يحدد مثالًا لنص رياضي موجود داخل MathParagraph ويبدأ في سطره الخاص.
type: docs
url: /ar/com.aspose.slides/imathblock/
---
**جميع الواجهات المُنفذة:**
[com.aspose.slides.IMathElementCollection](../../com.aspose.slides/imathelementcollection), [com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBlock extends IMathElementCollection, IMathElement
```

يحدد مثالًا لنص رياضي موجود داخل MathParagraph ويبدأ في سطره الخاص. تم تمثيل جميع مناطق الرياضيات، بما في ذلك المعادلات، التعابير، مصفوفات المعادلات أو التعابير، والصيغ، بواسطة كتلة رياضية.

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathBlock();
> ```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [delimit(char separatorCharacter)](#delimit-char-) | يفصل جميع العناصر الفرعية باستخدام حرف الفاصل (دون الأقواس) |
| [enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)](#enclose-char-char-char-) | يحيط العناصر الفرعية لهذه الكتلة بأحرف محددة مثل القوس أو غيره كإطار ويقسمها باستخدام حرف الفاصل |
| [joinBlock(IMathBlock other)](#joinBlock-com.aspose.slides.IMathBlock-) | يجمع كتلة رياضية أخرى مع هذه الكتلة |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | يحفظ محتوى هذا [IMathBlock](../../com.aspose.slides/imathblock) كـ MathML |
### delimit(char separatorCharacter) {#delimit-char-}
```
public abstract IMathDelimiter delimit(char separatorCharacter)
```

يفصل جميع العناصر الفرعية باستخدام حرف الفاصل (دون الأقواس)

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.delimit('|');
> ```


**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| separatorCharacter | char | الحرف المستخدم كفاصل |

**القيمة المرجعة:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - مثال على عنصر IMathDelimiter
### enclose(char beginningCharacter, char endingCharacter, char separatorCharacter) {#enclose-char-char-char-}
```
public abstract IMathDelimiter enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)
```

يحيط العناصر الفرعية لهذه الكتلة بأحرف محددة مثل القوس أو غيره كإطار ويقسمها باستخدام حرف الفاصل

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.enclose('{', '}', '%');
> ```


**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| beginningCharacter | char | الحرف الابتدائي (عادةً القوس الأيسر) |
| endingCharacter | char | الحرف النهائي (عادةً القوس الأيمن) |
| separatorCharacter | char | حرف الفاصل |

**القيمة المرجعة:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - عنصر رياضي من النوع [IMathDelimiter](../../com.aspose.slides/imathdelimiter) والذي يتضمن الأحرف المحددة كإطار وفاصل
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

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| other | [IMathBlock](../../com.aspose.slides/imathblock) | الكتلة المتصلة |

**القيمة المرجعة:**
[IMathBlock](../../com.aspose.slides/imathblock) - هذه الكتلة الرياضية بعد الانضمام
### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public abstract void writeAsMathMl(OutputStream stream)
```

يحفظ محتوى هذا [IMathBlock](../../com.aspose.slides/imathblock) كـ MathML

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.OutputStream | دفق الهدف |