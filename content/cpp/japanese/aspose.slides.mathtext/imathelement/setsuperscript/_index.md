---
title: SetSuperscript()
second_title: Aspose.Slides for C++ API リファレンス
description: 上付き文字を作成します
type: docs
weight: 92
url: /ja/aspose.slides.mathtext/imathelement/setsuperscript/
---
## IMathElement::SetSuperscript(System::SharedPtr\<IMathElement\>) method

上付き文字を作成します

```cpp
virtual System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSuperscript(System::SharedPtr<IMathElement> superscript)=0
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | 上付き文字（右側の上付きインデックス） |

### 戻り値

型 [IMathSuperscriptElement](../../imathsuperscriptelement/) の新しい数式要素

## 備考



例: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"4");
auto superscript = element->SetSuperscript(index);
```

## IMathElement::SetSuperscript(System::String) method

上付き文字を作成します

```cpp
virtual System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSuperscript(System::String superscript)=0
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| superscript | [System::String](../../../system/string/) | 上付き文字（右側の上付きインデックス） |

### 戻り値

型 [IMathSuperscriptElement](../../imathsuperscriptelement/) の新しい数式要素

## 備考



例: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto superscript = element->SetSuperscript(u"4");
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IMathSuperscriptElement](../../imathsuperscriptelement/)
* クラス [IMathElement](../)
* クラス [String](../../../system/string/)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)