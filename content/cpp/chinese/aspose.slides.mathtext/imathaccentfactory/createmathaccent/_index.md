---
title: CreateMathAccent()
second_title: Aspose.Slides C++ API 参考
description: 创建一个数学重音，应用于指定的数学元素，使用默认的重音字符值
type: docs
weight: 1
url: /zh/aspose.slides.mathtext/imathaccentfactory/createmathaccent/
---
## IMathAccentFactory::CreateMathAccent(System::SharedPtr\<IMathElement\>) 方法

创建一个数学重音，应用于指定的数学元素，使用默认的重音字符值

```cpp
virtual System::SharedPtr<IMathAccent> Aspose::Slides::MathText::IMathAccentFactory::CreateMathAccent(System::SharedPtr<IMathElement> element)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 要应用重音的数学元素 |

### 返回值

新的数学重音

## IMathAccentFactory::CreateMathAccent(System::SharedPtr\<IMathElement\>, char16_t) 方法

创建一个数学重音，应用于指定的数学元素

```cpp
virtual System::SharedPtr<IMathAccent> Aspose::Slides::MathText::IMathAccentFactory::CreateMathAccent(System::SharedPtr<IMathElement> element, char16_t accentCharacter)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 要应用重音的数学元素 |
| accentCharacter | char16_t | 重音字符 |

### 返回值

新的数学重音

## 参见

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathAccent](../../imathaccent/)
* Class [IMathElement](../../imathelement/)
* Class [IMathAccentFactory](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)