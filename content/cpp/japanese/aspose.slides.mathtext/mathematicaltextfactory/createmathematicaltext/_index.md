---
title: CreateMathematicalText()
second_title: Aspose.Slides for C++ API リファレンス
description: 空の数学テキスト要素を作成
type: docs
weight: 1
url: /ja/aspose.slides.mathtext/mathematicaltextfactory/createmathematicaltext/
---
## MathematicalTextFactory::CreateMathematicalText() method

空の Mathematical Text 要素を作成

```cpp
System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::MathematicalTextFactory::CreateMathematicalText() override
```

### 戻り値

new Mathematical Text

## MathematicalTextFactory::CreateMathematicalText(char16_t) method

指定された値で Mathematical Text 要素を作成

```cpp
System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::MathematicalTextFactory::CreateMathematicalText(char16_t mathSymbol) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| mathSymbol | char16_t | テキスト値として使用する単一シンボル |

### 戻り値

new Mathematical Text

## MathematicalTextFactory::CreateMathematicalText(System::String) method

指定された値で空の Mathematical Text 要素を作成

```cpp
System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::MathematicalTextFactory::CreateMathematicalText(System::String mathText) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | テキスト値 |

### 戻り値

new Mathematical Text

## MathematicalTextFactory::CreateMathematicalText(System::String, System::SharedPtr\<IPortionFormat\>) method

指定された値と書式設定プロパティで空の Mathematical Text 要素を作成

```cpp
System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::MathematicalTextFactory::CreateMathematicalText(System::String mathText, System::SharedPtr<IPortionFormat> portionFormat) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | テキスト値 |
| portionFormat | [System::SharedPtr](../../../system/sharedptr/)\<[IPortionFormat](../../../aspose.slides/iportionformat/)\> | テキスト書式設定 |

### 戻り値

new Mathematical Text

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathematicalText](../../imathematicaltext/)
* Class [MathematicalTextFactory](../)
* Class [String](../../../system/string/)
* Class [IPortionFormat](../../../aspose.slides/iportionformat/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)