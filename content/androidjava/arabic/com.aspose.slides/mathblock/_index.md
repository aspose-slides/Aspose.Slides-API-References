---
title: MathBlock
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يحدد مثالًا لنص رياضي موجود داخل MathParagraph ويبدأ في سطره الخاص.
type: docs
url: /ar/com.aspose.slides/mathblock/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**جميع الواجهات المنفذة:**
[com.aspose.slides.IMathBlock](../../com.aspose.slides/imathblock), com.aspose.slides.IDOMObject
```
public final class MathBlock extends MathElementBase implements IMathBlock, IDOMObject
```

يحدد مثالاً للنص الرياضي الموجود داخل MathParagraph ويبدأ في سطره الخاص. جميع مناطق الرياضيات، بما في ذلك المعادلات، والتعابير، ومصفوفات المعادلات أو التعابير، والصيغ يتم تمثيلها بواسطة كتلة الرياضيات.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock();
```
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [MathBlock()](#MathBlock--) | يُنشئ مثلاً جديداً من فئة MathBlock. |
| [MathBlock(IMathElement mathElement)](#MathBlock-com.aspose.slides.IMathElement-) | ينشئ كتلة رياضية جديدة ويضع العنصر المحدد فيها. |
| [MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements)](#MathBlock-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--) | ينشئ كتلة رياضية جديدة ويضع العناصر المحددة فيها. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getCount()](#getCount--) | يحصل على عدد عناصر الرياضيات الفرعية الموجودة فعلياً في المجموعة. |
| [get_Item(int index)](#get-Item-int-) | يحصل أو يضبط IMathElement عند الفهرس المحدد. |
| [set_Item(int index, IMathElement value)](#set-Item-int-com.aspose.slides.IMathElement-) | يحصل أو يضبط IMathElement عند الفهرس المحدد. |
| [isReadOnly()](#isReadOnly--) | يعيد false لأن مجموعة العناصر الفرعية يمكن تعديلها. |
| [getChildren()](#getChildren--) | احصل على العناصر الفرعية |
| [getParent_Immediate()](#getParent-Immediate--) | يعيد كائن Parent\_Immediate. |
| [add(IMathElement item)](#add-com.aspose.slides.IMathElement-) | يضيف عنصر رياضي إلى نهاية المجموعة. |
| [clear()](#clear--) | يزيل جميع العناصر من المجموعة. |
| [contains(IMathElement item)](#contains-com.aspose.slides.IMathElement-) | يحدد ما إذا كانت المجموعة تحتوي على قيمة معينة. |
| [copyTo(IMathElement[] array, int arrayIndex)](#copyTo-com.aspose.slides.IMathElement---int-) | نسخ إلى المصفوفة المحددة. |
| [remove(IMathElement item)](#remove-com.aspose.slides.IMathElement-) | يزيل أول حدوث لكائن معين من المجموعة. |
| [iterator()](#iterator--) | يعيد عداداً يتكرر عبر المجموعة. |
| [iteratorJava()](#iteratorJava--) | يعيد مكرراً (iterator) جافا للمجموعة بأكملها. |
| [indexOf(IMathElement item)](#indexOf-com.aspose.slides.IMathElement-) | يحدد فهرس عنصر رياضي معين في المجموعة. |
| [insert(int index, IMathElement item)](#insert-int-com.aspose.slides.IMathElement-) | يدرج MathElement في المجموعة عند الفهرس المحدد. |
| [removeAt(int index)](#removeAt-int-) | يزيل العنصر عند الفهرس المحدد في المجموعة. |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | ينضم عنصر رياضي إلى هذه الكتلة الرياضية |
| [join(String mathText)](#join-java.lang.String-) | ينضم نص رياضي إلى هذه الكتلة الرياضية |
| [joinBlock(IMathBlock other)](#joinBlock-com.aspose.slides.IMathBlock-) | ينضم كتلة رياضية أخرى إلى هذه |
| [delimit(char separatorCharacter)](#delimit-char-) | يفصل العناصر الفرعية بحرف فاصل (بدون الأقواس). |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | يحيط العناصر الفرعية لهذه الكتلة بأحرف محددة مثل الأقواس أو أحرف أخرى كإطار. |
| [enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)](#enclose-char-char-char-) | يحيط العناصر الفرعية لهذه الكتBlock بأحرف محددة مثل الأقواس أو أحرف أخرى كإطار ويفصلهم بحرف فاصل. |
| [toMathArray()](#toMathArray--) | يوضع العناصر الفرعية في مصفوفة رأسية. |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | يحفظ محتوى هذا [MathBlock](../../com.aspose.slides/mathblock) كـ MathML. |

### MathBlock() {#MathBlock--}
```
public MathBlock()
```

يُنشئ مثلاً جديداً من فئة MathBlock.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock();
> ```

### MathBlock(IMathElement mathElement) {#MathBlock-com.aspose.slides.IMathElement-}
```
public MathBlock(IMathElement mathElement)
```

