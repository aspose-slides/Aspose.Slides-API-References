---
title: CreateMathematicalText()
second_title: Aspose.Slides for C++ API 參考
description: 建立空的數學文字元素
type: docs
weight: 1
url: /zh-hant/aspose.slides.mathtext/imathematicaltextfactory/createmathematicaltext/
---
## IMathematicalTextFactory::CreateMathematicalText() 方法

建立空的數學文字元素

```cpp
virtual System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::IMathematicalTextFactory::CreateMathematicalText()=0
```

### 返回值

new Mathematical Text

## IMathematicalTextFactory::CreateMathematicalText(char16_t) 方法

建立具有指定值的數學文字元素

```cpp
virtual System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::IMathematicalTextFactory::CreateMathematicalText(char16_t mathSymbol)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| mathSymbol | char16_t | 使用作為文字值的單一符號 |

### 返回值

new Mathematical Text

## IMathematicalTextFactory::CreateMathematicalText(System::String) 方法

建立具有指定值的空數學文字元素

```cpp
virtual System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::IMathematicalTextFactory::CreateMathematicalText(System::String mathText)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | 文字值 |

### 返回值

new Mathematical Text

## IMathematicalTextFactory::CreateMathematicalText(System::String, System::SharedPtr\<IPortionFormat\>) 方法

建立具有指定值和格式屬性的空數學文字元素

```cpp
virtual System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::IMathematicalTextFactory::CreateMathematicalText(System::String mathText, System::SharedPtr<IPortionFormat> portionFormat)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | 文字值 |
| portionFormat | [System::SharedPtr](../../../system/sharedptr/)\<[IPortionFormat](../../../aspose.slides/iportionformat/)\> | 文字格式設定 |

### 返回值

new Mathematical Text

## 另請參閱

* 類型別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathematicalText](../../imathematicaltext/)
* 類別 [IMathematicalTextFactory](../)
* 類別 [String](../../../system/string/)
* 類別 [IPortionFormat](../../../aspose.slides/iportionformat/)
* 命名空間 [Aspose::Slides::MathText](../../)
* 程式庫 [Aspose.Slides](../../../)