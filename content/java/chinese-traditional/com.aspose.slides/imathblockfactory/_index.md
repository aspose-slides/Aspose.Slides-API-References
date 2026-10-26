---
title: IMathBlockFactory
second_title: Aspose.Slides for Java API Reference
description: Allows to create a math block
type: docs
url: /zh-hant/com.aspose.slides/imathblockfactory/
---```
public interface IMathBlockFactory
```

允許建立數學區塊

--------------------

用於 COM 相容性
## 方法

| 方法 | 說明 |
| --- | --- |
| [createMathBlock()](#createMathBlock--) | 建立數學區塊 |
| [createMathBlock(IMathElement mathElement)](#createMathBlock-com.aspose.slides.IMathElement-) | 建立數學區塊並將元素放入其中 |
| [createMathBlock(IMathElementCollection mathElements)](#createMathBlock-com.aspose.slides.IMathElementCollection-) | 建立數學區塊並將多個元素放入其中 |
### createMathBlock() {#createMathBlock--}
```
public abstract IMathBlock createMathBlock()
```

建立數學區塊

**返回：**
[IMathBlock](../../com.aspose.slides/imathblock) - 新的數學區塊
### createMathBlock(IMathElement mathElement) {#createMathBlock-com.aspose.slides.IMathElement-}
```
public abstract IMathBlock createMathBlock(IMathElement mathElement)
```

建立數學區塊並將元素放入其中

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | 數學元素 |

**返回：**
[IMathBlock](../../com.aspose.slides/imathblock) - 新的數學區塊
### createMathBlock(IMathElementCollection mathElements) {#createMathBlock-com.aspose.slides.IMathElementCollection-}
```
public abstract IMathBlock createMathBlock(IMathElementCollection mathElements)
```

建立數學區塊並將多個元素放入其中

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | 數學元素 |

**返回：**
[IMathBlock](../../com.aspose.slides/imathblock) - 新的數學區塊