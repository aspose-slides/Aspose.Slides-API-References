---
title: MathBlock
second_title: Aspose.Slides for Java API 参考
description: 指定一个位于 MathParagraph 中并且独占一行的数学文本实例。
type: docs
url: /zh/com.aspose.slides/mathblock/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**All Implemented Interfaces:**
[com.aspose.slides.IMathBlock](../../com.aspose.slides/imathblock), com.aspose.slides.IDOMObject
```
public final class MathBlock extends MathElementBase implements IMathBlock, IDOMObject
```

指定一个位于 MathParagraph 中并且独占一行的数学文本实例。所有数学区域，包括方程式、表达式、方程或表达式的数组以及公式，都由 math block 表示。

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock();
> ```

## Constructors

| 构造函数 | 描述 |
| --- | --- |
| [MathBlock()](#MathBlock--) | 初始化 MathBlock 类的新实例。 |
| [MathBlock(IMathElement mathElement)](#MathBlock-com.aspose.slides.IMathElement-) | 创建一个新的数学块并将指定的元素放入其中。 |
| [MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements)](#MathBlock-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--) | 创建一个新的数学块并将指定的元素放入其中。 |
## Methods

| 方法 | 描述 |
| --- | --- |
| [getCount()](#getCount--) | 获取集合中实际包含的子数学元素的数量。 |
| [get_Item(int index)](#get-Item-int-) | 获取或设置指定索引处的 IMathElement。 |
| [set_Item(int index, IMathElement value)](#set-Item-int-com.aspose.slides.IMathElement-) | 获取或设置指定索引处的 IMathElement。 |
| [isReadOnly()](#isReadOnly--) | 返回 false，因为子元素集合可以被修改。 |
| [getChildren()](#getChildren--) | 获取子元素 |
| [getParent_Immediate()](#getParent-Immediate--) | 返回 Parent_Immediate 对象。 |
| [add(IMathElement item)](#add-com.aspose.slides.IMathElement-) | 向集合末尾添加一个数学元素。 |
| [clear()](#clear--) | 删除集合中的所有元素。 |
| [contains(IMathElement item)](#contains-com.aspose.slides.IMathElement-) | 确定集合是否包含特定值。 |
| [copyTo(IMathElement[] array, int arrayIndex)](#copyTo-com.aspose.slides.IMathElement---int-) | 复制到指定数组。 |
| [remove(IMathElement item)](#remove-com.aspose.slides.IMathElement-) | 从集合中移除第一次出现的特定对象。 |
| [iterator()](#iterator--) | 返回遍历集合的枚举器。 |
| [iteratorJava()](#iteratorJava--) | 返回整个集合的 java 迭代器。 |
| [indexOf(IMathElement item)](#indexOf-com.aspose.slides.IMathElement-) | 确定集合中特定数学元素的索引。 |
| [insert(int index, IMathElement item)](#insert-int-com.aspose.slides.IMathElement-) | 在指定索引处向集合插入一个 MathElement。 |
| [removeAt(int index)](#removeAt-int-) | 删除集合中指定索引处的元素。 |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | 将一个数学元素与此数学块连接。 |
| [join(String mathText)](#join-java.lang.String-) | 将数学文本与此数学块连接。 |
| [joinBlock(IMathBlock other)](#joinBlock-com.aspose.slides.IMathBlock-) | 将另一个数学块与此块连接。 |
| [delimit(char separatorCharacter)](#delimit-char-) | 使用分隔符字符（不含括号）分隔子元素。 |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | 使用指定字符（如括号或其他字符）将此块的子元素括起来。 |
| [enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)](#enclose-char-char-char-) | 使用指定字符（如括号或其他）将此块的子元素括起来，并使用分隔字符进行分隔。 |
| [toMathArray()](#toMathArray--) | 将子元素放入竖直数组。 |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | 将此 [MathBlock](../../com.aspose.slides/mathblock) 的内容保存为 MathML。 |

### MathBlock() {#MathBlock--}
```
public MathBlock()
```

初始化 MathBlock 类的新实例。

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

创建一个新的数学块并将指定的元素放入其中。

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | 要放入块中的数学元素 |

### MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements) {#MathBlock-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--}
```
public MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements)
```

创建一个新的数学块并将指定的元素放入其中。

--------------------

> ```
> Example:
>  
>  var elems = new IMathElement[2] { new MathematicalText("item1"), new MathematicalText("item2") };
>  MathBlock mathBlock = new MathBlock(elems);
> ```


**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mathElements | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.IMathElement> | 要放入块中的数学元素 |

### getCount() {#getCount--}
```
public final int getCount()
```

获取集合中实际包含的子数学元素的数量。只读 int。

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  int count = mathBlock.getCount();
> ```

