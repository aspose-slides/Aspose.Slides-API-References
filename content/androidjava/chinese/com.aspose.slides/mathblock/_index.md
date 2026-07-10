---
title: MathBlock
second_title: Aspose.Slides Android 版 via Java API 参考
description: 指定一个位于 MathParagraph 中并在单独行上开始的数学文本实例。
type: docs
url: /zh/com.aspose.slides/mathblock/
---
**继承：**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**所有实现的接口：**
[com.aspose.slides.IMathBlock](../../com.aspose.slides/imathblock), com.aspose.slides.IDOMObject
```
public final class MathBlock extends MathElementBase implements IMathBlock, IDOMObject
```

指定一个位于 MathParagraph 中并在单独行上开始的数学文本实例。所有数学区域，包括等式、表达式、等式或表达式数组以及公式，都由 math block 表示。

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock();
> ```
## Constructors

| Constructor | Description |
| --- | --- |
| [MathBlock()](#MathBlock--) | Initializes a new instance of the MathBlock class. |
| [MathBlock(IMathElement mathElement)](#MathBlock-com.aspose.slides.IMathElement-) | Creates a new mathematical block and puts specified element in it |
| [MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements)](#MathBlock-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--) | Creates a new mathematical block and puts specified elements in it |
## Methods

| Method | Description |
| --- | --- |
| [getCount()](#getCount--) | Gets the number of child math elements actually contained in the collection. |
| [get_Item(int index)](#get-Item-int-) | Gets or sets IMathElement at the specified index. |
| [set_Item(int index, IMathElement value)](#set-Item-int-com.aspose.slides.IMathElement-) | Gets or sets IMathElement at the specified index. |
| [isReadOnly()](#isReadOnly--) | Returns false because child elements collection can be modified. |
| [getChildren()](#getChildren--) | Get children elements |
| [getParent_Immediate()](#getParent-Immediate--) | Returns Parent\_Immediate object. |
| [add(IMathElement item)](#add-com.aspose.slides.IMathElement-) | Adds a math element to the end of the collection. |
| [clear()](#clear--) | Removes all elements from the collection. |
| [contains(IMathElement item)](#contains-com.aspose.slides.IMathElement-) | Determines whether the collection contains a specific value. |
| [copyTo(IMathElement[] array, int arrayIndex)](#copyTo-com.aspose.slides.IMathElement---int-) | Copy to specified array. |
| [remove(IMathElement item)](#remove-com.aspose.slides.IMathElement-) | Removes the first occurrence of a specific object from the collection. |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [iteratorJava()](#iteratorJava--) | Returns a java iterator for the entire collection. |
| [indexOf(IMathElement item)](#indexOf-com.aspose.slides.IMathElement-) | Determines the index of a specific math element in collection. |
| [insert(int index, IMathElement item)](#insert-int-com.aspose.slides.IMathElement-) | Inserts a MathElement into the collection at the specified index. |
| [removeAt(int index)](#removeAt-int-) | Removes the element at the specified index of the collection. |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | Joins a mathematical element with this mathematical block |
| [join(String mathText)](#join-java.lang.String-) | Joins a mathematical text with this mathematical block |
| [joinBlock(IMathBlock other)](#joinBlock-com.aspose.slides.IMathBlock-) | Joins another mathematical block with this one |
| [delimit(char separatorCharacter)](#delimit-char-) | Delimits child elements with separator character (without the brackets) |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Encloses child elements of this block in specified characters such as parenthesis or another characters as framing |
| [enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)](#enclose-char-char-char-) | Encloses child elements of this block in specified characters such as parenthesis or another as framing and delimit with a separator character |
| [toMathArray()](#toMathArray--) | Puts child elements in a vertical array |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | Saves content of this [MathBlock](../../com.aspose.slides/mathblock) as MathML |
### MathBlock() {#MathBlock--}
```
public MathBlock()
```

Initializes a new instance of the MathBlock class.

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

创建一个新的数学块并将指定元素放入其中

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | The mathematical element to put in the block |

### MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements) {#MathBlock-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--}
```
public MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements)
```

Creates a new mathematical block and puts specified elements in it

--------------------

> ```
> Example:
>  
>  var elems = new IMathElement[2] { new MathematicalText("item1"), new MathematicalText("item2") };
>  MathBlock mathBlock = new MathBlock(elems);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mathElements | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.IMathElement> | Mathematical elements to put in the block |

