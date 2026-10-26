---
title: SetSubscript()
second_title: Aspose.Slides for C++ API リファレンス
description: 下付き文字を作成します
type: docs
weight: 66
url: /ja/aspose.slides.mathtext/mathelementbase/setsubscript/
---
## MathElementBase::SetSubscript(System::SharedPtr\<IMathElement\>) メソッド


下付き文字を作成します

```cpp
System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubscript(System::SharedPtr<IMathElement> subscript) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 下付き文字（右側の下付き指数） |

### 戻り値

タイプ [IMathSubscriptElement](../../imathsubscriptelement/) の新しい数式要素
## 備考



例： 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"i");
auto subscript = element->SetSubscript(index);
```

## MathElementBase::SetSubscript(System::String) メソッド


下付き文字を作成します

```cpp
System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubscript(System::String subscript) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | 下付き文字（右側の下付き指数） |

### 戻り値

タイプ [IMathSubscriptElement](../../imathsubscriptelement/) の新しい数式要素
## 備考



例： 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto subscript = element->SetSubscript(u"i");
```

## 関連項目

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IMathSubscriptElement](../../imathsubscriptelement/)
* クラス [IMathElement](../../imathelement/)
* クラス [MathElementBase](../)
* クラス [String](../../../system/string/)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)