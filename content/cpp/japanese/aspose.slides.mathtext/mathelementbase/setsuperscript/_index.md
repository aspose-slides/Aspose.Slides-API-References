---
title: SetSuperscript()
second_title: Aspose.Slides for C++ API リファレンス
description: 上付き文字を作成します
type: docs
weight: 79
url: /ja/aspose.slides.mathtext/mathelementbase/setsuperscript/
---
## MathElementBase::SetSuperscript(System::SharedPtr\<IMathElement\>) メソッド

上付き文字を作成します

```cpp
System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSuperscript(System::SharedPtr<IMathElement> superscript) override
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 上付き文字 (右側の上付き指数) |

### 戻り値

タイプ [IMathSuperscriptElement](../../imathsuperscriptelement/) の新しい数式要素

## 備考



```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"4");
auto superscript = element->SetSuperscript(index);
```

## MathElementBase::SetSuperscript(System::String) メソッド

上付き文字を作成します

```cpp
System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSuperscript(System::String superscript) override
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| superscript | [System::String](../../../system/string/) | 上付き文字 (右側の上付き指数) |

### 戻り値

タイプ [IMathSuperscriptElement](../../imathsuperscriptelement/) の新しい数式要素

## 備考



```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto superscript = element->SetSuperscript(u"4");
```

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IMathSuperscriptElement](../../imathsuperscriptelement/)
* クラス [IMathElement](../../imathelement/)
* クラス [MathElementBase](../)
* クラス [String](../../../system/string/)
* 名前空間 [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)