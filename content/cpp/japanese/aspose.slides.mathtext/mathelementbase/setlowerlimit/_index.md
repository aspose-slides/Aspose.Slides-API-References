---
title: SetLowerLimit()
second_title: Aspose.Slides for C++ API リファレンス
description: 下限を設定します
type: docs
weight: 144
url: /ja/aspose.slides.mathtext/mathelementbase/setlowerlimit/
---
## MathElementBase::SetLowerLimit(System::SharedPtr\<IMathElement\>) メソッド

下限を設定します

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathElementBase::SetLowerLimit(System::SharedPtr<IMathElement> limit) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 下限 |

### 戻り値

型 [IMathLimit](../../imathlimit/) の新しいインスタンス
## 備考



例: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"lim");
auto limitValue = System::MakeObject<MathematicalText>(u"\U0001d45b→∞");
auto limitElement = baseElement->SetLowerLimit(limitValue);
```

## MathElementBase::SetLowerLimit(System::String) メソッド


下限を設定します

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathElementBase::SetLowerLimit(System::String limit) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| limit | [System::String](../../../system/string/) | 下限 |

### 戻り値

型 [IMathLimit](../../imathlimit/) の新しいインスタンス
## 備考



例: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"lim");
auto limitElement = baseElement->SetLowerLimit(u"\U0001d45b→∞");
```

## 関連項目

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IMathLimit](../../imathlimit/)
* クラス [IMathElement](../../imathelement/)
* クラス [MathElementBase](../)
* クラス [String](../../../system/string/)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)