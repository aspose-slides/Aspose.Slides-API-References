---
title: IMathArrayFactory
second_title: Aspose.Slides for Java API Reference
description: 允許建立數學陣列
type: docs
url: /zh-hant/com.aspose.slides/imatharrayfactory/
---```
public interface IMathArrayFactory
```

允許建立數學陣列

--------------------

用於 COM 兼容性
## 方法

| 方法 | 說明 |
| --- | --- |
| [createMathArray(IMathElement element)](#createMathArray-com.aspose.slides.IMathElement-) | 建立一個數學陣列並將指定的元素放入其中 |
| [createMathArray(IMathElementCollection elements)](#createMathArray-com.aspose.slides.IMathElementCollection-) | 建立一個數學陣列並將指定的元素放入其中 |
### createMathArray(IMathElement element) {#createMathArray-com.aspose.slides.IMathElement-}
```
public abstract IMathArray createMathArray(IMathElement element)
```

建立一個數學陣列並將指定的元素放入其中

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 要放入陣列的數學元素 |

**返回值:**  
[IMathArray](../../com.aspose.slides/imatharray) - 新的數學陣列
### createMathArray(IMathElementCollection elements) {#createMathArray-com.aspose.slides.IMathElementCollection-}
```
public abstract IMathArray createMathArray(IMathElementCollection elements)
```

建立一個數學陣列並將指定的元素放入其中

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| elements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | 要放入陣列的數學元素 |

**返回值:**  
[IMathArray](../../com.aspose.slides/imatharray) - 新的數學陣列