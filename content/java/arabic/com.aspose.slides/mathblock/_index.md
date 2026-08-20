---
title: MathBlock
second_title: مرجع API Aspose.Slides للغة Java
description: يحدد مثلاً للنص الرياضي المتضمن داخل MathParagraph ويبدأ على سطر خاص به.
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

يحدد مثلاً للنص الرياضي الموجود داخل MathParagraph ويبدأ على سطر جديد. جميع مناطق الرياضيات، بما في ذلك المعادلات، العبارات، مصفوفات المعادلات أو العبارات، والصيغ يُمثَّل بواسطة MathBlock.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock();
```
## المنشئات

| Constructor | Description |
| --- | --- |
| [MathBlock()](#MathBlock--) | إنشاء مثيل جديد من الفئة MathBlock. |
| [MathBlock(IMathElement mathElement)](#MathBlock-com.aspose.slides.IMathElement-) | إنشاء كتلة رياضية جديدة ووضع العنصر المحدد فيها |
| [MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements)](#MathBlock-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--) | إنشاء كتلة رياضية جديدة ووضع العناصر المحددة فيها |
## الطرق

| Method | Description |
| --- | --- |
| [getCount()](#getCount--) | يُعيد عدد عناصر الرياضيات الفرعية الموجودة فعليًا في المجموعة. |
| [get_Item(int index)](#get-Item-int-) | يحصل أو يعيّن IMathElement في الفهرس المحدد. |
| [set_Item(int index, IMathElement value)](#set-Item-int-com.aspose.slides.IMathElement-) | يحصل أو يعيّن IMathElement في الفهرس المحدد. |
| [isReadOnly()](#isReadOnly--) | يرجع false لأن مجموعة العناصر الفرعية يمكن تعديلها. |
| [getChildren()](#getChildren--) | الحصول على عناصر الأطفال |
| [getParent_Immediate()](#getParent-Immediate--) | يرجع كائن Parent\_Immediate. |
| [add(IMathElement item)](#add-com.aspose.slides.IMathElement-) | يضيف عنصرًا رياضيًا إلى نهاية المجموعة. |
| [clear()](#clear--) | يزيل جميع العناصر من المجموعة. |
| [contains(IMathElement item)](#contains-com.aspose.slides.IMathElement-) | يحدد ما إذا كانت المجموعة تحتوي على قيمة محددة. |
| [copyTo(IMathElement[] array, int arrayIndex)](#copyTo-com.aspose.slides.IMathElement---int-) | Copy to specified array. |
| [remove(IMathElement item)](#remove-com.aspose.slides.IMathElement-) | يزيل أول حدوث لكائن معين من المجموعة. |
| [iterator()](#iterator--) | يرجع عدادًا يتجول عبر المجموعة. |
| [iteratorJava()](#iteratorJava--) | يرجع مكرّر java للمجموعة بالكامل. |
| [indexOf(IMathElement item)](#indexOf-com.aspose.slides.IMathElement-) | يحدد فهرس عنصر رياضي معين في المجموعة. |
| [insert(int index, IMathElement item)](#insert-int-com.aspose.slides.IMathElement-) | يدخل MathElement في المجموعة عند الفهرس المحدد. |
| [removeAt(int index)](#removeAt-int-) | يزيل العنصر عند الفهرس المحدد في المجموعة. |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | ينضم عنصر رياضي إلى هذا الكتلة الرياضية |
| [join(String mathText)](#join-java.lang.String-) | ينضم نص رياضي إلى هذه الكتلة الرياضية |
| [joinBlock(IMathBlock other)](#joinBlock-com.aspose.slides.IMathBlock-) | ينضم كتلة رياضية أخرى إلى هذه |
| [delimit(char separatorCharacter)](#delimit-char-) | يفصل العناصر الفرعية باستخدام حرف الفاصل (بدون الأقواس) |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | يضمّن العناصر الفرعية لهذا الكتلة في أحرف محددة مثل الأقواس أو أحرف أخرى كإطار |
| [enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)](#enclose-char-char-char-) | يضمّن العناصر الفرعية لهذا الكتلة في أحرف محددة مثل الأقواس أو أخرى كإطار ويفصل بحرف الفاصل |
| [toMathArray()](#toMathArray--) | يضع العناصر الفرعية في مصفوفة عمودية |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | يحفظ محتوى هذا [MathBlock](../../com.aspose.slides/mathblock) كـ MathML |
### MathBlock() {#MathBlock--}
```
public MathBlock()
```

إنشاء مثيل جديد من الفئة MathBlock.

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

إنشاء كتلة رياضية جديدة ووضع العنصر المحدد فيها

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
> ```

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | العنصر الرياضي لوضعه في الكتلة |

### MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements) {#MathBlock-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--}
```
public MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements)
```

إنشاء كتلة رياضية جديدة ووضع العناصر المحددة فيها

--------------------

> ```
> Example:
>  
>  var elems = new IMathElement[2] { new MathematicalText("item1"), new MathematicalText("item2") };
>  MathBlock mathBlock = new MathBlock(elems);
> ```

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| mathElements | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.IMathElement> | العناصر الرياضية لوضعها في الكتلة |

### getCount() {#getCount--}
```
public final int getCount()
```

يُعيد عدد عناصر الرياضيات الفرعية الموجودة فعليًا في المجموعة. int للقراءة فقط.

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

يحصل أو يعيّن IMathElement في الفهرس المحدد.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  IMathElement firstElem = mathBlock.get_Item(0);
> ```

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | الفهرس الصفري للعنصر |
**القيمة المرجعة:**
[IMathElement](../../com.aspose.slides/imathelement) - العنصر الرياضي.
### set_Item(int index, IMathElement value) {#set-Item-int-com.aspose.slides.IMathElement-}
```
public final void set_Item(int index, IMathElement value)
```

يحصل أو يعيّن IMathElement في الفهرس المحدد.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  IMathElement firstElem = mathBlock.get_Item(0);
> ```

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | الفهرس الصفري للعنصر |
| value | [IMathElement](../../com.aspose.slides/imathelement) | العنصر الرياضي. |
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

