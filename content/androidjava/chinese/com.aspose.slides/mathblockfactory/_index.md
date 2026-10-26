---
title: MathBlockFactory
second_title: Aspose.Slides for Android via Java API 参考
description: 允许创建数学块
type: docs
url: /zh/com.aspose.slides/mathblockfactory/
---
**继承：**
java.lang.Object

**所有实现的接口：**
[com.aspose.slides.IMathBlockFactory](../../com.aspose.slides/imathblockfactory)
```
public class MathBlockFactory implements IMathBlockFactory
```

允许创建数学块

--------------------

用于 COM 兼容性
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MathBlockFactory()](#MathBlockFactory--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [createMathBlock()](#createMathBlock--) | 创建数学块 |
| [createMathBlock(IMathElement mathElement)](#createMathBlock-com.aspose.slides.IMathElement-) | 创建数学块并将元素放入其中 |
| [createMathBlock(IMathElementCollection mathElements)](#createMathBlock-com.aspose.slides.IMathElementCollection-) | 创建数学块并将元素放入其中 |
### MathBlockFactory() {#MathBlockFactory--}
```
public MathBlockFactory()
```


### createMathBlock() {#createMathBlock--}
```
public final IMathBlock createMathBlock()
```


创建数学块

**返回值：**
[IMathBlock](../../com.aspose.slides/imathblock) - 新的数学块
### createMathBlock(IMathElement mathElement) {#createMathBlock-com.aspose.slides.IMathElement-}
```
public final IMathBlock createMathBlock(IMathElement mathElement)
```


创建数学块并将元素放入其中

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | 数学元素 |

**返回值：**
[IMathBlock](../../com.aspose.slides/imathblock) - 新的数学块
### createMathBlock(IMathElementCollection mathElements) {#createMathBlock-com.aspose.slides.IMathElementCollection-}
```
public final IMathBlock createMathBlock(IMathElementCollection mathElements)
```


创建数学块并将元素放入其中

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | 数学元素 |

**返回值：**
[IMathBlock](../../com.aspose.slides/imathblock) - 新的数学块