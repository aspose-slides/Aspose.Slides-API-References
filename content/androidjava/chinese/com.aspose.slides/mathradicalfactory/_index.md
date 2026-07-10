---
title: MathRadicalFactory
second_title: Aspose.Slides for Android 的 Java API 参考
description: 允许创建数学根式
type: docs
url: /zh/com.aspose.slides/mathradicalfactory/
---
**继承:**
java.lang.Object

**所有实现的接口:**
[com.aspose.slides.IMathRadicalFactory](../../com.aspose.slides/imathradicalfactory)
```
public class MathRadicalFactory implements IMathRadicalFactory
```

允许创建数学根式

--------------------

用于 COM 兼容性
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MathRadicalFactory()](#MathRadicalFactory--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [createMathRadical(IMathElement baseArgument, IMathElement degreeArgument)](#createMathRadical-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | 创建数学根式 |
### MathRadicalFactory() {#MathRadicalFactory--}
```
public MathRadicalFactory()
```


### createMathRadical(IMathElement baseArgument, IMathElement degreeArgument) {#createMathRadical-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathRadical createMathRadical(IMathElement baseArgument, IMathElement degreeArgument)
```


创建数学根式

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | 用于应用根式的基参数 |
| degreeArgument | [IMathElement](../../com.aspose.slides/imathelement) | 指数值 |

**返回值:**
[IMathRadical](../../com.aspose.slides/imathradical) - 新的根式元素