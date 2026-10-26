---
title: SetUpperLimit()
second_title: C++ 用 Aspose.Slides API リファレンス
description: 上限を設定します
type: docs
weight: 131
url: /ja/aspose.slides.mathtext/mathelementbase/setupperlimit/
---
## MathElementBase::SetUpperLimit(System::SharedPtr\<IMathElement\>) メソッド


上限を設定します

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathElementBase::SetUpperLimit(System::SharedPtr<IMathElement> limit) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | limit |

### 戻り値

型 [IMathLimit](../../imathlimit/) の新しいインスタンス
## 備考



例: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"y");
auto limitValue = System::MakeObject<MathematicalText>(u"y?>1");
auto limitElement = baseElement->SetUpperLimit(limitValue);
```

## MathElementBase::SetUpperLimit(System::String) メソッド


上限を設定します

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathElementBase::SetUpperLimit(System::String limit) override
```


### 引数

| パラメータ | 型 | 説明 |
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

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IMathLimit](../../imathlimit/)
* クラス [IMathElement](../../imathelement/)
* クラス [MathElementBase](../)
* クラス [String](../../../system/string/)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)