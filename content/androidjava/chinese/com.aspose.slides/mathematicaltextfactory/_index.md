---
title: MathematicalTextFactory
second_title: Aspose.Slides for Android via Java API 参考
description: 允许创建一个 MathematicalText 元素
type: docs
url: /zh/com.aspose.slides/mathematicaltextfactory/
---
**继承：**
java.lang.Object

**所有实现的接口：**
[com.aspose.slides.IMathematicalTextFactory](../../com.aspose.slides/imathematicaltextfactory)
```
public class MathematicalTextFactory implements IMathematicalTextFactory
```

允许创建一个 MathematicalText 元素

--------------------

用于 COM 兼容性
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MathematicalTextFactory()](#MathematicalTextFactory--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [createMathematicalText()](#createMathematicalText--) | 创建空的数学文本元素 |
| [createMathematicalText(char mathSymbol)](#createMathematicalText-char-) | 创建具有指定值的数学文本元素 |
| [createMathematicalText(String mathText)](#createMathematicalText-java.lang.String-) | 使用指定值创建空的数学文本元素 |
| [createMathematicalText(String mathText, IPortionFormat portionFormat)](#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | 使用指定值和格式属性创建空的数学文本元素 |
### MathematicalTextFactory() {#MathematicalTextFactory--}
```
public MathematicalTextFactory()
```


### createMathematicalText() {#createMathematicalText--}
```
public final IMathematicalText createMathematicalText()
```


创建空的数学文本元素

**返回：**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
### createMathematicalText(char mathSymbol) {#createMathematicalText-char-}
```
public final IMathematicalText createMathematicalText(char mathSymbol)
```


创建具有指定值的数学文本元素

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mathSymbol | char | 用作文本值的单个符号 |

**返回：**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
### createMathematicalText(String mathText) {#createMathematicalText-java.lang.String-}
```
public final IMathematicalText createMathematicalText(String mathText)
```


使用指定值创建空的数学文本元素

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mathText | java.lang.String | 文本值 |

**返回：**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
### createMathematicalText(String mathText, IPortionFormat portionFormat) {#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public final IMathematicalText createMathematicalText(String mathText, IPortionFormat portionFormat)
```


使用指定值和格式属性创建空的数学文本元素

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mathText | java.lang.String | 文本值 |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | 文本格式设置 |

**返回：**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text