### getCount() {#getCount--}
```
public final int getCount()
```

Gets the number of child math elements actually contained in the collection. Read-only int.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  int count = mathBlock.getCount();
> ```

**Returns:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IMathElement get_Item(int index)
```

获取或设置在指定索引处的 IMathElement。

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  IMathElement firstElem = mathBlock.get_Item(0);
> ```

**参数：**
| Parameter | Type | Description |
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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 项目的零基索引 |
| value | [IMathElement](../../com.aspose.slides/imathelement) | 数学元素。 |

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```
Returns false because child elements collection can be modified.

**Returns:**
boolean
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

获取子元素

**Returns:**
com.aspose.slides.IMathElement[]
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

返回 Parent_Immediate 对象。只读 IDOMObject。

**Returns:**
com.aspose.slides.IDOMObject
### add(IMathElement item) {#add-com.aspose.slides.IMathElement-}
```
public final void add(IMathElement item)
```


Adds a math element to the end of the collection.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  mathBlock.add(new MathematicalText("+"));
>  mathBlock.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | The IMathElement to be added to the end of the collection. |

### clear() {#clear--}
```
public final void clear()
```

从集合中移除所有元素。

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

确定集合是否包含特定的值。

--------------------

> ```
> 示例：
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.Add(plusElement);
>  mathBlock.Add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  boolean contains = mathBlock.Contains(plusElement);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | The object to locate in the collection. |

**Returns:**
boolean - true if item is found in the collection; otherwise, false.
### copyTo(IMathElement[] array, int arrayIndex) {#copyTo-com.aspose.slides.IMathElement---int-}
```
public final void copyTo(IMathElement[] array, int arrayIndex)
```

Copy to specified array.

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | [IMathElement\[\]](../../com.aspose.slides/imathelement) | Array to copy to. |
| arrayIndex | int | Index to begin copying. |

### remove(IMathElement item) {#remove-com.aspose.slides.IMathElement-}
```
public final boolean remove(IMathElement item)
```


Removes the first occurrence of a specific object from the collection.

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | The object to remove from the collection. |

**Returns:**
boolean - true if item was successfully removed from the collection; otherwise, false. This method also returns false if item is not found in the original collection.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMathElement> iterator()
```

返回一个遍历集合的枚举器。

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMathElement> - 一个可用于遍历集合的 IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.IEnumerator iteratorJava()
```

返回整个集合的 java 迭代器。

**Returns:**
com.aspose.ms.System.Collections.IEnumerator - 整个集合的 java.util.Iterator。
### indexOf(IMathElement item) {#indexOf-com.aspose.slides.IMathElement-}
```
public final int indexOf(IMathElement item)
```
确定集合中特定数学元素的索引。

--------------------

> ```
> 示例：
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.add(new MathRadial(new MathematicalText("x"), new MathematicalText("3")));
>  int index = mathBlock.indexOf(plusElement);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | The element to locate in the collection. |

**Returns:**
int - The index of item if found in the collection; otherwise, -1.
### insert(int index, IMathElement item) {#insert-int-com.aspose.slides.IMathElement-}
```
public final void insert(int index, IMathElement item)
```

插入一个 MathElement 到集合中指定的索引位置。

--------------------

