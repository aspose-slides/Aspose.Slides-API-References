---
title: MathParagraph
second_title: مرجع API جاوا برای Aspose.Slides در اندروید
description: پاراگراف ریاضی که یک محفظه برای بلوک‌های ریاضی IMathBlock است
type: docs
url: /fa/com.aspose.slides/mathparagraph/
---
**ارث‌بری:**  
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.IMathParagraph](../../com.aspose.slides/imathparagraph), com.aspose.slides.IDOMObject  
```
public class MathParagraph implements IMathParagraph, IDOMObject
```

پاراگراف ریاضی که یک محفظه برای بلوک‌های ریاضی (IMathBlock) است

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
| [getJustification()](#getJustification--) | توجیه پاراگراف مقدار پیش‌فرض: CenteredAsGroup |
| [setJustification(int value)](#setJustification-int-) | توجیه پاراگراف مقدار پیش‌فرض: CenteredAsGroup |
| [getParent_Immediate()](#getParent-Immediate--) | شیء Parent_Immediate را بازمی‌گرداند. |
| [getCount()](#getCount--) | تعداد عناصری که واقعاً در مجموعه موجود هستند را برمی‌گرداند. |
| [get_Item(int index)](#get-Item-int-) | مورد در شاخص مشخص‌شده را برمی‌گرداند. |
| [set_Item(int index, IMathBlock value)](#set-Item-int-com.aspose.slides.IMathBlock-) | مورد در شاخص مشخص‌شده را برمی‌گرداند. |
| [clear()](#clear--) | تمام عناصری را که در مجموعه وجود دارند حذف می‌کند. |
| [add(IMathBlock mathBlock)](#add-com.aspose.slides.IMathBlock-) | IMathBlock را به انتهای مجموعه اضافه می‌کند. |
| [remove(IMathBlock mathBlock)](#remove-com.aspose.slides.IMathBlock-) | اولین رخداد یک شیء خاص را از مجموعه حذف می‌کند. |
| [contains(IMathBlock mathBlock)](#contains-com.aspose.slides.IMathBlock-) | تعیین می‌کند که آیا مجموعه شامل مقدار خاصی است یا نه. |
| [indexOf(IMathBlock mathBlock)](#indexOf-com.aspose.slides.IMathBlock-) | اندیس یک IMathBlock خاص را در مجموعه تعیین می‌کند. |
| [insert(int index, IMathBlock mathBlock)](#insert-int-com.aspose.slides.IMathBlock-) | IMathBlock را در شاخص مشخص‌شده به مجموعه وارد می‌کند. |
| [removeAt(int index)](#removeAt-int-) | موردی را در شاخص مشخص‌شده از مجموعه حذف می‌کند. |
| [iterator()](#iterator--) |  |
| [iteratorJava()](#iteratorJava--) |  |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | محتوای این [MathParagraph](../../com.aspose.slides/mathparagraph) را به صورت MathML ذخیره می‌کند |
| [toLatex()](#toLatex--) | معادله ریاضی را در قالب LaTeX دریافت می‌کند |
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

توجیه پاراگراف مقدار پیش‌فرض: CenteredAsGroup

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```

**بازگرداندن:**
int
### setJustification(int value) {#setJustification-int-}
```
public final void setJustification(int value)
```

توجیه پاراگراف مقدار پیش‌فرض: CenteredAsGroup

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

شیء Parent_Immediate را بازمی‌گرداند. فقط-خواندنی IDOMObject.

**بازگرداندن:**
com.aspose.slides.IDOMObject
### getCount() {#getCount--}
```
public final int getCount()
```

تعداد عناصری که واقعاً در مجموعه موجود هستند را برمی‌گرداند. فقط-خواندنی int.

--------------------

> ```
> Example:
>  
>  MathParagraph mathParagraph = new MathParagraph();
>  int blocksCount = mathParagraph.getCount();
> ```

**بازگرداندن:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IMathBlock get_Item(int index)
```

مورد در شاخص مشخص‌شده را برمی‌گرداند. فقط-خواندنی [IMathBlock](../../com.aspose.slides/imathblock).

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
| index | int | شاخص صفر-مبنای مورد برای دریافت |

**بازگرداندن:**
[IMathBlock](../../com.aspose.slides/imathblock) - بلوک متن ریاضی.
### set_Item(int index, IMathBlock value) {#set-Item-int-com.aspose.slides.IMathBlock-}
```
public final void set_Item(int index, IMathBlock value)
```

مورد در شاخص مشخص‌شده را برمی‌گرداند. فقط-خواندنی [IMathBlock](../../com.aspose.slides/imathblock).

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
| index | int | شاخص صفر-مبنای مورد برای دریافت |
| value | [IMathBlock](../../com.aspose.slides/imathblock) | بلوک متن ریاضی. |

### clear() {#clear--}
```
public final void clear()
```

تمام عناصری را که در مجموعه وجود دارند حذف می‌کند.

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
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | شیء‌ای که از مجموعه حذف می‌شود. |

**بازگرداندن:**
boolean - true اگر mathBlock با موفقیت از مجموعه حذف شد؛ در غیر این صورت false. این متد همچنین false برمی‌گرداند اگر mathBlock در مجموعه اصلی یافت نشود.
### contains(IMathBlock mathBlock) {#contains-com.aspose.slides.IMathBlock-}
```
public final boolean contains(IMathBlock mathBlock)
```

تعیین می‌کند که آیا مجموعه شامل مقدار خاصی است یا نه.

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
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | شیء‌ای که در مجموعه جستجو می‌شود. |

**بازگرداندن:**
boolean - true اگر mathBlock در مجموعه یافت شود؛ در غیر این صورت false.
### indexOf(IMathBlock mathBlock) {#indexOf-com.aspose.slides.IMathBlock-}
```
public final int indexOf(IMathBlock mathBlock)
```

اندیس یک IMathBlock خاص را در مجموعه تعیین می‌کند.

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
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | موردی که در مجموعه جستجو می‌شود. |

**بازگرداندن:**
int - اندیس mathBlock اگر در مجموعه یافت شود؛ در غیر این صورت -1.
### insert(int index, IMathBlock mathBlock) {#insert-int-com.aspose.slides.IMathBlock-}
```
public final void insert(int index, IMathBlock mathBlock)
```

IMathBlock را در شاخص مشخص‌شده به مجموعه وارد می‌کند.

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
| index | int | شاخص صفر-مبنای که مورد باید وارد شود. |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | IMathBlock برای وارد کردن. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

موردی را در شاخص مشخص‌شده از مجموعه حذف می‌کند.

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
| index | int | شاخص صفر-مبنای مورد برای حذف. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMathBlock> iterator()
```

**بازگرداندن:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMathBlock>
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.IEnumerator iteratorJava()
```

**بازگرداندن:**
com.aspose.ms.System.Collections.IEnumerator
### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public final void writeAsMathMl(OutputStream stream)
```

محتوای این [MathParagraph](../../com.aspose.slides/mathparagraph) را به صورت MathML ذخیره می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | java.io.OutputStream | جریان هدف |
### toLatex() {#toLatex--}
```
public final String toLatex()
```

معادله ریاضی را در قالب LaTeX دریافت می‌کند

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathematicalText("a").join("+").join(new MathematicalText("b").join("=").join(new MathematicalText("c"))));
>  String mathLatex = mathParagraph.toLatex();
> ```

**بازگرداندن:**
java.lang.String