---
title: MathBlock
second_title: Aspose.Slides for Java API 參考
description: 指定一個包含在 MathParagraph 中、並自行在新行開始的數學文字實例。
type: docs
url: /zh-hant/com.aspose.slides/mathblock/
---
**繼承：**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**所有已實作的介面：**
[com.aspose.slides.IMathBlock](../../com.aspose.slides/imathblock), com.aspose.slides.IDOMObject
```
public final class MathBlock extends MathElementBase implements IMathBlock, IDOMObject
```

指定包含在 MathParagraph 中且自行開始於新行的數學文字實例。所有數學區域，包括方程式、運算式、方程式或運算式陣列，以及公式，均由 MathBlock 表示。

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock();
> ```

## 建構函式

| 建構函式 | 描述 |
| --- | --- |
| [MathBlock()](#MathBlock--) | 初始化 MathBlock 類別的新執行個體。 |
| [MathBlock(IMathElement mathElement)](#MathBlock-com.aspose.slides.IMathElement-) | 建立新的數學區塊並將指定的元素放入其中。 |
| [MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements)](#MathBlock-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--) | 建立新的數學區塊並將指定的元素放入其中。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getCount()](#getCount--) | 取得集合中實際包含的子數學元素的數量。 |
| [get_Item(int index)](#get-Item-int-) | 取得或設定指定索引處的 IMathElement。 |
| [set_Item(int index, IMathElement value)](#set-Item-int-com.aspose.slides.IMathElement-) | 取得或設定指定索引處的 IMathElement。 |
| [isReadOnly()](#isReadOnly--) | 傳回 false，因為子元素集合可以被修改。 |
| [getChildren()](#getChildren--) | 取得子元素 |
| [getParent_Immediate()](#getParent-Immediate--) | 傳回 Parent_Immediate 物件。 |
| [add(IMathElement item)](#add-com.aspose.slides.IMathElement-) | 將數學元素新增至集合的末端。 |
| [clear()](#clear--) | 從集合中移除所有元素。 |
| [contains(IMathElement item)](#contains-com.aspose.slides.IMathElement-) | 判斷集合是否包含特定值。 |
| [copyTo(IMathElement[] array, int arrayIndex)](#copyTo-com.aspose.slides.IMathElement---int-) | 複製至指定的陣列。 |
| [remove(IMathElement item)](#remove-com.aspose.slides.IMathElement-) | 從集合中移除第一次出現的特定物件。 |
| [iterator()](#iterator--) | 傳回可遍歷集合的列舉器。 |
| [iteratorJava()](#iteratorJava--) | 傳回整個集合的 java 迭代器。 |
| [indexOf(IMathElement item)](#indexOf-com.aspose.slides.IMathElement-) | 判斷特定數學元素在集合中的索引。 |
| [insert(int index, IMathElement item)](#insert-int-com.aspose.slides.IMathElement-) | 在指定索引處將 MathElement 插入集合。 |
| [removeAt(int index)](#removeAt-int-) | 移除集合中指定索引處的元素。 |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | 將數學元素加入此數學區塊 |
| [join(String mathText)](#join-java.lang.String-) | 將數學文字加入此數學區塊 |
| [joinBlock(IMathBlock other)](#joinBlock-com.aspose.slides.IMathBlock-) | 將另一個數學區塊與此區塊結合 |
| [delimit(char separatorCharacter)](#delimit-char-) | 以分隔字元界定子元素（不含括號） |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | 使用指定的字元（如括號或其他符號）將此區塊的子元素包圍起來 |
| [enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)](#enclose-char-char-char-) | 使用指定的字元（如括號或其他）將此區塊的子元素包圍，並以分隔字元界定 |
| [toMathArray()](#toMathArray--) | 將子元素排列成垂直陣列 |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | 將此 [MathBlock](../../com.aspose.slides/mathblock) 的內容儲存為 MathML |
### MathBlock() {#MathBlock--}
```
public MathBlock()
```

初始化 MathBlock 類別的新執行個體。

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

建立新的數學區塊並將指定的元素放入其中

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
> ```

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | 要放入區塊的數學元素 |

### MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements) {#MathBlock-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--}
```
public MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements)
```

建立新的數學區塊並將指定的元素放入其中

--------------------

> ```
> Example:
>  
>  var elems = new IMathElement[2] { new MathematicalText("item1"), new MathematicalText("item2") };
>  MathBlock mathBlock = new MathBlock(elems);
> ```

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| mathElements | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.IMathElement> | 要放入區塊的數學元素 |

### getCount() {#getCount--}
```
public final int getCount()
```

取得集合中實際包含的子數學元素的數量。只讀 int。

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  int count = mathBlock.getCount();
> ```

**傳回：**
int
### get_Item(int index) {#get-Item-int-}
```
public final IMathElement get_Item(int index)
```

取得或設定指定索引處的 IMathElement。

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  IMathElement firstElem = mathBlock.get_Item(0);
> ```

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | int | 項目的零基索引 |

**傳回：**
[IMathElement](../../com.aspose.slides/imathelement) - 數學元素。

### set_Item(int index, IMathElement value) {#set-Item-int-com.aspose.slides.IMathElement-}
```
public final void set_Item(int index, IMathElement value)
```

取得或設定指定索引處的 IMathElement。

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  IMathElement firstElem = mathBlock.get_Item(0);
> ```

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | int | 項目的零基索引 |
| value | [IMathElement](../../com.aspose.slides/imathelement) | 數學元素。 |

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

傳回 false，因為子元素集合可以被修改。

**傳回：**
boolean
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

取得子元素

**傳回：**
com.aspose.slides.IMathElement[]
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

傳回 Parent_Immediate 物件。只讀 IDOMObject。

**傳回：**
com.aspose.slides.IDOMObject
### add(IMathElement item) {#add-com.aspose.slides.IMathElement-}
```
public final void add(IMathElement item)
```

將數學元素新增至集合的末端。

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  mathBlock.add(new MathematicalText("+"));
>  mathBlock.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | 要新增至集合末端的 IMathElement。 |

### clear() {#clear--}
```
public final void clear()
```

移除集合中所有元素。

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

判斷集合是否包含特定值。

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

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | 要在集合中定位的物件。 |

**傳回：**
boolean - 若在集合中找到項目則為 true；否則為 false。

### copyTo(IMathElement[] array, int arrayIndex) {#copyTo-com.aspose.slides.IMathElement---int-}
```
public final void copyTo(IMathElement[] array, int arrayIndex)
```

複製至指定的陣列。

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

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| array | [IMathElement\[\]](../../com.aspose.slides/imathelement) | 要複製至的陣列。 |
| arrayIndex | int | 開始複製的索引。 |

### remove(IMathElement item) {#remove-com.aspose.slides.IMathElement-}
```
public final boolean remove(IMathElement item)
```

從集合中移除第一次出現的特定物件。

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

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | 要從集合中移除的物件。 |

**傳回：**
boolean - 若成功從集合中移除項目則為 true；否則為 false。若集合中未找到該項目也返回 false。

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMathElement> iterator()
```

傳回可遍歷集合的列舉器。

**傳回：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMathElement> - 可用於遍歷集合的 IGenericEnumerator。

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.IEnumerator iteratorJava()
```

傳回整個集合的 java 迭代器。

**傳回：**
com.aspose.ms.System.Collections.IEnumerator - 整個集合的 java.util.Iterator。

### indexOf(IMathElement item) {#indexOf-com.aspose.slides.IMathElement-}
```
public final int indexOf(IMathElement item)
```

判斷特定數學元素在集合中的索引。

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

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | 要在集合中定位的元素。 |

**傳回：**
int - 若在集合中找到項目則返回其索引；否則返回 -1。

### insert(int index, IMathElement item) {#insert-int-com.aspose.slides.IMathElement-}
```
public final void insert(int index, IMathElement item)
```

在指定索引處將 MathElement 插入集合。

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathblock.add(plusElement);
>  mathblock.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | int | 要插入 MathElement 的零基索引。 |
| item | [IMathElement](../../com.aspose.slides/imathelement) | 要插入的 MathElement。 |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

移除集合中指定索引處的元素。

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathblock.add(plusElement);
>  mathblock.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  mathblock.removeAt(2);
> ```

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | int | 要移除的元素之零基索引。 |