> ```
> 示例：
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 要插入 MathElement 的零基索引。 |
| item | [IMathElement](../../com.aspose.slides/imathelement) | 要插入的 MathElement。 |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

从集合中删除指定索引处的元素。

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 要删除的元素的零基索引。 |

### join(IMathElement mathElement) {#join-com.aspose.slides.IMathElement-}
```
public IMathBlock join(IMathElement mathElement)
```


Joins a mathematical element with this mathematical block

--------------------

> ```
> Example:
>  
>  IMathElement element1 = new MathematicalText("x");
>  IMathElement element2 = new MathematicalText("y");
>  IMathBlock block = element1.join(element2);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | The element to be joined |

**Returns:**
[IMathBlock](../../com.aspose.slides/imathblock) - The current instance of IMathBlock
### join(String mathText) {#join-java.lang.String-}
```
public IMathBlock join(String mathText)
```
将数学文本与此数学块连接

--------------------

> ```
> 示例：
>  
>  IMathElement element = new MathematicalText("x");
>  IMathBlock block = element.join("+y");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mathText | java.lang.String | Mathematical text to be joined |

**Returns:**
[IMathBlock](../../com.aspose.slides/imathblock) - A new IMathBlock containing this instance and specified argument
```
public final IMathBlock joinBlock(IMathBlock other)
```
Joins another mathematical block with this one

--------------------

> ```
> Example:
>  
>  IMathBlock block1 = new MathSuperscriptElement(new MathematicalText("c"), new MathematicalText("2")).join(new MathematicalText("="));
>  IMathBlock block2 = new MathSuperscriptElement(new MathematicalText("a"), new MathematicalText("2")).join(new MathematicalText("+"))
>  .join(new MathSuperscriptElement(new MathematicalText("b"), new MathematicalText("2")));
>  IMathBlock block3 = block1.joinBlock(block2);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [IMathBlock](../../com.aspose.slides/imathblock) | The joining block |

**Returns:**
[IMathBlock](../../com.aspose.slides/imathblock) - this mathematical block after joining
### delimit(char separatorCharacter) {#delimit-char-}
```
public final IMathDelimiter delimit(char separatorCharacter)
```
使用分隔符字符（不包括括号）对子元素进行分隔

--------------------

> ```
> 示例：
>  
>  MathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.delimit('|');
>  ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| separatorCharacter | char | 分隔符字符 |

**Returns:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - 类型为 [IMathDelimiter](../../com.aspose.slides/imathdelimiter) 的数学元素
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```


Encloses child elements of this block in specified characters such as parenthesis or another characters as framing

--------------------

> ```
> Example:
>  
>  IMathBlock block = new MathematicalText("x").join("+y");
>  IMathDelimiter delimiter = block.enclose('[', ']');
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| beginningCharacter | char | Beginning character (usually left bracket) |
| endingCharacter | char | Ending character (usually right bracket) |

**Returns:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - The math element of type [IMathDelimiter](../../com.aspose.slides/imathdelimiter) which includes specified characters as framing
### enclose(char beginningCharacter, char endingCharacter, char separatorCharacter) {#enclose-char-char-char-}
```
public final IMathDelimiter enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)
```


Encloses child elements of this block in specified characters such as parenthesis or another as framing and delimit with a separator character

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.enclose('{', '}', '%');
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| beginningCharacter | char | Beginning character (usually left bracket) |
| endingCharacter | char | Ending character (usually right bracket) |
| separatorCharacter | char | Separator character |

**Returns:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - The math element of type [IMathDelimiter](../../com.aspose.slides/imathdelimiter) which includes specified characters as framing and delimiter
### toMathArray() {#toMathArray--}
```
public IMathArray toMathArray()
```

将子元素放入垂直数组

--------------------

> ```
> 示例：
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
>  ```

**Returns:**
[IMathArray](../../com.aspose.slides/imatharray) - New instance of type [IMathArray](../../com.aspose.slides/imatharray)
### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public final void writeAsMathMl(OutputStream stream)

保存此 [MathBlock](../../com.aspose.slides/mathblock) 的内容为 MathML

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream | 目标流 |