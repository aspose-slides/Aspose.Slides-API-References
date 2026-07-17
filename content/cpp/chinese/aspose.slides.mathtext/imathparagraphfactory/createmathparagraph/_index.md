---
title: CreateMathParagraph()
second_title: Aspose.Slides for C++ API 参考
description: 创建空的数学段落
type: docs
weight: 1
url: /zh/aspose.slides.mathtext/imathparagraphfactory/createmathparagraph/
---
## IMathParagraphFactory::CreateMathParagraph() 方法

创建空的数学段落

```cpp
virtual System::SharedPtr<IMathParagraph> Aspose::Slides::MathText::IMathParagraphFactory::CreateMathParagraph()=0
```

### 返回值

新的数学段落

## IMathParagraphFactory::CreateMathParagraph(System::SharedPtr\<IMathBlock\>) 方法

创建一个数学段落并将指定的数学块放置在其中

```cpp
virtual System::SharedPtr<IMathParagraph> Aspose::Slides::MathText::IMathParagraphFactory::CreateMathParagraph(System::SharedPtr<IMathBlock> mathBlock)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mathBlock | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | 要放入段落的数学块 |

### 返回值

新的数学段落

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IMathParagraph](../../imathparagraph/)
* 类 [IMathParagraphFactory](../)
* 类 [IMathBlock](../../imathblock/)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)