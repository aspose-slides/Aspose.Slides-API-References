---
title: MathParagraph
second_title: مرجع API لأسبوز سلايدز للجاوا
description: فقرة رياضية هي حاوية للكتل الرياضية IMathBlock
type: docs
url: /ar/com.aspose.slides/mathparagraph/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المُنفذة:**
[com.aspose.slides.IMathParagraph](../../com.aspose.slides/imathparagraph), com.aspose.slides.IDOMObject
```
public class MathParagraph implements IMathParagraph, IDOMObject
```

فقرة رياضية هي حاوية للكتل الرياضية (IMathBlock)

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```
## المُنشئات

| المنشئ | الوصف |
| --- | --- |
| [MathParagraph()](#MathParagraph--) | ينشئ مثيلاً جديداً من الفئة MathParagraph. |
| [MathParagraph(IMathBlock mathBlock)](#MathParagraph-com.aspose.slides.IMathBlock-) | ينشئ مثيلاً جديداً من الفئة MathParagraph. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getJustification()](#getJustification--) | محاذاة الفقرة القيمة الافتراضية: CenteredAsGroup |
| [setJustification(int value)](#setJustification-int-) | محاذاة الفقرة القيمة الافتراضية: CenteredAsGroup |
| [getParent_Immediate()](#getParent-Immediate--) | يعيد كائن Parent_Immediate. |
| [getCount()](#getCount--) | يحصل على عدد العناصر الموجودة فعليًا في المجموعة. |
| [get_Item(int index)](#get-Item-int-) | يحصل على العنصر في الفهرس المحدد. |
| [set_Item(int index, IMathBlock value)](#set-Item-int-com.aspose.slides.IMathBlock-) | يحصل على العنصر في الفهرس المحدد. |
| [clear()](#clear--) | يزيل جميع العناصر من المجموعة. |
| [add(IMathBlock mathBlock)](#add-com.aspose.slides.IMathBlock-) | يضيف IMathBlock إلى نهاية المجموعة. |
| [remove(IMathBlock mathBlock)](#remove-com.aspose.slides.IMathBlock-) | يزيل أول حدوث لكائن محدد من المجموعة. |
| [contains(IMathBlock mathBlock)](#contains-com.aspose.slides.IMathBlock-) | يحدد ما إذا كانت المجموعة تحتوي على قيمة محددة. |
| [indexOf(IMathBlock mathBlock)](#indexOf-com.aspose.slides.IMathBlock-) | يحدد فهرس IMathBlock معين في المجموعة. |
| [insert(int index, IMathBlock mathBlock)](#insert-int-com.aspose.slides.IMathBlock-) | يدخل IMathBlock في المجموعة عند الفهرس المحدد. |
| [removeAt(int index)](#removeAt-int-) | يزيل عنصرًا عند الفهرس المحدد في المجموعة. |
| [iterator()](#iterator--) |  |
| [iteratorJava()](#iteratorJava--) |  |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | يحفظ محتوى هذا [MathParagraph](../../com.aspose.slides/mathparagraph) كـ MathML |
| [toLatex()](#toLatex--) | يحصل على المعادلة الرياضية بصيغة LaTeX |

### MathParagraph() {#MathParagraph--}
```
public MathParagraph()
```

ينشئ مثيلاً جديداً من الفئة MathParagraph.

--------------------

> ```
> Example:
>  
>  MathParagraph mathParagraph = new MathParagraph();
> ```

### MathParagraph(IMathBlock mathBlock) {#MathParagraph-com.aspose.slides.IMathBlock-}
```
public MathParagraph(IMathBlock mathBlock)
```

ينشئ مثيلاً جديداً من الفئة MathParagraph.

--------------------

> ```
> Example:
>  
>  MathParagraph mathParagraph = new MathParagraph(new MathBlock());
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) |  |

### getJustification() {#getJustification--}
```
public final int getJustification()
```

محاذاة الفقرة القيمة الافتراضية: CenteredAsGroup

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```

**الإرجاع:**
int
### setJustification(int value) {#setJustification-int-}
```
public final void setJustification(int value)
```

محاذاة الفقرة القيمة الافتراضية: CenteredAsGroup

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

يعيد كائن Parent_Immediate. قراءة فقط IDOMObject.

**القيمة المرجعة:**
com.aspose.slides.IDOMObject
### getCount() {#getCount--}
```
public final int getCount()
```

يحصل على عدد العناصر الموجودة فعليًا في المجموعة. قراءة فقط int.

--------------------

> ```
> Example:
>  
>  MathParagraph mathParagraph = new MathParagraph();
>  int blocksCount = mathParagraph.getCount();
> ```

**القيمة المرجعة:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IMathBlock get_Item(int index)
```

