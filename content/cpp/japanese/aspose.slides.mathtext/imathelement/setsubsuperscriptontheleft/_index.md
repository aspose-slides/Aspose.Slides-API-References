---
title: SetSubSuperscriptOnTheLeft()
second_title: Aspose.Slides for C++ API リファレンス
description: 左側に下付き文字および上付き文字を作成します
type: docs
weight: 118
url: /ja/aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft/
---
## IMathElement::SetSubSuperscriptOnTheLeft(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) メソッド


左側に下付き文字および上付き文字を作成します

```cpp
virtual System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSubSuperscriptOnTheLeft(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript)=0
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | 下付き文字（左側の下付きインデックス） |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | 上付き文字（左側の上付きインデックス） |

### 戻り値

タイプ [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/) の新しい数式要素
## 備考



例: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto leftSubsuperscript = baseElement->SetSubSuperscriptOnTheLeft(subscript, superscript);
```

## IMathElement::SetSubSuperscriptOnTheLeft(System::String, System::String) メソッド


左側に下付き文字および上付き文字を作成します

```cpp
virtual System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSubSuperscriptOnTheLeft(System::String subscript, System::String superscript)=0
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | 下付き文字（左側の下付きインデックス） |
| superscript | [System::String](../../../system/string/) | 上付き文字（左側の上付きインデックス） |

### 戻り値

タイプ [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/) の新しい数式要素
## 備考



例: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto leftSubsuperscript = baseElement->SetSubSuperscriptOnTheLeft(u"i", u"j");
```

## 関連項目

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
* クラス [IMathElement](../)
* クラス [String](../../../system/string/)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)