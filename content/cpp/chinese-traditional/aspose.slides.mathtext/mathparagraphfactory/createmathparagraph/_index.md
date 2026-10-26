---
title: CreateMathParagraph()
second_title: Aspose.Slides for C++ API 參考文件
description: 建立空的數學段落
type: docs
weight: 1
url: /zh-hant/aspose.slides.mathtext/mathparagraphfactory/createmathparagraph/
---
## MathParagraphFactory::CreateMathParagraph() 方法


建立空的數學段落

```cpp
System::SharedPtr<IMathParagraph> Aspose::Slides::MathText::MathParagraphFactory::CreateMathParagraph() override
```


### 返回值

新的數學段落

## MathParagraphFactory::CreateMathParagraph(System::SharedPtr\<IMathBlock\>) 方法


建立一個數學段落，並將指定的數學區塊放入其中

```cpp
System::SharedPtr<IMathParagraph> Aspose::Slides::MathText::MathParagraphFactory::CreateMathParagraph(System::SharedPtr<IMathBlock> mathBlock) override
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| mathBlock | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | 要放入段落的數學區塊 |

### 返回值

新的數學段落

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathParagraph](../../imathparagraph/)
* 類別 [MathParagraphFactory](../)
* 類別 [IMathBlock](../../imathblock/)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)