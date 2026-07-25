---
title: SetSubSuperscriptOnTheRight()
second_title: Aspose.Slides for C++ APIリファレンス
description: 右側に下付き文字と上付き文字を作成します
type: docs
weight: 105
url: /ja/aspose.slides.mathtext/imathelement/setsubsuperscriptontheright/
---
## IMathElement::SetSubSuperscriptOnTheRight(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) メソッド


右側に下付きと上付きの文字を作成します

```cpp
virtual System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSubSuperscriptOnTheRight(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | 下付き (右側の下付きインデックス) |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | 上付き (右側の上付きインデックス) |

### 戻り値

[IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/) 型の新しい数式要素
## 備考



例: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = baseElement->SetSubSuperscriptOnTheRight(subscript, superscript);
```

## IMathElement::SetSubSuperscriptOnTheRight(System::String, System::String) メソッド


右側に下付きと上付きの文字を作成します

```cpp
virtual System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSubSuperscriptOnTheRight(System::String subscript, System::String superscript)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | 下付き (右側の下付きインデックス) |
| superscript | [System::String](../../../system/string/) | 上付き (右側の上付きインデックス) |

### 戻り値

[IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/) 型の新しい数式要素
## 備考



例: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subsuperscript = baseElement->SetSubSuperscriptOnTheRight(u"i", u"j");
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
* クラス [IMathElement](../)
* クラス [String](../../../system/string/)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)