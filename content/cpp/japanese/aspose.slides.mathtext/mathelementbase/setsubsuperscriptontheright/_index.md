---
title: SetSubSuperscriptOnTheRight()
second_title: Aspose.Slides for C++ API リファレンス
description: 右側に下付文字と上付文字を作成します
type: docs
weight: 92
url: /ja/aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright/
---
## MathElementBase::SetSubSuperscriptOnTheRight(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) メソッド


右側に下付文字と上付文字を作成します

```cpp
System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheRight(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript) override
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 下付文字（右側の下付きインデックス） |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 上付文字（右側の上付きインデックス） |

### 戻り値

型 [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/) の新しい数式要素
## 備考



例: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = baseElement->SetSubSuperscriptOnTheRight(subscript, superscript);
```

## MathElementBase::SetSubSuperscriptOnTheRight(System::String, System::String) メソッド


右側に下付文字と上付文字を作成します

```cpp
System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheRight(System::String subscript, System::String superscript) override
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | 下付文字（右側の下付きインデックス） |
| superscript | [System::String](../../../system/string/) | 上付文字（右側の上付きインデックス） |

### 戻り値

型 [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/) の新しい数式要素
## 備考



例: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subsuperscript = baseElement->SetSubSuperscriptOnTheRight(u"i", u"j");
```

## 関連項目

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
* Class [IMathElement](../../imathelement/)
* Class [MathElementBase](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)