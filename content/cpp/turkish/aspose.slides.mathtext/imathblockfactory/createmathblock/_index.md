---
title: CreateMathBlock()
second_title: Aspose.Slides for C++ API Referansı
description: Bir matematik bloğu oluştur
type: docs
weight: 1
url: /tr/aspose.slides.mathtext/imathblockfactory/createmathblock/
---
## IMathBlockFactory::CreateMathBlock() method

Bir matematik bloğu oluştur

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathBlockFactory::CreateMathBlock()=0
```

### Dönüş Değeri

yeni matematik bloğu

## IMathBlockFactory::CreateMathBlock(System::SharedPtr\<IMathElement\>) method

Bir matematik bloğu oluştur ve öğeyi içine yerleştir

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathBlockFactory::CreateMathBlock(System::SharedPtr<IMathElement> mathElement)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Bir matematik öğesi |

### Dönüş Değeri

yeni matematik bloğu

## IMathBlockFactory::CreateMathBlock(System::SharedPtr\<IMathElementCollection\>) method

Bir matematik bloğu oluştur ve öğeleri içine yerleştir

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathBlockFactory::CreateMathBlock(System::SharedPtr<IMathElementCollection> mathElements)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mathElements | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElementCollection](../../imathelementcollection/)\> | matematik öğeleri |

### Dönüş Değeri

yeni matematik bloğu

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathBlock](../../imathblock/)
* Sınıf [IMathBlockFactory](../)
* Sınıf [IMathElement](../../imathelement/)
* Sınıf [IMathElementCollection](../../imathelementcollection/)
* AdAlanı [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)