---
title: MathBoxFactory
second_title: Aspose.Slides for Android via Java API 参考
description: 允许创建数学盒子
type: docs
url: /zh/com.aspose.slides/mathboxfactory/
---

**继承：**
java.lang.Object

**所有实现的接口：**
[com.aspose.slides.IMathBoxFactory](../../com.aspose.slides/imathboxfactory)
```
public class MathBoxFactory implements IMathBoxFactory
```

允许创建数学盒子

--------------------

用于 COM 兼容性
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MathBoxFactory()](#MathBoxFactory--) |  |

## 方法

| 方法 | 描述 |
| --- | --- |
| [createMathBox(IMathElement element)](#createMathBox-com.aspose.slides.IMathElement-) | 通过应用到元素来创建数学盒子 |

### MathBoxFactory() {#MathBoxFactory--}
```
public MathBoxFactory()
```

### createMathBox(IMathElement element) {#createMathBox-com.aspose.slides.IMathElement-}
```
public final IMathBox createMathBox(IMathElement element)
```

通过将盒子应用于元素来创建数学盒子

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 用于应用盒子的数学元素 |

**返回值：**
[IMathBox](../../com.aspose.slides/imathbox) - 新的盒子元素