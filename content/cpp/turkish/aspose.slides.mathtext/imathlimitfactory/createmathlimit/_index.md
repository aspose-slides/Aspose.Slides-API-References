---
title: CreateMathLimit()
second_title: Aspose.Slides for C++ API Referansı
description: IMathLimit oluşturur
type: docs
weight: 1
url: /tr/aspose.slides.mathtext/imathlimitfactory/createmathlimit/
---
## IMathLimitFactory::CreateMathLimit(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, bool) metot


Oluşturur [IMathLimit](../../imathlimit/)

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathLimitFactory::CreateMathLimit(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> limit, bool upperLimit)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| baseArg | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Sınıra uygulanan temel argüman |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Limit öğesi |
| upperLimit | **bool** | Limitin üstte yerleştirilmesini ayarlar |

### Dönüş Değeri

yeni matematik sınırı

## IMathLimitFactory::CreateMathLimit(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) metot


Oluşturur [IMathLimit](../../imathlimit/) alt kısıtla

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathLimitFactory::CreateMathLimit(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> limit)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| baseArg | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Sınıra uygulanan temel argüman |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Limit öğesi |

### Dönüş Değeri

yeni matematik sınırı

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathLimit](../../imathlimit/)
* Sınıf [IMathElement](../../imathelement/)
* Sınıf [IMathLimitFactory](../)
* AdAlanı [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)