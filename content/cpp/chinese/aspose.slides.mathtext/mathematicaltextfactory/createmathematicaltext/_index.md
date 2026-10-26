---
title: CreateMathematicalText()
second_title: Aspose.Slides for C++ API 参考
description: 创建空的数学文本元素
type: docs
weight: 1
url: /zh/aspose.slides.mathtext/mathematicaltextfactory/createmathematicaltext/
---
## MathematicalTextFactory::CreateMathematicalText() 方法

创建空的数学文本元素

```cpp
System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::MathematicalTextFactory::CreateMathematicalText() override
```

### 返回值

new Mathematical Text

## MathematicalTextFactory::CreateMathematicalText(char16_t) 方法

使用指定值创建数学文本元素

```cpp
System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::MathematicalTextFactory::CreateMathematicalText(char16_t mathSymbol) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mathSymbol | char16_t | 用作文本值的单个符号 |

### 返回值

new Mathematical Text

## MathematicalTextFactory::CreateMathematicalText(System::String) 方法

使用指定值创建空的数学文本元素

```cpp
System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::MathematicalTextFactory::CreateMathematicalText(System::String mathText) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | 文本值 |

### 返回值

new Mathematical Text

## MathematicalTextFactory::CreateMathematicalText(System::String, System::SharedPtr\<IPortionFormat\>) 方法

使用指定值和格式属性创建空的数学文本元素

```cpp
System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::MathematicalTextFactory::CreateMathematicalText(System::String mathText, System::SharedPtr<IPortionFormat> portionFormat) override
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
* 类 [MathematicalTextFactory](../)
* 类 [String](../../../system/string/)
* 类 [IPortionFormat](../../../aspose.slides/iportionformat/)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)