**返回：**
int
### get_Item(int index) {#get-Item-int-}
```
public final IMathElement get_Item(int index)
```

获取或设置指定索引处的 IMathElement。

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  IMathElement firstElem = mathBlock.get_Item(0);
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 项目的零基索引 |

**返回：**
[IMathElement](../../com.aspose.slides/imathelement) - 数学元素。

### set_Item(int index, IMathElement value) {#set-Item-int-com.aspose.slides.IMathElement-}
```
public final void set_Item(int index, IMathElement value)
```

获取或设置指定索引处的 IMathElement。

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  IMathElement firstElem = mathBlock.get_Item(0);
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 项目的零基索引 |
| value | [IMathElement](../../com.aspose.slides/imathelement) | 数学元素。 |

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

返回 false，因为子元素集合可以被修改。

**返回：**
boolean

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

获取子元素

**返回：**
com.aspose.slides.IMathElement[]

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

返回 Parent_Immediate 对象。只读 IDOMObject。

**返回：**
com.aspose.slides.IDOMObject

### add(IMathElement item) {#add-com.aspose.slides.IMathElement-}
```
public final void add(IMathElement item)
```

向集合末尾添加一个数学元素。

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  mathBlock.add(new MathematicalText("+"));
>  mathBlock.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | 要添加到集合末尾的 IMathElement。 |

### clear() {#clear--}
```
public final void clear()
```

删除集合中的所有元素。

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

确定集合是否包含特定值。

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

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | 要在集合中定位的对象。 |

**返回：**
boolean - 如果在集合中找到该项则为 true；否则为 false。

### copyTo(IMathElement[] array, int arrayIndex) {#copyTo-com.aspose.slides.IMathElement---int-}
```
public final void copyTo(IMathElement[] array, int arrayIndex)
```

复制到指定数组。

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


**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| array | [IMathElement[]](../../com.aspose.slides/imathelement) | 要复制到的数组。 |
| arrayIndex | int | 开始复制的索引。 |

### remove(IMathElement item) {#remove-com.aspose.slides.IMathElement-}
```
public final boolean remove(IMathElement item)
```

从集合中移除第一次出现的特定对象。

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

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | 要从集合中移除的对象。 |

**返回：**
boolean - 如果成功移除该项则为 true；否则为 false。如果在原集合中未找到该项，也返回 false。

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMathElement> iterator()
```

返回遍历集合的枚举器。

**返回：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMathElement> - 可用于遍历集合的 IGenericEnumerator。

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.IEnumerator iteratorJava()
```

返回整个集合的 java 迭代器。

**返回：**
com.aspose.ms.System.Collections.IEnumerator - 整个集合的 java.util.Iterator。

### indexOf(IMathElement item) {#indexOf-com.aspose.slides.IMathElement-}
```
public final int indexOf(IMathElement item)
```

确定集合中特定数学元素的索引。

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


**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | 要在集合中定位的元素。 |

**返回：**
int - 如果在集合中找到该项，则返回其索引；否则返回 -1。

### insert(int index, IMathElement item) {#insert-int-com.aspose.slides.IMathElement-}
```
public final void insert(int index, IMathElement item)
```

在指定索引处向集合插入一个 MathElement。

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入 MathElement 的零基索引。 |
| item | [IMathElement](../../com.aspose.slides/imathelement) | 要插入的 MathElement。 |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

