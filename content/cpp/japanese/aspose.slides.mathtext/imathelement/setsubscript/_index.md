---
title: SetSubscript()
second_title: Aspose.Slides for C++ API リファレンス
description: サブスクリプトを作成します
type: docs
weight: 79
url: /ja/aspose.slides.mathtext/imathelement/setsubscript/
---
## IMathElement::SetSubscript(System::SharedPtr\<IMathElement\>) メソッド

サブスクリプトを作成します

```cpp
virtual System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::IMathElement::SetSubscript(System::SharedPtr<IMathElement> subscript)=0
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | 右側の下付き (下指数) |

### 戻り値

[IMathSubscriptElement](../../imathsubscriptelement/) 型の新しい数式要素

## 備考



例: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"i");
auto subscript = element->SetSubscript(index);
```

## IMathElement::SetSubscript(System::String) メソッド

サブスクリプトを作成します

```cpp
virtual System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::IMathElement::SetSubscript(System::String subscript)=0
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | 右側の下付き (下指数) |

### 戻り値

[IMathSubscriptElement](../../imathsubscriptelement/) 型の新しい数式要素

## 備考



例: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto subscript = element->SetSubscript(u"i");
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IMathSubscriptElement](../../imathsubscriptelement/)
* クラス [IMathElement](../)
* クラス [String](../../../system/string/)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)