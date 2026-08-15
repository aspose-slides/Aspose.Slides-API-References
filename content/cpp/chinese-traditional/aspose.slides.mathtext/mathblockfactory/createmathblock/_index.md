---
title: CreateMathBlock()
second_title: Aspose.Slides for C++ API 參考文件
description: 建立數學區塊
type: docs
weight: 1
url: /zh-hant/aspose.slides.mathtext/mathblockfactory/createmathblock/
---
## MathBlockFactory::CreateMathBlock() 方法


建立數學區塊

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlockFactory::CreateMathBlock() override
```


### 傳回值

新的數學區塊

## MathBlockFactory::CreateMathBlock(System::SharedPtr\<IMathElement\>) 方法


建立數學區塊並將元素放入其中

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlockFactory::CreateMathBlock(System::SharedPtr<IMathElement> mathElement) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 數學元素 |

### 傳回值

新的數學區塊

## MathBlockFactory::CreateMathBlock(System::SharedPtr\<IMathElementCollection\>) 方法


建立數學區塊並將多個元素放入其中

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlockFactory::CreateMathBlock(System::SharedPtr<IMathElementCollection> mathElements) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| mathElements | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElementCollection](../../imathelementcollection/)\> | 數學元素 |

### 傳回值

新的數學區塊

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathBlock](../../imathblock/)
* Class [MathBlockFactory](../)
* Class [IMathElement](../../imathelement/)
* Class [IMathElementCollection](../../imathelementcollection/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)