---
title: IMathRadicalFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create math radical
type: docs
url: /zh-hant/com.aspose.slides/imathradicalfactory/
---```
public interface IMathRadicalFactory
```

允許建立數學根號

--------------------

用於 COM 相容性
## 方法

| 方法 | 說明 |
| --- | --- |
| [createMathRadical(IMathElement baseArgument, IMathElement degreeArgument)](#createMathRadical-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | 建立數學根號 |
### createMathRadical(IMathElement baseArgument, IMathElement degreeArgument) {#createMathRadical-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathRadical createMathRadical(IMathElement baseArgument, IMathElement degreeArgument)
```

建立數學根號

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | 用於套用根號的基礎參數 |
| degreeArgument | [IMathElement](../../com.aspose.slides/imathelement) | 次方值 |

**返回值:**
[IMathRadical](../../com.aspose.slides/imathradical) - 新的根號元素