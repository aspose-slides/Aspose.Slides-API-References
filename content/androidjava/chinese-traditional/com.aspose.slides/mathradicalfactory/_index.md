---
title: MathRadicalFactory
second_title: Aspose.Slides for Android via Java API 參考
description: 允許建立數學根號
type: docs
url: /zh-hant/com.aspose.slides/mathradicalfactory/
---
**Inheritance:**  
java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.IMathRadicalFactory](../../com.aspose.slides/imathradicalfactory)  
```
public class MathRadicalFactory implements IMathRadicalFactory
```

允許建立數學根號

--------------------

用於 COM 相容性
## Constructors

| Constructor | Description |
| --- | --- |
| [MathRadicalFactory()](#MathRadicalFactory--) |  |
## Methods

| Method | Description |
| --- | --- |
| [createMathRadical(IMathElement baseArgument, IMathElement degreeArgument)](#createMathRadical-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | 建立數學根號 |
### MathRadicalFactory() {#MathRadicalFactory--}
```
public MathRadicalFactory()
```


### createMathRadical(IMathElement baseArgument, IMathElement degreeArgument) {#createMathRadical-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathRadical createMathRadical(IMathElement baseArgument, IMathElement degreeArgument)
```

建立數學根號

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | 套用根號的基礎參數 |
| degreeArgument | [IMathElement](../../com.aspose.slides/imathelement) | 次方值 |

**Returns:**  
[IMathRadical](../../com.aspose.slides/imathradical) - 新的根號元素