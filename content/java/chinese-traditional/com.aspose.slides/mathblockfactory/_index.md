---
title: MathBlockFactory
second_title: Aspose.Slides for Java API 參考文件
description: 允許建立數學區塊
type: docs
url: /zh-hant/com.aspose.slides/mathblockfactory/
---
**繼承：**
java.lang.Object

**所有實作的介面：**
[com.aspose.slides.IMathBlockFactory](../../com.aspose.slides/imathblockfactory)
```
public class MathBlockFactory implements IMathBlockFactory
```

允許建立數學區塊

--------------------

適用於 COM 相容性
## 建構函式

| 建構式 | 說明 |
| --- | --- |
| [MathBlockFactory()](#MathBlockFactory--) |  |
## 方法

| 方法 | 說明 |
| --- | --- |
| [createMathBlock()](#createMathBlock--) | 建立數學區塊 |
| [createMathBlock(IMathElement mathElement)](#createMathBlock-com.aspose.slides.IMathElement-) | 建立數學區塊並將元素放入其中 |
| [createMathBlock(IMathElementCollection mathElements)](#createMathBlock-com.aspose.slides.IMathElementCollection-) | 建立數學區塊並將多個元素放入其中 |
### MathBlockFactory() {#MathBlockFactory--}
```
public MathBlockFactory()
```

### createMathBlock() {#createMathBlock--}
```
public final IMathBlock createMathBlock()
```

建立數學區塊

**傳回值：**
[IMathBlock](../../com.aspose.slides/imathblock) - 新的數學區塊
### createMathBlock(IMathElement mathElement) {#createMathBlock-com.aspose.slides.IMathElement-}
```
public final IMathBlock createMathBlock(IMathElement mathElement)
```

建立數學區塊並將元素放入其中

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | 數學元素 |

**傳回值：**
[IMathBlock](../../com.aspose.slides/imathblock) - 新的數學區塊
### createMathBlock(IMathElementCollection mathElements) {#createMathBlock-com.aspose.slides.IMathElementCollection-}
```
public final IMathBlock createMathBlock(IMathElementCollection mathElements)
```

建立數學區塊並將多個元素放入其中

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | 數學元素 |

**傳回值：**
[IMathBlock](../../com.aspose.slides/imathblock) - 新的數學區塊