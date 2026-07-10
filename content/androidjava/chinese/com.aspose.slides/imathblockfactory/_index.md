---
title: IMathBlockFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create a math block
type: docs
url: /zh/com.aspose.slides/imathblockfactory/
---```
public interface IMathBlockFactory
```

允许创建数学块

--------------------

用于 COM 兼容性
## 方法

| 方法 | 描述 |
| --- | --- |
| [createMathBlock()](#createMathBlock--) | 创建数学块 |
| [createMathBlock(IMathElement mathElement)](#createMathBlock-com.aspose.slides.IMathElement-) | 创建数学块并将元素放入其中 |
| [createMathBlock(IMathElementCollection mathElements)](#createMathBlock-com.aspose.slides.IMathElementCollection-) | 创建数学块并将元素放入其中 |
### createMathBlock() {#createMathBlock--}
```
public abstract IMathBlock createMathBlock()
```

创建数学块

**返回:**  
[IMathBlock](../../com.aspose.slides/imathblock) - 新的数学块

### createMathBlock(IMathElement mathElement) {#createMathBlock-com.aspose.slides.IMathElement-}
```
public abstract IMathBlock createMathBlock(IMathElement mathElement)
```

创建数学块并将元素放入其中

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | 数学元素 |

**返回:**  
[IMathBlock](../../com.aspose.slides/imathblock) - 新的数学块

### createMathBlock(IMathElementCollection mathElements) {#createMathBlock-com.aspose.slides.IMathElementCollection-}
```
public abstract IMathBlock createMathBlock(IMathElementCollection mathElements)
```

创建数学块并将元素放入其中

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | 数学元素 |

**返回:**  
[IMathBlock](../../com.aspose.slides/imathblock) - 新的数学块