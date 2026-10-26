---
title: CreateMathematicalText()
second_title: Aspose.Slides for C++ API 參考
description: 建立空的數學文字元素
type: docs
weight: 1
url: /zh-hant/aspose.slides.mathtext/mathematicaltextfactory/createmathematicaltext/
---
## MathematicalTextFactory::CreateMathematicalText() method


建立空的數學文字元素

```cpp
System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::MathematicalTextFactory::CreateMathematicalText() override
```


### 返回值

new Mathematical Text

## MathematicalTextFactory::CreateMathematicalText(char16_t) method


建立具有指定值的數學文字元素

```cpp
System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::MathematicalTextFactory::CreateMathematicalText(char16_t mathSymbol) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| mathSymbol | char16_t | 作為文字值的單一符號 |

### 返回值

new Mathematical Text

## MathematicalTextFactory::CreateMathematicalText(System::String) method


建立具有指定值的空數學文字元素

```cpp
System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::MathematicalTextFactory::CreateMathematicalText(System::String mathText) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | 文字值 |

### 返回值

new Mathematical Text

## MathematicalTextFactory::CreateMathematicalText(System::String, System::SharedPtr\<IPortionFormat\>) method


建立具有指定值和格式屬性的空數學文字元素

```cpp
System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::MathematicalTextFactory::CreateMathematicalText(System::String mathText, System::SharedPtr<IPortionFormat> portionFormat) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | 文字值 |
| portionFormat | [System::SharedPtr](../../../system/sharedptr/)\<[IPortionFormat](../../../aspose.slides/iportionformat/)\> | 文字格式設定 |

### 返回值

new Mathematical Text

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathematicalText](../../imathematicaltext/)
* Class [MathematicalTextFactory](../)
* Class [String](../../../system/string/)
* Class [IPortionFormat](../../../aspose.slides/iportionformat/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)