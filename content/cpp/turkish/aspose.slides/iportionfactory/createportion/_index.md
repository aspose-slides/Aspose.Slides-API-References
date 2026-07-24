---
title: CreatePortion()
second_title: Aspose.Slides for C++ API Referansı
description: Boş bir metin bölümü oluşturur.
type: docs
weight: 1
url: /tr/aspose.slides/iportionfactory/createportion/
---
## IPortionFactory::CreatePortion() metod


Boş bir metin bölümü oluşturur.

```cpp
virtual System::SharedPtr<IPortion> Aspose::Slides::IPortionFactory::CreatePortion()=0
```


### Dönüş Değeri

[Portion](../../portion/).

## IPortionFactory::CreatePortion(System::String) metod


Belirtilen dizeden bir metin bölümü oluşturur.

```cpp
virtual System::SharedPtr<IPortion> Aspose::Slides::IPortionFactory::CreatePortion(System::String str)=0
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | [System::String](../../../system/string/) | String. |

### Dönüş Değeri

[Portion](../../portion/).

## IPortionFactory::CreatePortion(System::SharedPtr\<IPortion\>) metod


Belirtilen bölüm verisi kullanılarak bir bölüm oluşturur.

```cpp
virtual System::SharedPtr<IPortion> Aspose::Slides::IPortionFactory::CreatePortion(System::SharedPtr<IPortion> portion)=0
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| portion | [System::SharedPtr](../../../system/sharedptr/)\<[IPortion](../../iportion/)\> | Kullanılacak bir bölüm. |

### Dönüş Değeri

[Portion](../../portion/).

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IPortion](../../iportion/)
* Sınıf [IPortionFactory](../)
* Sınıf [String](../../../system/string/)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)