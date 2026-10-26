---
title: IMathematicalTextFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create a MathematicalText element
type: docs
url: /zh/com.aspose.slides/imathematicaltextfactory/
---``` 
public interface IMathematicalTextFactory 
```

允许创建 MathematicalText 元素

--------------------

用于 COM 兼容性
## 方法

| 方法 | 描述 |
| --- | --- |
| [createMathematicalText()](#createMathematicalText--) | 创建空的 MathematicalText 元素 |
| [createMathematicalText(char mathSymbol)](#createMathematicalText-char-) | 使用指定值创建 MathematicalText 元素 |
| [createMathematicalText(String mathText)](#createMathematicalText-java.lang.String-) | 使用指定值创建空的 MathematicalText 元素 |
| [createMathematicalText(String mathText, IPortionFormat portionFormat)](#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | 使用指定值和格式属性创建空的 MathematicalText 元素 |
### createMathematicalText() {#createMathematicalText--}
```
public abstract IMathematicalText createMathematicalText()
```

创建空的 MathematicalText 元素

**返回:**  
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new MathematicalText
### createMathematicalText(char mathSymbol) {#createMathematicalText-char-}
```
public abstract IMathematicalText createMathematicalText(char mathSymbol)
```

使用指定值创建 MathematicalText 元素

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mathSymbol | char | 用作文本值的单个符号 |

**返回:**  
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new MathematicalText
### createMathematicalText(String mathText) {#createMathematicalText-java.lang.String-}
```
public abstract IMathematicalText createMathematicalText(String mathText)
```

使用指定值创建空的 MathematicalText 元素

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mathText | java.lang.String | 文本值 |

**返回:**  
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new MathematicalText
### createMathematicalText(String mathText, IPortionFormat portionFormat) {#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public abstract IMathematicalText createMathematicalText(String mathText, IPortionFormat portionFormat)
```

使用指定值和格式属性创建空的 MathematicalText 元素

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mathText | java.lang.String | 文本值 |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | 文本格式设置 |

**返回:**  
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new MathematicalText