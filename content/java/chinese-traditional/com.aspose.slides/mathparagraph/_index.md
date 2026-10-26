---
title: MathParagraph
second_title: Aspose.Slides for Java API 參考文件
description: 作為數學區塊 IMathBlock 容器的數學段落
type: docs
url: /zh-hant/com.aspose.slides/mathparagraph/
---
**繼承:**
java.lang.Object

**所有已實作的介面:**
[com.aspose.slides.IMathParagraph](../../com.aspose.slides/imathparagraph), com.aspose.slides.IDOMObject
```
public class MathParagraph implements IMathParagraph, IDOMObject
```

作為數學區塊 (IMathBlock) 容器的數學段落

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```
## 建構式

| 建構式 | 說明 |
| --- | --- |
| [MathParagraph()](#MathParagraph--) | 初始化 MathParagraph 類別的新執行個體。 |
| [MathParagraph(IMathBlock mathBlock)](#MathParagraph-com.aspose.slides.IMathBlock-) | 初始化 MathParagraph 類別的新執行個體。 |
## 方法

| 方法 | 說明 |
| --- | --- |
| [getJustification()](#getJustification--) | 段落對齊 預設值：CenteredAsGroup |
| [setJustification(int value)](#setJustification-int-) | 段落對齊 預設值：CenteredAsGroup |
| [getParent_Immediate()](#getParent-Immediate--) | 傳回 Parent_Immediate 物件。 |
| [getCount()](#getCount--) | 取得集合中實際包含的元素數量。 |
| [get_Item(int index)](#get-Item-int-) | 取得指定索引處的項目。 |
| [set_Item(int index, IMathBlock value)](#set-Item-int-com.aspose.slides.IMathBlock-) | 取得指定索引處的項目。 |
| [clear()](#clear--) | 從集合中移除所有元素。 |
| [add(IMathBlock mathBlock)](#add-com.aspose.slides.IMathBlock-) | 將 IMathBlock 新增至集合的末端。 |
| [remove(IMathBlock mathBlock)](#remove-com.aspose.slides.IMathBlock-) | 從集合中移除特定物件的第一個出現。 |
| [contains(IMathBlock mathBlock)](#contains-com.aspose.slides.IMathBlock-) | 判斷集合是否包含特定值。 |
| [indexOf(IMathBlock mathBlock)](#indexOf-com.aspose.slides.IMathBlock-) | 判斷特定 IMathBlock 在集合中的索引。 |
| [insert(int index, IMathBlock mathBlock)](#insert-int-com.aspose.slides.IMathBlock-) | 在指定索引處將 IMathBlock 插入至集合中。 |
| [removeAt(int index)](#removeAt-int-) | 移除集合中指定索引處的項目。 |
| [iterator()](#iterator--) |  |
| [iteratorJava()](#iteratorJava--) |  |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | 將此 [MathParagraph](../../com.aspose.slides/mathparagraph) 的內容儲存為 MathML |
| [toLatex()](#toLatex--) | 取得 LaTeX 格式的數學方程式 |
### MathParagraph() {#MathParagraph--}
```
public MathParagraph()
```

初始化 MathParagraph 類別的新執行個體。

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

初始化 MathParagraph 類別的新執行個體。

--------------------

> ```
> Example:
>  
>  MathParagraph mathParagraph = new MathParagraph(new MathBlock());
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) |  |

### getJustification() {#getJustification--}
```
public final int getJustification()
```

段落對齊 預設值：CenteredAsGroup

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```

**傳回值：**
int
### setJustification(int value) {#setJustification-int-}
```
public final void setJustification(int value)
```

段落對齊 預設值：CenteredAsGroup

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

傳回 Parent_Immediate 物件。唯讀 IDOMObject。

**傳回值：**
com.aspose.slides.IDOMObject
### getCount() {#getCount--}
```
public final int getCount()
```

取得集合中實際包含的元素數量。唯讀 int。

--------------------

> ```
> Example:
>  
>  MathParagraph mathParagraph = new MathParagraph();
>  int blocksCount = mathParagraph.getCount();
> ```

**傳回值：**
int
### get_Item(int index) {#get-Item-int-}
```
public final IMathBlock get_Item(int index)
```

取得指定索引處的項目。唯讀 [IMathBlock](../../com.aspose.slides/imathblock)。

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

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要取得的項目的零基索引 |

**傳回值：**
[IMathBlock](../../com.aspose.slides/imathblock) - 數學文字的區塊
### set_Item(int index, IMathBlock value) {#set-Item-int-com.aspose.slides.IMathBlock-}
```
public final void set_Item(int index, IMathBlock value)
```

取得指定索引處的項目。唯讀 [IMathBlock](../../com.aspose.slides/imathblock)。

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

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要取得的項目的零基索引 |
| value | [IMathBlock](../../com.aspose.slides/imathblock) | 數學文字的區塊 |

### clear() {#clear--}
```
public final void clear()
```

從集合中移除所有元素。

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

將 IMathBlock 新增至集合的末端。

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathBlock(new MathematicalText("x")));
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | 將被新增至集合末端的數學區塊 |

### remove(IMathBlock mathBlock) {#remove-com.aspose.slides.IMathBlock-}
```
public final boolean remove(IMathBlock mathBlock)
```

從集合中移除特定物件的第一個出現。

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

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | 要從集合中移除的物件。 |

**傳回值：**
boolean - 若成功從集合中移除 mathBlock 則為 true；否則為 false。如果在原始集合中找不到 mathBlock，此方法亦回傳 false。
### contains(IMathBlock mathBlock) {#contains-com.aspose.slides.IMathBlock-}
```
public final boolean contains(IMathBlock mathBlock)
```

判斷集合是否包含特定值。

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

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | 要在集合中定位的物件。 |

**傳回值：**
boolean - 若在集合中找到 mathBlock 則為 true；否則為 false。
### indexOf(IMathBlock mathBlock) {#indexOf-com.aspose.slides.IMathBlock-}
```
public final int indexOf(IMathBlock mathBlock)
```

判斷特定 IMathBlock 在集合中的索引。

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

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | 要在集合中定位的項目。 |

**傳回值：**
int - 若在集合中找到 mathBlock，則回傳其索引；否則回傳 -1。
### insert(int index, IMathBlock mathBlock) {#insert-int-com.aspose.slides.IMathBlock-}
```
public final void insert(int index, IMathBlock mathBlock)
```

在指定索引處將 IMathBlock 插入至集合中。

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  mathParagraph.insert(0, block);
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要插入項目的零基索引。 |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | 要插入的 IMathBlock。 |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

移除集合中指定索引處的項目。

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

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要移除項目的零基索引。 |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMathBlock> iterator()
```

**傳回值：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMathBlock>
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.IEnumerator iteratorJava()
```

**傳回值：**
com.aspose.ms.System.Collections.IEnumerator
### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public final void writeAsMathMl(OutputStream stream)
```

將此 [MathParagraph](../../com.aspose.slides/mathparagraph) 的內容儲存為 MathML

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| stream | java.io.OutputStream | 目標串流 |

### toLatex() {#toLatex--}
```
public final String toLatex()
```

取得 LaTeX 格式的數學方程式

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathematicalText("a").join("+").join(new MathematicalText("b").join("=").join(new MathematicalText("c"))));
>  String mathLatex = mathParagraph.toLatex();
> ```

**傳回值：**
java.lang.String