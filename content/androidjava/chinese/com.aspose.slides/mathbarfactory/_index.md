---
title: MathBarFactory
second_title: 适用于 Android 的 Aspose.Slides via Java API 参考
description: 允许创建数学栏
type: docs
url: /zh/com.aspose.slides/mathbarfactory/
---
**继承：**
java.lang.Object

**所有实现的接口：**
[com.aspose.slides.IMathBarFactory](../../com.aspose.slides/imathbarfactory)
```
public class MathBarFactory implements IMathBarFactory
```

允许创建数学栏

--------------------

用于 COM 兼容性
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MathBarFactory()](#MathBarFactory--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [createMathBar(IMathElement element)](#createMathBar-com.aspose.slides.IMathElement-) | 创建数学栏，应用于该元素 |
| [createMathBar(IMathElement element, int position)](#createMathBar-com.aspose.slides.IMathElement-int-) | 创建数学栏，应用于该元素 |
### MathBarFactory() {#MathBarFactory--}
```
public MathBarFactory()
```

### createMathBar(IMathElement element) {#createMathBar-com.aspose.slides.IMathElement-}
```
public final IMathBar createMathBar(IMathElement element)
```

创建数学栏，应用于该元素

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 用于应用栏的数学元素 |

**返回值：**
[IMathBar](../../com.aspose.slides/imathbar) - 新的数学栏元素
### createMathBar(IMathElement element, int position) {#createMathBar-com.aspose.slides.IMathElement-int-}
```
public final IMathBar createMathBar(IMathElement element, int position)
```

创建数学栏，应用于该元素

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 用于应用栏的数学元素 |
| position | int | 栏的位置 |

**返回值：**
[IMathBar](../../com.aspose.slides/imathbar) - 新的数学栏元素