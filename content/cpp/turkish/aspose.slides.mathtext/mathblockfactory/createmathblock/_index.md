---
title: CreateMathBlock()
second_title: Aspose.Slides for C++ API Referansı
description: Bir matematik bloğu oluştur
type: docs
weight: 1
url: /tr/aspose.slides.mathtext/mathblockfactory/createmathblock/
---
## MathBlockFactory::CreateMathBlock() yöntemi


Bir matematik bloğu oluştur

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlockFactory::CreateMathBlock() override
```


### Dönüş Değeri

yeni matematik bloğu

## MathBlockFactory::CreateMathBlock(System::SharedPtr\<IMathElement\>) yöntemi


Bir matematik bloğu oluştur ve elemanı içine yerleştir

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlockFactory::CreateMathBlock(System::SharedPtr<IMathElement> mathElement) override
```


### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Bir matematik öğesi |

### Dönüş Değeri

yeni matematik bloğu

## MathBlockFactory::CreateMathBlock(System::SharedPtr\<IMathElementCollection\>) yöntemi


Bir matematik bloğu oluştur ve elemanları içine yerleştir

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlockFactory::CreateMathBlock(System::SharedPtr<IMathElementCollection> mathElements) override
```


### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| mathElements | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElementCollection](../../imathelementcollection/)\> | matematik öğeleri |

### Dönüş Değeri

yeni matematik bloğu

## Başvurular

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathBlock](../../imathblock/)
* Sınıf [MathBlockFactory](../)
* Sınıf [IMathElement](../../imathelement/)
* Sınıf [IMathElementCollection](../../imathelementcollection/)
* Ad alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)