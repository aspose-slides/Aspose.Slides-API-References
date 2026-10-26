---
title: CreateMathematicalText()
second_title: Aspose.Slides for C++ API 参考
description: 创建空的数学文本元素
type: docs
weight: 1
url: /zh/aspose.slides.mathtext/imathematicaltextfactory/createmathematicaltext/
---
## IMathematicalTextFactory::CreateMathematicalText() 方法

创建空的数学文本元素

```cpp
virtual System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::IMathematicalTextFactory::CreateMathematicalText()=0
```

### 返回值

new Mathematical Text

## IMathematicalTextFactory::CreateMathematicalText(char16_t) 方法

使用指定的值创建数学文本元素

```cpp
virtual System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::IMathematicalTextFactory::CreateMathematicalText(char16_t mathSymbol)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mathSymbol | char16_t | 单个符号用作文本值 |

### 返回值

new Mathematical Text

## IMathematicalTextFactory::CreateMathematicalText(System::String) 方法

使用指定的值创建空的数学文本元素

```cpp
virtual System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::IMathematicalTextFactory::CreateMathematicalText(System::String mathText)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | 文本值 |

### 返回值

new Mathematical Text

## IMathematicalTextFactory::CreateMathematicalText(System::String, System::SharedPtr\<IPortionFormat\>) 方法

使用指定的值和格式属性创建空的数学文本元素

```cpp
virtual System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::IMathematicalTextFactory::CreateMathematicalText(System::String mathText, System::SharedPtr<IPortionFormat> portionFormat)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | 文本值 |
| portionFormat | [System::SharedPtr](../../../system/sharedptr/)\<[IPortionFormat](../../../aspose.slides/iportionformat/)\> | 文本格式设置 |

### 返回值

new Mathematical Text

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IMathematicalText](../../imathematicaltext/)
* 类 [IMathematicalTextFactory](../)
* 类 [String](../../../system/string/)
* 类 [IPortionFormat](../../../aspose.slides/iportionformat/)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)