---
title: IMathRadicalFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create math radical
type: docs
url: /zh/com.aspose.slides/imathradicalfactory/
---```
public interface IMathRadicalFactory
```

允许创建数学根号

--------------------

用于 COM 兼容性
## 方法

| 方法 | 描述 |
| --- | --- |
| [createMathRadical(IMathElement baseArgument, IMathElement degreeArgument)](#createMathRadical-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | 创建数学根号 |
### createMathRadical(IMathElement baseArgument, IMathElement degreeArgument) {#createMathRadical-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathRadical createMathRadical(IMathElement baseArgument, IMathElement degreeArgument)
```

创建数学根号

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | 要应用根号的基数参数 |
| degreeArgument | [IMathElement](../../com.aspose.slides/imathelement) | 指数值 |

**返回：**
[IMathRadical](../../com.aspose.slides/imathradical) - 新的根号元素