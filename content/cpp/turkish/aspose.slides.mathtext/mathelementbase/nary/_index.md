---
title: Nary()
second_title: Aspose.Slides for C++ API Referansı
description: N-ary bir operatör oluşturur
type: docs
weight: 157
url: /tr/aspose.slides.mathtext/mathelementbase/nary/
---
## MathElementBase::Nary(MathNaryOperatorTypes, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) metot

N-ary bir operatör oluşturur

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathElementBase::Nary(MathNaryOperatorTypes type, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| type | [MathNaryOperatorTypes](../../mathnaryoperatortypes/) | The N-ary operator type |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | The lower limit |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | The upper limit |

### Dönüş Değeri

Yeni [IMathNaryOperator](../../imathnaryoperator/) türünden örnek

## Açıklamalar

Örnek: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"i-1");
auto lowerLimit = System::MakeObject<MathematicalText>(u"i=0");
auto upperLimit = System::MakeObject<MathematicalText>(u"\U0001d465");
auto naryOperator = baseElement->Nary(MathNaryOperatorTypes::Summation, lowerLimit, upperLimit);
```

## MathElementBase::Nary(MathNaryOperatorTypes, System::String, System::String) metot

N-ary bir operatör oluşturur

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathElementBase::Nary(MathNaryOperatorTypes type, System::String lowerLimit, System::String upperLimit) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| type | [MathNaryOperatorTypes](../../mathnaryoperatortypes/) | The N-ary operator type |
| lowerLimit | [System::String](../../../system/string/) | The lower limit |
| upperLimit | [System::String](../../../system/string/) | The upper limit |

### Dönüş Değeri

Yeni [IMathNaryOperator](../../imathnaryoperator/) türünden örnek

## Açıklamalar

Örnek: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"i")->Nary(MathNaryOperatorTypes::Summation, u"i=0", u"\U0001d465");
```

## Ayrıca Bakınız

* Enum [MathNaryOperatorTypes](../../mathnaryoperatortypes/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathNaryOperator](../../imathnaryoperator/)
* Sınıf [IMathElement](../../imathelement/)
* Sınıf [MathElementBase](../)
* Sınıf [String](../../../system/string/)
* Ad Alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)