ينشئ كتلة رياضية جديدة ويضع العنصر المحدد فيها.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | عنصر رياضي لوضعه في الكتلة |

### MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements) {#MathBlock-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--}
```
public MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements)
```

ينشئ كتلة رياضية جديدة ويضع العناصر المحددة فيها.

--------------------

> ```
> Example:
>  
>  var elems = new IMathElement[2] { new MathematicalText("item1"), new MathematicalText("item2") };
>  MathBlock mathBlock = new MathBlock(elems);
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| mathElements | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.IMathElement> | عناصر رياضية لوضعها في الكتلة |

### getCount() {#getCount--}
```
public final int getCount()
```

يحصل على عدد عناصر الرياضيات الفرعية الموجودة فعلياً في المجموعة. int للقراءة فقط.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  int count = mathBlock.getCount();
> ```

**القيمة المرجعة:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IMathElement get_Item(int index)
```

يحصل أو يضبط IMathElement عند الفهرس المحدد.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  IMathElement firstElem = mathBlock.get_Item(0);
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري للعنصر |

**القيمة المرجعة:**
[IMathElement](../../com.aspose.slides/imathelement) - العنصر الرياضي.

### set_Item(int index, IMathElement value) {#set-Item-int-com.aspose.slides.IMathElement-}
```
public final void set_Item(int index, IMathElement value)
```

يحصل أو يضبط IMathElement عند الفهرس المحدد.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  IMathElement firstElem = mathBlock.get_Item(0);
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري للعنصر |
| value | [IMathElement](../../com.aspose.slides/imathelement) | العنصر الرياضي. |

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

يعيد false لأن مجموعة العناصر الفرعية يمكن تعديلها.

**القيمة المرجعة:**
boolean
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

احصل على العناصر الفرعية

**القيمة المرجعة:**
com.aspose.slides.IMathElement[]
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

يعيد كائن Parent\_Immediate. IDOMObject للقراءة فقط.

**القيمة المرجعة:**
com.aspose.slides.IDOMObject
### add(IMathElement item) {#add-com.aspose.slides.IMathElement-}
```
public final void add(IMathElement item)
```

يضيف عنصر رياضي إلى نهاية المجموعة.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  mathBlock.add(new MathematicalText("+"));
>  mathBlock.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | العنصر IMathElement الذي يضاف إلى نهاية المجموعة. |

### clear() {#clear--}
```
public final void clear()
```

يزيل جميع العناصر من المجموعة.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  mathBlock.clear();
> ```

### contains(IMathElement item) {#contains-com.aspose.slides.IMathElement-}
```
public final boolean contains(IMathElement item)
```

يحدد ما إذا كانت المجموعة تحتوي على قيمة معينة.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.Add(plusElement);
>  mathBlock.Add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  boolean contains = mathBlock.Contains(plusElement);
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | الكائن لتحديد موقعه في المجموعة. |

**القيمة المرجعة:**
boolean - true إذا تم العثور على العنصر في المجموعة؛ وإلا false.

### copyTo(IMathElement[] array, int arrayIndex) {#copyTo-com.aspose.slides.IMathElement---int-}
```
public final void copyTo(IMathElement[] array, int arrayIndex)
```

نسخ إلى المصفوفة المحددة.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  IMathElement[] destinationArray = new IMathElement[mathBlock.Count];
>  mathBlock.copyTo(destinationArray, 0);
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| array | [IMathElement\[\]](../../com.aspose.slides/imathelement) | المصفوفة التي يتم النسخ إليها. |
| arrayIndex | int | الفهرس للبدء في النسخ. |

### remove(IMathElement item) {#remove-com.aspose.slides.IMathElement-}
```
public final boolean remove(IMathElement item)
```

يزيل أول حدوث لكائن معين من المجموعة.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.Add(plusElement);
>  mathBlock.Add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  mathBlock.Remove(plusElement);
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | الكائن لإزالته من المجموعة. |

**القيمة المرجعة:**
boolean - true إذا تم إزالة العنصر بنجاح من المجموعة؛ وإلا false. تُعيد هذه الطريقة false أيضاً إذا لم يُعثر على العنصر في المجموعة الأصلية.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMathElement> iterator()
```

يعيد عداداً يتكرر عبر المجموعة.

**القيمة المرجعة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMathElement> - IGenericEnumerator يمكن استخدامه للتكرار عبر المجموعة.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.IEnumerator iteratorJava()
```

يعيد مكرراً (iterator) جافا للمجموعة بأكملها.

**القيمة المرجعة:**
com.aspose.ms.System.Collections.IEnumerator - java.util.Iterator للمجموعة بأكملها.

### indexOf(IMathElement item) {#indexOf-com.aspose.slides.IMathElement-}
```
public final int indexOf(IMathElement item)
```

