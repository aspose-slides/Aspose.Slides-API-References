---
title: SetUpperLimit()
second_title: Aspose.Slides for C++ API リファレンス
description: 上限を設定します
type: docs
weight: 144
url: /ja/aspose.slides.mathtext/imathelement/setupperlimit/
---
## IMathElement::SetUpperLimit(System::SharedPtr\<IMathElement\>) メソッド

上限を設定します

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathElement::SetUpperLimit(System::SharedPtr<IMathElement> limit)=0
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | limit |

### 戻り値

型 [IMathLimit](../../imathlimit/) の新しいインスタンス
## 備考



例: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"y");
auto limitValue = System::MakeObject<MathematicalText>(u"y?>1");
auto limitElement = baseElement->SetUpperLimit(limitValue);
```

## IMathElement::SetUpperLimit(System::String) メソッド

上限を設定します

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathElement::SetUpperLimit(System::String limit)=0
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| limit | [System::String](../../../system/string/) | limit |

### 戻り値

型 [IMathLimit](../../imathlimit/) の新しいインスタンス
## 備考



例: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"y");
auto limitElement = baseElement->SetUpperLimit(u"y?>1");
```

## 関連項目

* typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IMathLimit](../../imathlimit/)
* クラス [IMathElement](../)
* クラス [String](../../../system/string/)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)