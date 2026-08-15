---
title: CreateMathLimit()
second_title: Aspose.Slides for C++ API 參考
description: 建立 IMathLimit
type: docs
weight: 1
url: /zh-hant/aspose.slides.mathtext/imathlimitfactory/createmathlimit/
---
## IMathLimitFactory::CreateMathLimit(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, bool) 方法


建立 [IMathLimit](../../imathlimit/)

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathLimitFactory::CreateMathLimit(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> limit, bool upperLimit)=0
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| baseArg | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 用於套用限制的基礎參數 |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 限制元素 |
| upperLimit | **bool** | 設定限制置於上方 |

### 返回值

新的數學限制

## IMathLimitFactory::CreateMathLimit(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) 方法


建立 [IMathLimit](../../imathlimit/)，限制在底部

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathLimitFactory::CreateMathLimit(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> limit)=0
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| baseArg | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 用於套用限制的基礎參數 |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 限制元素 |

### 返回值

新的數學限制

## 另請參閱

* 類型定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathLimit](../../imathlimit/)
* 類別 [IMathElement](../../imathelement/)
* 類別 [IMathLimitFactory](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)