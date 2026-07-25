---
title: Nary()
second_title: Aspose.Slides for C++ API リファレンス
description: N-ary 演算子を作成します
type: docs
weight: 170
url: /ja/aspose.slides.mathtext/imathelement/nary/
---
## IMathElement::Nary(MathNaryOperatorTypes, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) method


N-ary 演算子を作成します

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Nary(MathNaryOperatorTypes type, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| type | [MathNaryOperatorTypes](../../mathnaryoperatortypes/) | N-ary 演算子のタイプ |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | 下限 |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | 上限 |

### Return Value

型 [IMathNaryOperator](../../imathnaryoperator/) の新しいインスタンス
## Remarks



例: 
```cpp
System::SharedPtr<IMathElement> baseElement = System::MakeObject<MathematicalText>(u"i-1");
System::SharedPtr<IMathElement> lowerLimit = System::MakeObject<MathematicalText>(u"i=0");
System::SharedPtr<IMathElement> upperLimit = System::MakeObject<MathematicalText>(u"\U0001d45b");
auto naryOperator = baseElement->Nary(MathNaryOperatorTypes::Summation, lowerLimit, upperLimit);
```

## IMathElement::Nary(MathNaryOperatorTypes, System::String, System::String) method


N-ary 演算子を作成します

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Nary(MathNaryOperatorTypes type, System::String lowerLimit, System::String upperLimit)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| type | [MathNaryOperatorTypes](../../mathnaryoperatortypes/) | N-ary 演算子のタイプ |
| lowerLimit | [System::String](../../../system/string/) | 下限 |
| upperLimit | [System::String](../../../system/string/) | 上限 |

### Return Value

型 [IMathNaryOperator](../../imathnaryoperator/) の新しいインスタンス
## Remarks



例: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"i")->Nary(MathNaryOperatorTypes::Summation, u"i=0", u"\U0001d45b");
```

## See Also

* 列挙体 [MathNaryOperatorTypes](../../mathnaryoperatortypes/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IMathNaryOperator](../../imathnaryoperator/)
* クラス [IMathElement](../)
* クラス [String](../../../system/string/)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)