### join(IMathElement mathElement) {#join-com.aspose.slides.IMathElement-}
```
public IMathBlock join(IMathElement mathElement)
```

將數學元素加入此數學區塊

--------------------

> ```
> Example:
>  
>  IMathElement element1 = new MathematicalText("x");
>  IMathElement element2 = new MathematicalText("y");
>  IMathBlock block = element1.join(element2);
> ```

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | 要加入的元素 |

**傳回：**
[IMathBlock](../../com.aspose.slides/imathblock) - 當前 IMathBlock 實例

### join(String mathText) {#join-java.lang.String-}
```
public IMathBlock join(String mathText)
```

將數學文字加入此數學區塊

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathBlock block = element.join("+y");
> ```

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| mathText | java.lang.String | 要加入的數學文字 |

**傳回：**
[IMathBlock](../../com.aspose.slides/imathblock) - 包含此實例與指定參數的新 IMathBlock

### joinBlock(IMathBlock other) {#joinBlock-com.aspose.slides.IMathBlock-}
```
public final IMathBlock joinBlock(IMathBlock other)
```

將另一個數學區塊與此區塊結合

--------------------

> ```
> Example:
>  
>  IMathBlock block1 = new MathSuperscriptElement(new MathematicalText("c"), new MathematicalText("2")).join(new MathematicalText("="));
>  IMathBlock block2 = new MathSuperscriptElement(new MathematicalText("a"), new MathematicalText("2")).join(new MathematicalText("+"))
>  .join(new MathSuperscriptElement(new MathematicalText("b"), new MathematicalText("2")));
>  IMathBlock block3 = block1.joinBlock(block2);
> ```

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | |
| other | [IMathBlock](../../com.aspose.slides/imathblock) | 要結合的區塊 |

**傳回：**
[IMathBlock](../../com.aspose.slides/imathblock) - 結合後的此數學區塊

### delimit(char separatorCharacter) {#delimit-char-}
```
public final IMathDelimiter delimit(char separatorCharacter)
```

以分隔字元界定子元素（不含括號）

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.delimit('|');
> ```

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| separatorCharacter | char | 分隔字元 |

**傳回：**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - 類型為 [IMathDelimiter](../../com.aspose.slides/imathdelimiter) 的數學元素

### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

使用指定的字元（如括號或其他符號）將此區塊的子元素包圍起來

--------------------

> ```
> Example:
>  
>  IMathBlock block = new MathematicalText("x").join("+y");
>  IMathDelimiter delimiter = block.enclose('[', ']');
> ```

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | |
| beginningCharacter | char | 起始字元（通常為左括號） |
| endingCharacter | char | 結束字元（通常為右括號） |

**傳回：**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - 類型為 [IMathDelimiter](../../com.aspose.slides/imathdelimiter) 的數學元素，包含指定的包圍字元

### enclose(char beginningCharacter, char endingCharacter, char separatorCharacter) {#enclose-char-char-char-}
```
public final IMathDelimiter enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)
```

使用指定的字元（如括號或其他）將此區塊的子元素包圍，並以分隔字元界定

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.enclose('{', '}', '%');
> ```

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | |
| beginningCharacter | char | 起始字元（通常為左括號） |
| endingCharacter | char | 結束字元（通常為右括號） |
| separatorCharacter | char | 分隔字元 |

**傳回：**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - 類型為 [IMathDelimiter](../../com.aspose.slides/imathdelimiter) 的數學元素，包含指定的包圍字元與分隔符號

### toMathArray() {#toMathArray--}
```
public IMathArray toMathArray()
```

將子元素排列成垂直陣列

--------------------

> ```
> 範例：
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```

**傳回：**
[IMathArray](../../com.aspose.slides/imatharray) - 類型為 [IMathArray](../../com.aspose.slides/imatharray) 的新實例

### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public final void writeAsMathMl(OutputStream stream)
```

將此 [MathBlock](../../com.aspose.slides/mathblock) 的內容儲存為 MathML

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream | 目標串流 |