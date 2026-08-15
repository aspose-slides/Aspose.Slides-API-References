---
title: CreateMathBlock()
second_title: Aspose.Slides for C++ API 參考
description: 建立數學區塊
type: docs
weight: 1
url: /zh-hant/aspose.slides.mathtext/imathblockfactory/createmathblock/
---
## IMathBlockFactory::CreateMathBlock() 方法


建立數學區塊

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathBlockFactory::CreateMathBlock()=0
```


### 返回值

新的數學區塊

## IMathBlockFactory::CreateMathBlock(System::SharedPtr\<IMathElement\>) 方法


建立數學區塊並將元素放入其中

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathBlockFactory::CreateMathBlock(System::SharedPtr<IMathElement> mathElement)=0
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 數學元素 |

### 返回值

新的數學區塊

## IMathBlockFactory::CreateMathBlock(System::SharedPtr\<IMathElementCollection\>) 方法


建立數學區塊並將多個元素放入其中

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathBlockFactory::CreateMathBlock(System::SharedPtr<IMathElementCollection> mathElements)=0
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| mathElements | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElementCollection](../../imathelementcollection/)\> | 數學元素 |

### 返回值

新的數學區塊

## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathBlock](../../imathblock/)
* 類別 [IMathBlockFactory](../)
* 類別 [IMathElement](../../imathelement/)
* 類別 [IMathElementCollection](../../imathelementcollection/)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)