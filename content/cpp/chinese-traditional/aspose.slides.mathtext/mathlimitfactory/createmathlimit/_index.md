---
title: CreateMathLimit()
second_title: Aspose.Slides for C++ API 參考文件
description: 建立 IMathLimit
type: docs
weight: 1
url: /zh-hant/aspose.slides.mathtext/mathlimitfactory/createmathlimit/
---
## MathLimitFactory::CreateMathLimit(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, bool) method


建立 [IMathLimit](../../imathlimit/)

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathLimitFactory::CreateMathLimit(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> limit, bool upperLimit) override
```


### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| baseArg | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 套用限制的基礎參數 |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 限制元素 |
| upperLimit | **bool** | 設定限制置於上方 |

### 返回值

新的數學限制

## MathLimitFactory::CreateMathLimit(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) method


建立 [IMathLimit](../../imathlimit/)，限制位於下方

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathLimitFactory::CreateMathLimit(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> limit) override
```


### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| baseArg | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 套用限制的基礎參數 |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 限制元素 |

### 返回值

新的數學限制

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathLimit](../../imathlimit/)
* 類別 [IMathElement](../../imathelement/)
* 類別 [MathLimitFactory](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)