يرجع false لأن مجموعة العناصر الفرعية يمكن تعديلها.

**القيمة المرجعة:**
boolean
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

الحصول على عناصر الأطفال

**القيمة المرجعة:**
com.aspose.slides.IMathElement[]
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

يرجع كائن Parent\_Immediate. IDOMObject للقراءة فقط.

**القيمة المرجعة:**
com.aspose.slides.IDOMObject
### add(IMathElement item) {#add-com.aspose.slides.IMathElement-}
```
public final void add(IMathElement item)
```

يضيف عنصرًا رياضيًا إلى نهاية المجموعة.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  mathBlock.add(new MathematicalText("+"));
>  mathBlock.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | العنصر IMathElement الذي سيُضاف إلى نهاية المجموعة. |
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
| Parameter | Type | Description |
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
| Parameter | Type | Description |
| --- | --- | --- |
| array | [IMathElement\[\]](../../com.aspose.slides/imathelement) | المصفوفة للنسخ إليها. |
| arrayIndex | int | الفهرس لبدء النسخ. |
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
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | الكائن لإزالته من المجموعة. |
**القيمة المرجعة:**
boolean - true إذا تم إزالة العنصر بنجاح من المجموعة؛ وإلا false. هذه الطريقة تُعيد false أيضًا إذا لم يُعثر على العنصر في المجموعة الأصلية.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMathElement> iterator()
```

يرجع عدادًا يتجول عبر المجموعة.

**القيمة المرجعة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMathElement> - مُعدد IGenericEnumerator يمكن استخدامه للتجول عبر المجموعة.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.IEnumerator iteratorJava()
```

يرجع مكرّر java للمجموعة بأكملها.

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
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | العنصر لتحديد موقعه في المجموعة. |
**القيمة المرجعة:**
int - فهرس العنصر إذا وجد في المجموعة؛ وإلا -1.
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
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | الفهرس الصفري لإدخال MathElement عنده. |
| item | [IMathElement](../../com.aspose.slides/imathelement) | MathElement المراد إدخاله. |
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
| Parameter | Type | Description |
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
| Parameter | Type | Description |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | العنصر الذي سيُضم. |
**القيمة المرجعة:**
[IMathBlock](../../com.aspose.slides/imathblock) - المثيل الحالي لـ IMMathBlock
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
| Parameter | Type | Description |
| --- | --- | --- |
| mathText | java.lang.String | النص الرياضي الذي سيُضم. |
**القيمة المرجعة:**
[IMathBlock](../../com.aspose.slides/imathblock) - IMathBlock جديد يحتوي على هذا المثيل والوسيط المحدد
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
| Parameter | Type | Description |
| --- | --- | --- |
| other | [IMathBlock](../../com.aspose.slides/imathblock) | كتلة الانضمام |
**القيمة المرجعة:**
[IMathBlock](../../com.aspose.slides/imathblock) - هذه الكتلة الرياضية بعد الانضمام
### delimit(char separatorCharacter) {#delimit-char-}
```
public final IMathDelimiter delimit(char separatorCharacter)
```

يفصل العناصر الفرعية بحرف الفاصل (بدون الأقواس)

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.delimit('|');
> ```

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| separatorCharacter | char | حرف الفاصل |
**القيمة المرجعة:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - عنصر الرياضيات من النوع [IMathDelimiter](../../com.aspose.slides/imathdelimiter)
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

يضمّن العناصر الفرعية لهذا الكتلة في أحرف محددة مثل الأقواس أو أحرف أخرى كإطار

--------------------

> ```
> Example:
>  
>  IMathBlock block = new MathematicalText("x").join("+y");
>  IMathDelimiter delimiter = block.enclose('[', ']');
> ```

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| beginningCharacter | char | حرف البداية (عادةً القوس الأيسر) |
| endingCharacter | char | حرف النهاية (عادةً القوس الأيمن) |
**القيمة المرجعة:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - عنصر الرياضيات من النوع [IMathDelimiter](../../com.aspose.slides/imathdelimiter) الذي يتضمن الأحرف المحددة كإطار
### enclose(char beginningCharacter, char endingCharacter, char separatorCharacter) {#enclose-char-char-char-}
```
public final IMathDelimiter enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)
```

يضمّن العناصر الفرعية لهذا الكتلة في أحرف محددة مثل الأقواس أو أخرى كإطار ويفصل بحرف الفاصل

--------------------

> ```
> مثال:
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.enclose('{', '}', '%');
> ```

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| beginningCharacter | char | حرف البداية (عادةً القوس الأيسر) |
| endingCharacter | char | حرف النهاية (عادةً القوس الأيمن) |
| separatorCharacter | char | حرف الفاصل |
**القيمة المرجعة:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - عنصر الرياضيات من النوع [IMathDelimiter](../../com.aspose.slides/imathdelimiter) الذي يتضمن الأحرف المحددة كإطار وفاصل
### toMathArray() {#toMathArray--}
```
public IMathArray toMathArray()
```

يضع العناصر الفرعية في مصفوفة عمودية

--------------------

> ```
> Example:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```

**القيمة المرجعة:**
[IMathArray](../../com.aspose.slides/imatharray) - مثال جديد من النوع [IMathArray](../../com.aspose.slides/imatharray)
### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public final void writeAsMathMl(OutputStream stream)
```

يحفظ محتوى هذا [MathBlock](../../com.aspose.slides/mathblock) كـ MathML

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | دفق الهدف |