删除集合中指定索引处的元素。

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

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要删除的元素的零基索引。 |

### join(IMathElement mathElement) {#join-com.aspose.slides.IMathElement-}
```
public IMathBlock join(IMathElement mathElement)
```

将一个数学元素与此数学块连接。

--------------------

> ```
> Example:
>  
>  IMathElement element1 = new MathematicalText("x");
>  IMathElement element2 = new MathematicalText("y");
>  IMathBlock block = element1.join(element2);
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | 要连接的元素。 |

**返回：**
[IMathBlock](../../com.aspose.slides/imathblock) - 当前 IMathBlock 实例

### join(String mathText) {#join-java.lang.String-}
```
public IMathBlock join(String mathText)
```

将数学文本与此数学块连接。

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathBlock block = element.join("+y");
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mathText | java.lang.String | 要连接的数学文本。 |

**返回：**
[IMathBlock](../../com.aspose.slides/imathblock) - 包含此实例和指定参数的新 IMathBlock

### joinBlock(IMathBlock other) {#joinBlock-com.aspose.slides.IMathBlock-}
```
public final IMathBlock joinBlock(IMathBlock other)
```

将另一个数学块与此块连接。

--------------------

> ```
> Example:
>  
>  IMathBlock block1 = new MathSuperscriptElement(new MathematicalText("c"), new MathematicalText("2")).join(new MathematicalText("="));
>  IMathBlock block2 = new MathSuperscriptElement(new MathematicalText("a"), new MathematicalText("2")).join(new MathematicalText("+"))
>  .join(new MathSuperscriptElement(new MathematicalText("b"), new MathematicalText("2")));
>  IMathBlock block3 = block1.joinBlock(block2);
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| other | [IMathBlock](../../com.aspose.slides/imathblock) | 要连接的块。 |

**返回：**
[IMathBlock](../../com.aspose.slides/imathblock) - 连接后的此数学块

### delimit(char separatorCharacter) {#delimit-char-}
```
public final IMathDelimiter delimit(char separatorCharacter)
```

使用分隔符字符（不含括号）分隔子元素。

--------------------

> ```
> 示例:
>  
>  MathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.delimit('|');
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| separatorCharacter | char | 分隔符字符。 |

**返回：**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - 类型为 [IMathDelimiter](../../com.aspose.slides/imathdelimiter) 的数学元素

### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

使用指定字符（如括号或其他字符）将此块的子元素括起来。

--------------------

> ```
> 示例:
>  
>  IMathBlock block = new MathematicalText("x").join("+y");
>  IMathDelimiter delimiter = block.enclose('[', ']');
> ```


**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| beginningCharacter | char | 起始字符（通常为左括号）。 |
| endingCharacter | char | 结束字符（通常为右括号）。 |

**返回：**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - 包含指定字符作为框架的类型为 [IMathDelimiter](../../com.aspose.slides/imathdelimiter) 的数学元素

### enclose(char beginningCharacter, char endingCharacter, char separatorCharacter) {#enclose-char-char-char-}
```
public final IMathDelimiter enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)
```

使用指定字符（如括号或其他）将此块的子元素括起来，并使用分隔字符进行分隔。

--------------------

> ```
> 示例:
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.enclose('{', '}', '%');
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| beginningCharacter | char | 起始字符（通常为左括号）。 |
| endingCharacter | char | 结束字符（通常为右括号）。 |
| separatorCharacter | char | 分隔符字符。 |

**返回：**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - 包含指定字符作为框架并作为分隔符的类型为 [IMathDelimiter](../../com.aspose.slides/imathdelimiter) 的数学元素

### toMathArray() {#toMathArray--}
```
public IMathArray toMathArray()
```

将子元素放入竖直数组。

--------------------

> ```
> 示例:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```

**返回：**
[IMathArray](../../com.aspose.slides/imatharray) - 类型为 [IMathArray](../../com.aspose.slides/imatharray) 的新实例

### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public final void writeAsMathMl(OutputStream stream)
```

将此 [MathBlock](../../com.aspose.slides/mathblock) 的内容保存为 MathML

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream | 目标流 |
