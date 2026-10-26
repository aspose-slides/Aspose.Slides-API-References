---
title: SetSubSuperscriptOnTheLeft()
second_title: Aspose.Slides C++ 用 API リファレンス
description: 左側に下付き文字と上付き文字を作成します
type: docs
weight: 105
url: /ja/aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft/
---
## MathElementBase::SetSubSuperscriptOnTheLeft(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) メソッド


左側に下付き文字と上付き文字を作成します

```cpp
System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheLeft(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript) override
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 下付き文字（左側の下付きインデックス） |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 上付き文字（左側の上付きインデックス） |

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

## MathElementBase::SetSubSuperscriptOnTheLeft(System::String, System::String) メソッド


左側に下付き文字と上付き文字を作成します

```cpp
System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheLeft(System::String subscript, System::String superscript) override
```


### 引数

| Parameter | Type | Description |
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

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
* クラス [IMathElement](../../imathelement/)
* クラス [MathElementBase](../)
* クラス [String](../../../system/string/)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)