---
title: SetLowerLimit()
second_title: Aspose.Slides for C++ API リファレンス
description: 下限を設定します
type: docs
weight: 157
url: /ja/aspose.slides.mathtext/imathelement/setlowerlimit/
---
## IMathElement::SetLowerLimit(System::SharedPtr\<IMathElement\>) メソッド

下限を設定します

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathElement::SetLowerLimit(System::SharedPtr<IMathElement> limit)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | 下限 |
 
### 戻り値

型 [IMathLimit](../../imathlimit/) の新しいインスタンス

## 備考



例: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"lim");
auto limitValue = System::MakeObject<MathematicalText>(u"\U0001d45b→∞");
auto limitElement = baseElement->SetLowerLimit(limitValue);
```

## IMathElement::SetLowerLimit(System::String) メソッド

下限を設定します

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathElement::SetLowerLimit(System::String limit)=0
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
System::SharedPtr<IMathElement> baseElement = System::MakeObject<MathematicalText>(u"lim");
auto limitElement = baseElement->SetLowerLimit(u"\U0001d45b→∞");
```

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathLimit](../../imathlimit/)
* Class [IMathElement](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)