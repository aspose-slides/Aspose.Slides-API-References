---
title: CreateMathParagraph()
second_title: Aspose.Slides for C++ API 參考文件
description: 建立空的數學段落
type: docs
weight: 1
url: /zh-hant/aspose.slides.mathtext/imathparagraphfactory/createmathparagraph/
---
## IMathParagraphFactory::CreateMathParagraph() 方法


建立空的數學段落

```cpp
virtual System::SharedPtr<IMathParagraph> Aspose::Slides::MathText::IMathParagraphFactory::CreateMathParagraph()=0
```


### 傳回值

新的數學段落

## IMathParagraphFactory::CreateMathParagraph(System::SharedPtr\<IMathBlock\>) 方法


建立數學段落並將指定的數學區塊放入其中

```cpp
virtual System::SharedPtr<IMathParagraph> Aspose::Slides::MathText::IMathParagraphFactory::CreateMathParagraph(System::SharedPtr<IMathBlock> mathBlock)=0
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| mathBlock | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | 要放入段落的數學區塊 |

### 傳回值

新的數學段落

## 另請參見

* 類型別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathParagraph](../../imathparagraph/)
* 類別 [IMathParagraphFactory](../)
* 類別 [IMathBlock](../../imathblock/)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)