---
title: IMathArrayFactory
second_title: Aspose.Slides for Android via Java API Reference
description: 允许创建数学数组
type: docs
url: /zh/com.aspose.slides/imatharrayfactory/
---```
public interface IMathArrayFactory
```

允许创建数学数组

--------------------

用于 COM 兼容性
## 方法

| 方法 | 说明 |
| --- | --- |
| [createMathArray(IMathElement element)](#createMathArray-com.aspose.slides.IMathElement-) | 创建一个数学数组并将指定的元素放入其中 |
| [createMathArray(IMathElementCollection elements)](#createMathArray-com.aspose.slides.IMathElementCollection-) | 创建一个数学数组并将指定的元素放入其中 |

### createMathArray(IMathElement element) {#createMathArray-com.aspose.slides.IMathElement-}
```
public abstract IMathArray createMathArray(IMathElement element)
```

创建一个数学数组并将指定的元素放入其中

**参数:**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 要放入数组的数学元素 |

**返回值:**
[IMathArray](../../com.aspose.slides/imatharray) - 新的数学数组

### createMathArray(IMathElementCollection elements) {#createMathArray-com.aspose.slides.IMathElementCollection-}
```
public abstract IMathArray createMathArray(IMathElementCollection elements)
```

创建一个数学数组并将指定的元素放入其中

**参数:**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| elements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | 要放入数组的数学元素 |

**返回值:**
[IMathArray](../../com.aspose.slides/imatharray) - 新的数学数组