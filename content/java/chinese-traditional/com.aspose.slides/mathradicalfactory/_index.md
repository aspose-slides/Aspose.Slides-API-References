---
title: MathRadicalFactory
second_title: Aspose.Slides for Java API 參考文件
description: 允許建立數學根式
type: docs
url: /zh-hant/com.aspose.slides/mathradicalfactory/
---
**繼承:**
java.lang.Object

**所有實作的介面:**
[com.aspose.slides.IMathRadicalFactory](../../com.aspose.slides/imathradicalfactory)
```
public class MathRadicalFactory implements IMathRadicalFactory
```

允許建立數學根式

--------------------

用於 COM 相容性
## 建構函式

| 建構函式 | 說明 |
| --- | --- |
| [MathRadicalFactory()](#MathRadicalFactory--) |  |
## 方法

| 方法 | 說明 |
| --- | --- |
| [createMathRadical(IMathElement baseArgument, IMathElement degreeArgument)](#createMathRadical-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | 建立數學根式 |
### MathRadicalFactory() {#MathRadicalFactory--}
```
public MathRadicalFactory()
```


### createMathRadical(IMathElement baseArgument, IMathElement degreeArgument) {#createMathRadical-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathRadical createMathRadical(IMathElement baseArgument, IMathElement degreeArgument)
```


建立數學根式

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | 套用根號的基礎參數 |
| degreeArgument | [IMathElement](../../com.aspose.slides/imathelement) | 次方值 |

**傳回值:**
[IMathRadical](../../com.aspose.slides/imathradical) - 新的根號元素