يحصل على العنصر في الفهرس المحدد. قراءة فقط [IMathBlock](../../com.aspose.slides/imathblock).

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathBlock(new MathematicalText("block1")));
>  mathParagraph.add(new MathBlock(new MathematicalText("block2")));
>  IMathBlock block = mathParagraph.get_Item(1);
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس القائم على الصفر للعنصر المراد جلبه |

**القيمة المرجعة:**
[IMathBlock](../../com.aspose.slides/imathblock) - كتلة نص رياضي.
### set_Item(int index, IMathBlock value) {#set-Item-int-com.aspose.slides.IMathBlock-}
```
public final void set_Item(int index, IMathBlock value)
```

يحصل على العنصر في الفهرس المحدد. قراءة فقط [IMathBlock](../../com.aspose.slides/imathblock).

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathBlock(new MathematicalText("block1")));
>  mathParagraph.add(new MathBlock(new MathematicalText("block2")));
>  IMathBlock block = mathParagraph.get_Item(1);
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس القائم على الصفر للعنصر المراد جلبه |
| value | [IMathBlock](../../com.aspose.slides/imathblock) | كتلة نص رياضي. |

### clear() {#clear--}
```
public final void clear()
```

يزيل جميع العناصر من المجموعة.

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathBlock(new MathematicalText("block1")));
>  mathParagraph.add(new MathBlock(new MathematicalText("block2")));
>  mathParagraph.clear();
> ```

### add(IMathBlock mathBlock) {#add-com.aspose.slides.IMathBlock-}
```
public final void add(IMathBlock mathBlock)
```

يضيف IMathBlock إلى نهاية المجموعة.

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathBlock(new MathematicalText("x")));
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | كتلة رياضية سيتم إضافتها إلى نهاية المجموعة |

### remove(IMathBlock mathBlock) {#remove-com.aspose.slides.IMathBlock-}
```
public final boolean remove(IMathBlock mathBlock)
```

يزيل أول حدوث لكائن محدد من المجموعة.

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathBlock(new MathematicalText("x")));
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  mathParagraph.add(block);
>  mathParagraph.remove(block);
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | الكائن المراد إزالته من المجموعة. |

**القيمة المرجعة:**
boolean - صحيح إذا تم إزالة mathBlock بنجاح من المجموعة؛ وإلا، خاطئ. تُعيد هذه الطريقة أيضًا خاطئ إذا لم يتم العثور على mathBlock في المجموعة الأصلية.
### contains(IMathBlock mathBlock) {#contains-com.aspose.slides.IMathBlock-}
```
public final boolean contains(IMathBlock mathBlock)
```

يحدد ما إذا كانت المجموعة تحتوي على قيمة محددة.

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  mathParagraph.add(block);
>  boolean contains = mathParagraph.contains(block);
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | الكائن المراد العثور عليه في المجموعة. |

**القيمة المرجعة:**
boolean - صحيح إذا تم العثور على mathBlock في المجموعة؛ وإلا، خاطئ.
### indexOf(IMathBlock mathBlock) {#indexOf-com.aspose.slides.IMathBlock-}
```
public final int indexOf(IMathBlock mathBlock)
```

يحدد فهرس IMathBlock معين في المجموعة.

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  mathParagraph.add(block);
>  int index = mathParagraph.indexOf(block);
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | العنصر المراد العثور عليه في المجموعة. |

**القيمة المرجعة:**
int - فهرس mathBlock إذا وجد في المجموعة؛ وإلا، -1.
### insert(int index, IMathBlock mathBlock) {#insert-int-com.aspose.slides.IMathBlock-}
```
public final void insert(int index, IMathBlock mathBlock)
```

يدخل IMathBlock في المجموعة عند الفهرس المحدد.

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  mathParagraph.insert(0, block);
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس القائم على الصفر الذي ينبغي إدراج العنصر عنده. |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | الـ IMathBlock المراد إدخاله. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

يزيل عنصرًا عند الفهرس المحدد في المجموعة.

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  mathParagraph.add(block);
>  mathParagraph.removeAt(0);
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس القائم على الصفر للعنصر المراد إزالته. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMathBlock> iterator()
```

**القيمة المرجعة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMathBlock>
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.IEnumerator iteratorJava()
```

**القيمة المرجعة:**
com.aspose.ms.System.Collections.IEnumerator
### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public final void writeAsMathMl(OutputStream stream)
```

يحفظ محتوى هذا [MathParagraph](../../com.aspose.slides/mathparagraph) كـ MathML

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.OutputStream | دفق الهدف |
### toLatex() {#toLatex--}
```
public final String toLatex()
```

يحصل على المعادلة الرياضية بصيغة LaTeX

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathematicalText("a").join("+").join(new MathematicalText("b").join("=").join(new MathematicalText("c"))));
>  String mathLatex = mathParagraph.toLatex();
> ```

**القيمة المرجعة:**
java.lang.String