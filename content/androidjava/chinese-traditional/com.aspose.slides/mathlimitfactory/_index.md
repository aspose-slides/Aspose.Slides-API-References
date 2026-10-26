---
title: MathLimitFactory
second_title: Aspose.Slides for Android via Java API 參考文件
description: 允許建立 IMathLimit
type: docs
url: /zh-hant/com.aspose.slides/mathlimitfactory/
---
**繼承關係:**  
java.lang.Object  

**所有已實作的介面:**  
[com.aspose.slides.IMathLimitFactory](../../com.aspose.slides/imathlimitfactory)  
```
public class MathLimitFactory implements IMathLimitFactory
```  

允許建立 IMathLimit  

--------------------  

供 COM 相容性使用  

## 建構式

| 建構子 | 說明 |
| --- | --- |
| [MathLimitFactory()](#MathLimitFactory--) |  |

## 方法

| 方法 | 說明 |
| --- | --- |
| [createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-) | 建立 IMathLimit |
| [createMathLimit(IMathElement baseArg, IMathElement limit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | 建立底部限制的 IMathLimit |

### MathLimitFactory() {#MathLimitFactory--}
```
public MathLimitFactory()
```

### createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-}
```
public final IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)
```

建立 IMathLimit  

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | 套用限制的基礎參數 |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | 限制元素 |
| upperLimit | boolean | 設定限制置於上方 |

**回傳:**  
[IMathLimit](../../com.aspose.slides/imathlimit) - 新的數學限制  

### createMathLimit(IMathElement baseArg, IMathElement limit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit)
```

建立底部限制的 IMathLimit  

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | 套用限制的基礎參數 |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | 限制元素 |

**回傳:**  
[IMathLimit](../../com.aspose.slides/imathlimit) - 新的數學限制