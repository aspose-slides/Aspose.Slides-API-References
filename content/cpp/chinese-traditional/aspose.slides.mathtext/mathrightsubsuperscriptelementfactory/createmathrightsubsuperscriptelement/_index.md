---
title: CreateMathRightSubSuperscriptElement()
second_title: Aspose.Slides for C++ API 參考
description: 建立 IMathRightSubSuperscriptElementFactory 的實例
type: docs
weight: 1
url: /zh-hant/aspose.slides.mathtext/mathrightsubsuperscriptelementfactory/createmathrightsubsuperscriptelement/
---
## MathRightSubSuperscriptElementFactory::CreateMathRightSubSuperscriptElement(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) 方法

建立 [IMathRightSubSuperscriptElementFactory](../../imathrightsubsuperscriptelementfactory/) 的實例

```cpp
System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::MathRightSubSuperscriptElementFactory::CreateMathRightSubSuperscriptElement(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> subScript, System::SharedPtr<IMathElement> superScript) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| baseArg | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 用於套用索引的基礎參數 |
| subScript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 右下索引 |
| superScript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 右上索引 |

### 返回值

new [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)

## 另見

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
* 類別 [IMathElement](../../imathelement/)
* 類別 [MathRightSubSuperscriptElementFactory](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)