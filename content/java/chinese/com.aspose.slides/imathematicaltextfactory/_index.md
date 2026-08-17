---
title: IMathematicalTextFactory
second_title: Aspose.Slides for Java API 参考
description: 允许创建一个 MathematicalText 元素
type: docs
url: /zh/com.aspose.slides/imathematicaltextfactory/
---```
public interface IMathematicalTextFactory
```

允许创建一个 MathematicalText 元素

--------------------

用于 COM 兼容性
## 方法

| 方法 | 描述 |
| --- | --- |
| [createMathematicalText()](#createMathematicalText--) | Create empty mathematical text element |
| [createMathematicalText(char mathSymbol)](#createMathematicalText-char-) | Create mathematical text element with the specified value |
| [createMathematicalText(String mathText)](#createMathematicalText-java.lang.String-) | Create empty mathematical text element with the specified value |
| [createMathematicalText(String mathText, IPortionFormat portionFormat)](#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | Create empty mathematical text element with the specified value and formatting properties |
### createMathematicalText() {#createMathematicalText--}
```
public abstract IMathematicalText createMathematicalText()
```


创建空的 MathematicalText 元素

**返回：**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - 新的 Mathematical Text
### createMathematicalText(char mathSymbol) {#createMathematicalText-char-}
```
public abstract IMathematicalText createMathematicalText(char mathSymbol)
```


创建 MathematicalText 元素并使用指定的值

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mathSymbol | char | 用作文本值的单个符号 |

**返回：**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - 新的 Mathematical Text
### createMathematicalText(String mathText) {#createMathematicalText-java.lang.String-}
```
public abstract IMathematicalText createMathematicalText(String mathText)
```


创建空的 MathematicalText 元素并使用指定的值

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mathText | java.lang.String | 文本值 |

**返回：**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - 新的 Mathematical Text
### createMathematicalText(String mathText, IPortionFormat portionFormat) {#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public abstract IMathematicalText createMathematicalText(String mathText, IPortionFormat portionFormat)
```


创建空的 MathematicalText 元素并使用指定的值和格式属性

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mathText | java.lang.String | 文本值 |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | 文本格式设置 |

**返回：**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - 新的 Mathematical Text