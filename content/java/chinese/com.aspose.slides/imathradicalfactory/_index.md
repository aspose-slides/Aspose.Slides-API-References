---
title: IMathRadicalFactory
second_title: Aspose.Slides for Java API Reference
description: Allows to create math radical
type: docs
url: /zh/com.aspose.slides/imathradicalfactory/
---```
public interface IMathRadicalFactory
```

允许创建数学根式

--------------------

用于 COM 兼容性
## 方法

| 方法 | 描述 |
| --- | --- |
| [createMathRadical(IMathElement baseArgument, IMathElement degreeArgument)](#createMathRadical-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | 创建数学根式 |
### createMathRadical(IMMathElement baseArgument, IMMathElement degreeArgument) {#createMathRadical-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathRadical createMathRadical(IMathElement baseArgument, IMathElement degreeArgument)
```


创建数学根式

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | 用于应用根式的基参数 |
| degreeArgument | [IMathElement](../../com.aspose.slides/imathelement) | 度数值 |

**返回值：**
[IMathRadical](../../com.aspose.slides/imathradical) - 新的根式元素