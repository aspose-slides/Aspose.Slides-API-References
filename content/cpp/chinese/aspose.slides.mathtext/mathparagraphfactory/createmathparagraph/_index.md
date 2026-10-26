---
title: CreateMathParagraph()
second_title: Aspose.Slides for C++ API 参考文档
description: 创建空数学段落
type: docs
weight: 1
url: /zh/aspose.slides.mathtext/mathparagraphfactory/createmathparagraph/
---
## MathParagraphFactory::CreateMathParagraph() 方法

创建空数学段落

```cpp
System::SharedPtr<IMathParagraph> Aspose::Slides::MathText::MathParagraphFactory::CreateMathParagraph() override
```

### 返回值

新的数学段落

## MathParagraphFactory::CreateMathParagraph(System::SharedPtr\<IMathBlock\>) 方法

创建一个数学段落并将指定的数学块放入其中

```cpp
System::SharedPtr<IMathParagraph> Aspose::Slides::MathText::MathParagraphFactory::CreateMathParagraph(System::SharedPtr<IMathBlock> mathBlock) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mathBlock | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | 要放入段落的数学块 |

### 返回值

新的数学段落

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IMathParagraph](../../imathparagraph/)
* 类 [MathParagraphFactory](../)
* 类 [IMathBlock](../../imathblock/)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)