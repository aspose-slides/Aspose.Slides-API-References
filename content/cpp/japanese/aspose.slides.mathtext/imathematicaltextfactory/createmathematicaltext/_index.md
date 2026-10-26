---
title: CreateMathematicalText()
second_title: Aspose.Slides for C++ API リファレンス
description: 空の数式テキスト要素を作成
type: docs
weight: 1
url: /ja/aspose.slides.mathtext/imathematicaltextfactory/createmathematicaltext/
---
## IMathematicalTextFactory::CreateMathematicalText() メソッド

空の数式テキスト要素を作成

```cpp
virtual System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::IMathematicalTextFactory::CreateMathematicalText()=0
```

### 戻り値

新しい Mathematical Text

## IMathematicalTextFactory::CreateMathematicalText(char16_t) メソッド

指定された値で数式テキスト要素を作成

```cpp
virtual System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::IMathematicalTextFactory::CreateMathematicalText(char16_t mathSymbol)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| mathSymbol | char16_t | テキスト値として使用する単一シンボル |

### 戻り値

新しい Mathematical Text

## IMathematicalTextFactory::CreateMathematicalText(System::String) メソッド

指定された値で空の数式テキスト要素を作成

```cpp
virtual System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::IMathematicalTextFactory::CreateMathematicalText(System::String mathText)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | テキスト値 |

### 戻り値

新しい Mathematical Text

## IMathematicalTextFactory::CreateMathematicalText(System::String, System::SharedPtr\<IPortionFormat\>) メソッド

指定された値と書式設定プロパティで空の数式テキスト要素を作成

```cpp
virtual System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::IMathematicalTextFactory::CreateMathematicalText(System::String mathText, System::SharedPtr<IPortionFormat> portionFormat)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | テキスト値 |
| portionFormat | [System::SharedPtr](../../../system/sharedptr/)\<[IPortionFormat](../../../aspose.slides/iportionformat/)\> | テキスト書式設定 |

### 戻り値

新しい Mathematical Text

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IMathematicalText](../../imathematicaltext/)
* クラス [IMathematicalTextFactory](../)
* クラス [String](../../../system/string/)
* クラス [IPortionFormat](../../../aspose.slides/iportionformat/)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)