يحدد فهرس عنصر رياضي معين في المجموعة.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  int index = mathBlock.indexOf(plusElement);
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | العنصر لتحديد موقعه في المجموعة. |

**القيمة المرجعة:**
int - فهرس العنصر إذا وُجد في المجموعة؛ وإلا -1.

### insert(int index, IMathElement item) {#insert-int-com.aspose.slides.IMathElement-}
```
public final void insert(int index, IMathElement item)
```

يدرج MathElement في المجموعة عند الفهرس المحدد.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري الذي يُدرج عنده MathElement. |
| item | [IMathElement](../../com.aspose.slides/imathelement) | الـ MathElement الذي يُدرج. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

يزيل العنصر عند الفهرس المحدد في المجموعة.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  mathBlock.removeAt(2);
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري للعنصر الذي يُزال. |

### join(IMathElement mathElement) {#join-com.aspose.slides.IMathElement-}
```
public IMathBlock join(IMathElement mathElement)
```

ينضم عنصر رياضي إلى هذه الكتلة الرياضية

--------------------

> ```
> Example:
>  
>  IMathElement element1 = new MathematicalText("x");
>  IMathElement element2 = new MathematicalText("y");
>  IMathBlock block = element1.join(element2);
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | العنصر الذي يُنضم |

**القيمة المرجعة:**
[IMathBlock](../../com.aspose.slides/imathblock) - النسخة الحالية من IMathBlock

### join(String mathText) {#join-java.lang.String-}
```
public IMathBlock join(String mathText)
```

ينضم نص رياضي إلى هذه الكتلة الرياضية

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathBlock block = element.join("+y");
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| mathText | java.lang.String | نص رياضي للانضمام إليه |

**القيمة المرجعة:**
[IMathBlock](../../com.aspose.slides/imathblock) - IMathBlock جديد يحتوي على هذه النسخة والوسيط المحدد

### joinBlock(IMathBlock other) {#joinBlock-com.aspose.slides.IMathBlock-}
```
public final IMathBlock joinBlock(IMathBlock other)
```

ينضم كتلة رياضية أخرى إلى هذه

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
| المعامل | النوع | الوصف |
| --- | --- | --- |
| other | [IMathBlock](../../com.aspose.slides/imathblock) | الكتلة المنضمة |

**القيمة المرجعة:**
[IMathBlock](../../com.aspose.slides/imathblock) - هذه الكتلة الرياضية بعد الانضمام

### delimit(char separatorCharacter) {#delimit-char-}
```
public final IMathDelimiter delimit(char separatorCharacter)
```

يفصل عناصر فرعية بحرف فاصل (بدون الأقواس)

--------------------

> ```
> مثال:
>  
>  MathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.delimit('|');
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| separatorCharacter | char | حرف الفاصل |

**القيمة المرجعة:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - عنصر رياضي من النوع [IMathDelimiter](../../com.aspose.slides/imathdelimiter)

### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

يحيط العناصر الفرعية لهذه الكتلة بأحرف محددة مثل الأقواس أو أحرف أخرى كإطار

--------------------

> ```
> مثال:
>  
>  IMathBlock block = new MathematicalText("x").join("+y");
>  IMathDelimiter delimiter = block.enclose('[', ']');
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| beginningCharacter | char | الحرف الافتتاحي (عادة قوس أيسر) |
| endingCharacter | char | الحرف الختامي (عادة قوس أيمن) |

**القيمة المرجعة:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - عنصر رياضي من النوع [IMathDelimiter](../../com.aspose.slides/imathdelimiter) الذي يتضمن الأحرف المحددة كإطار

### enclose(char beginningCharacter, char endingCharacter, char separatorCharacter) {#enclose-char-char-char-}
```
public final IMathDelimiter enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)
```

يحيط العناصر الفرعية لهذه الكتلة بأحرف محددة مثل الأقواس أو أحرف أخرى كإطار ويفصلهم بحرف فاصل

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.enclose('{', '}', '%');
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| beginningCharacter | char | الحرف الافتتاحي (عادة قوس أيسر) |
| endingCharacter | char | الحرف الختامي (عادة قوس أيمن) |
| separatorCharacter | char | حرف الفاصل |

**القيمة المرجعة:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - عنصر رياضي من النوع [IMathDelimiter](../../com.aspose.slides/imathdelimiter) الذي يتضمن الأحرف المحددة كإطار وفاصل

### toMathArray() {#toMathArray--}
```
public IMathArray toMathArray()
```

يوضع العناصر الفرعية في مصفوفة رأسية

--------------------

> ```
> Example:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```

**القيمة المرجعة:**
[IMathArray](../../com.aspose.slides/imatharray) - نسخة جديدة من النوع [IMathArray](../../com.aspose.slides/imatharray)

### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public final void writeAsMathMl(OutputStream stream)
```

يحفظ محتوى هذا [MathBlock](../../com.aspose.slides/mathblock) كـ MathML

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.OutputStream | دفق الهدف |