---
title: CreateMathLimit()
second_title: Aspose.Slides pro C++ – reference API
description: Vytváří IMathLimit
type: docs
weight: 1
url: /cs/aspose.slides.mathtext/imathlimitfactory/createmathlimit/
---
## IMathLimitFactory::CreateMathLimit(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, bool) metoda


Vytváří [IMathLimit](../../imathlimit/)

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathLimitFactory::CreateMathLimit(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> limit, bool upperLimit)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| baseArg | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Základní argument pro aplikaci limitu |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Element limitu |
| upperLimit | **bool** | Nastavuje umístění limitu nahoře |

### Návratová hodnota

nový matematický limit

## IMathLimitFactory::CreateMathLimit(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) metoda


Vytváří [IMathLimit](../../imathlimit/) s limitem dole

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathLimitFactory::CreateMathLimit(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> limit)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| baseArg | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Základní argument pro aplikaci limitu |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Element limitu |

### Návratová hodnota

nový matematický limit

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* třída [IMathLimit](../../imathlimit/)
* třída [IMathElement](../../imathelement/)
* třída [IMathLimitFactory](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)