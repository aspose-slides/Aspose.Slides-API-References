---
title: MathParagraph
second_title: Aspose.Sildes for PHP 通过 Java API 参考
description: 
type: docs

url: /zh/aspose.slides/mathparagraph/
---
## MathParagraph 类

数学段落，作为数学块 (IMathBlock) 的容器

### MathParagraph {#MathParagraph}

| 名称 | 描述 |
| --- | --- |
| MathParagraph() | 初始化 MathParagraph 类的新实例。 |

**返回：**
MathParagraph


---


### MathParagraph {#MathParagraph}

| 名称 | 描述 |
| --- | --- |
| MathParagraph([MathBlock](../mathblock)) | 初始化 MathParagraph 类的新实例。 |

**返回：**
MathParagraph


---


### add {#add}

| 名称 | 描述 |
| --- | --- |
| add ([MathBlock](../mathblock)) | 将 IMMathBlock 添加到集合的末尾。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| mathBlock | [MathBlock](../mathblock) | 将要添加到集合末尾的数学块。 |

**返回：**
void


---


### clear {#clear}

| 名称 | 描述 |
| --- | --- |
| clear () | 从集合中移除所有元素。 |

**返回：**
void


---


### contains {#contains}

| 名称 | 描述 |
| --- | --- |
| contains ([MathBlock](../mathblock)) | 确定集合是否包含特定值。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| mathBlock | [MathBlock](../mathblock) | 要在集合中定位的对象。 |

**返回：**
boolean


---


### getCount {#getCount}

| 名称 | 描述 |
| --- | --- |
| getCount () | 获取集合实际包含的元素数量。只读 int。 |

**返回：**
int


---


### getJustification {#getJustification}

| 名称 | 描述 |
| --- | --- |
| getJustification () | 段落对齐方式 默认值：CenteredAsGroup |

**返回：**
int


---


### get_Item {#get_Item}

| 名称 | 描述 |
| --- | --- |
| get_Item (int) | 获取指定索引处的项。只读 IMathBlock。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要获取的项的零基索引 |

**返回：**
[MathBlock](../mathblock)


---


### indexOf {#indexOf}

| 名称 | 描述 |
| --- | --- |
| indexOf ([MathBlock](../mathblock)) | 确定集合中特定 IMathBlock 的索引。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| mathBlock | [MathBlock](../mathblock) | 要在集合中定位的项。 |

**返回：**
int


---


### insert {#insert}

| 名称 | 描述 |
| --- | --- |
| insert (int, [MathBlock](../mathblock)) | 在指定索引处将 IMathBlock 插入到集合中。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入项的零基索引。 |
| mathBlock | [MathBlock](../mathblock) | 要插入的 IMathBlock。 |

**返回：**
void


---


### iterator {#iterator}

| 名称 | 描述 |
| --- | --- |
| iterator () |  |

**返回：**



---


### iteratorJava {#iteratorJava}

| 名称 | 描述 |
| --- | --- |
| iteratorJava () |  |

**返回：**



---


### remove {#remove}

| 名称 | 描述 |
| --- | --- |
| remove ([MathBlock](../mathblock)) | 从集合中移除特定对象的第一次出现。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| mathBlock | [MathBlock](../mathblock) | 要从集合中移除的对象。 |

**返回：**
boolean


---


### removeAt {#removeAt}

| 名称 | 描述 |
| --- | --- |
| removeAt (int) | 从集合中移除指定索引处的项。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要移除的项的零基索引。 |

**返回：**
void


---


### setJustification {#setJustification}

| 名称 | 描述 |
| --- | --- |
| setJustification (int) | 段落对齐方式 默认值：CenteredAsGroup |

**返回：**
void


---


### set_Item {#set_Item}

| 名称 | 描述 |
| --- | --- |
| set_Item (int, [MathBlock](../mathblock)) | 获取指定索引处的项。只读 IMathBlock。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 数学文本块。 |
| index | [MathBlock](../mathblock) | 要获取的项的零基索引 |

**返回：**
void


---


### toLatex {#toLatex}

| 名称 | 描述 |
| --- | --- |
| toLatex () | 获取 LaTeX 格式的数学公式 |

**返回：**
String


---


### writeAsMathMl {#writeAsMathMl}

| 名称 | 描述 |
| --- | --- |
| writeAsMathMl (OutputStream) | 将此 MathParagraph 的内容保存为 MathML |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| stream | OutputStream | 目标流 |

**返回：**
void


---