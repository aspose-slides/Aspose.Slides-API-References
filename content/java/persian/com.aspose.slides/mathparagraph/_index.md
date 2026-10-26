---
title: MathParagraph
second_title: مرجع API Aspose.Slides برای جاوا
description: پاراگراف ریاضی که یک مخزن برای بلوک‌های ریاضی IMathBlock است
type: docs
url: /fa/com.aspose.slides/mathparagraph/
---
**ارث‌بری:**  
java.lang.Object

**تمام رابط‌های پیاده‌سازی شده:**  
[com.aspose.slides.IMathParagraph](../../com.aspose.slides/imathparagraph), com.aspose.slides.IDOMObject  
```
public class MathParagraph implements IMathParagraph, IDOMObject
```

پاراگراف ریاضی که یک مخزن برای بلوک‌های ریاضی (IMathBlock) است

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [MathParagraph()](#MathParagraph--) | یک نمونه جدید از کلاس MathParagraph را مقداردهی اولیه می‌کند. |
| [MathParagraph(IMathBlock mathBlock)](#MathParagraph-com.aspose.slides.IMathBlock-) | یک نمونه جدید از کلاس MathParagraph را مقداردهی اولیه می‌کند. |
## متدها

| متد | توضیح |
| --- | --- |
| [getJustification()](#getJustification--) | تعدیل پاراگراف مقدار پیش‌فرض: CenteredAsGroup |
| [setJustification(int value)](#setJustification-int-) | تعدیل پاراگراف مقدار پیش‌فرض: CenteredAsGroup |
| [getParent_Immediate()](#getParent-Immediate--) | شی Parent_Immediate را برمی‌گرداند. |
| [getCount()](#getCount--) | تعداد عناصری که در واقع در مجموعه موجود است را دریافت می‌کند. |
| [get_Item(int index)](#get-Item-int-) | مورد مورد نظر در شاخص مشخص شده را دریافت می‌کند. |
| [set_Item(int index, IMathBlock value)](#set-Item-int-com.aspose.slides.IMathBlock-) | مورد مورد نظر در شاخص مشخص شده را دریافت می‌کند. |
| [clear()](#clear--) | تمام عناصر را از مجموعه حذف می‌کند. |
| [add(IMathBlock mathBlock)](#add-com.aspose.slides.IMathBlock-) | IMathBlock را به انتهای مجموعه اضافه می‌کند. |
| [remove(IMathBlock mathBlock)](#remove-com.aspose.slides.IMathBlock-) | اولین رخداد یک شیء خاص را از مجموعه حذف می‌کند. |
| [contains(IMathBlock mathBlock)](#contains-com.aspose.slides.IMathBlock-) | تعیین می‌کند آیا مجموعه شامل مقدار خاصی است یا نه. |
| [indexOf(IMathBlock mathBlock)](#indexOf-com.aspose.slides.IMathBlock-) | شاخص یک IMathBlock خاص در مجموعه را تعیین می‌کند. |
| [insert(int index, IMathBlock mathBlock)](#insert-int-com.aspose.slides.IMathBlock-) | IMathBlock را در شاخص مشخص شده به مجموعه وارد می‌کند. |
| [removeAt(int index)](#removeAt-int-) | یک مورد را در شاخص مشخص شده از مجموعه حذف می‌کند. |
| [iterator()](#iterator--) |  |
| [iteratorJava()](#iteratorJava--) |  |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | محتویات این [MathParagraph](../../com.aspose.slides/mathparagraph) را به عنوان MathML ذخیره می‌کند |
| [toLatex()](#toLatex--) | معادله ریاضی را در فرمت LaTeX دریافت می‌کند |
### MathParagraph() {#MathParagraph--}
```
public MathParagraph()
```

یک نمونه جدید از کلاس MathParagraph را مقداردهی اولیه می‌کند.

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

یک نمونه جدید از کلاس MathParagraph را مقداردهی اولیه می‌کند.

--------------------

> ```
> Example:
>  
>  MathParagraph mathParagraph = new MathParagraph(new MathBlock());
> ```

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) |  |

### getJustification() {#getJustification--}
```
public final int getJustification()
```

تعدیل پاراگراف مقدار پیش‌فرض: CenteredAsGroup

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```

**باز می‌گرداند:**  
int
### setJustification(int value) {#setJustification-int-}
```
public final void setJustification(int value)
```

تعدیل پاراگراف مقدار پیش‌فرض: CenteredAsGroup

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

شی Parent_Immediate را برمی‌گرداند. فقط خواندنی IDOMObject.

**باز می‌گرداند:**  
com.aspose.slides.IDOMObject
### getCount() {#getCount--}
```
public final int getCount()
```

تعداد عناصری که در واقع در مجموعه موجود است را دریافت می‌کند. فقط خواندنی int.

--------------------

> ```
> Example:
>  
>  MathParagraph mathParagraph = new MathParagraph();
>  int blocksCount = mathParagraph.getCount();
> ```

**باز می‌گرداند:**  
int
### get_Item(int index) {#get-Item-int-}
```
public final IMathBlock get_Item(int index)
```

مورد مورد نظر در شاخص مشخص شده را دریافت می‌کند. فقط خواندنی [IMathBlock](../../com.aspose.slides/imathblock).

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

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | شاخص صفر مبنی موردی که باید دریافت شود |
**باز می‌گرداند:**  
[IMathBlock](../../com.aspose.slides/imathblock) - بلوک متن ریاضی.

### set_Item(int index, IMathBlock value) {#set-Item-int-com.aspose.slides.IMathBlock-}
```
public final void set_Item(int index, IMathBlock value)
```

مورد مورد نظر در شاخص مشخص شده را دریافت می‌کند. فقط خواندنی [IMathBlock](../../com.aspose.slides/imathblock).

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

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | شاخص صفر مبنی موردی که باید دریافت شود |
| value | [IMathBlock](../../com.aspose.slides/imathblock) | بلوک متن ریاضی. |

### clear() {#clear--}
```
public final void clear()
```

تمام عناصر را از مجموعه حذف می‌کند.

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

IMathBlock را به انتهای مجموعه اضافه می‌کند.

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathBlock(new MathematicalText("x")));
> ```

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | یک بلوک ریاضی که به انتهای مجموعه اضافه می‌شود |

### remove(IMathBlock mathBlock) {#remove-com.aspose.slides.IMathBlock-}
```
public final boolean remove(IMathBlock mathBlock)
```

اولین رخداد یک شیء خاص را از مجموعه حذف می‌کند.

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

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | شیئی که باید از مجموعه حذف شود. |
**باز می‌گرداند:**  
boolean - اگر mathBlock با موفقیت از مجموعه حذف شود true؛ در غیر این صورت false. این متد همچنین false برمی‌گرداند اگر mathBlock در مجموعه اصلی یافت نشود.
### contains(IMathBlock mathBlock) {#contains-com.aspose.slides.IMathBlock-}
```
public final boolean contains(IMathBlock mathBlock)
```

تعیین می‌کند آیا مجموعه شامل مقدار خاصی است یا نه.

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

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | شیئی که باید در مجموعه پیدا شود. |
**باز می‌گرداند:**  
boolean - اگر mathBlock در مجموعه یافت شود true؛ در غیر این صورت false.
### indexOf(IMathBlock mathBlock) {#indexOf-com.aspose.slides.IMathBlock-}
```
public final int indexOf(IMathBlock mathBlock)
```

شاخص یک IMathBlock خاص در مجموعه را تعیین می‌کند.

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

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | موردی که باید در مجموعه پیدا شود. |
**باز می‌گرداند:**  
int - شاخص mathBlock اگر در مجموعه یافت شود؛ در غیر این صورت -1.
### insert(int index, IMathBlock mathBlock) {#insert-int-com.aspose.slides.IMathBlock-}
```
public final void insert(int index, IMathBlock mathBlock)
```

IMathBlock را در شاخص مشخص شده به مجموعه وارد می‌کند.

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  mathParagraph.insert(0, block);
> ```

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | شاخص صفر مبنی که باید یک مورد در آن وارد شود. |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | IMathBlock برای وارد کردن. |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

یک مورد را در شاخص مشخص شده از مجموعه حذف می‌کند.

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

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | شاخص صفر مبنی موردی که باید حذف شود. |
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMathBlock> iterator()
```

**باز می‌گرداند:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMathBlock>
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.IEnumerator iteratorJava()
```

**باز می‌گرداند:**  
com.aspose.ms.System.Collections.IEnumerator
### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public final void writeAsMathMl(OutputStream stream)
```

محتویات این [MathParagraph](../../com.aspose.slides/mathparagraph) را به عنوان MathML ذخیره می‌کند

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | java.io.OutputStream | جریان هدف |
### toLatex() {#toLatex--}
```
public final String toLatex()
```

معادله ریاضی را در فرمت LaTeX دریافت می‌کند

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathematicalText("a").join("+").join(new MathematicalText("b").join("=").join(new MathematicalText("c"))));
>  String mathLatex = mathParagraph.toLatex();
> ```

**باز می‌گرداند:**  
java.lang.String