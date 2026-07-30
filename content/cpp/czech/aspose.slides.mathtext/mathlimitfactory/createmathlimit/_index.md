---
title: CreateMathLimit()
second_title: Aspose.Slides pro C++ API referenci
description: Vytváří IMathLimit
type: docs
weight: 1
url: /cs/aspose.slides.mathtext/mathlimitfactory/createmathlimit/
---
## MathLimitFactory::CreateMathLimit(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, bool) metoda

Vytváří [IMathLimit](../../imathlimit/)

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathLimitFactory::CreateMathLimit(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> limit, bool upperLimit) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| baseArg | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Základní argument pro aplikaci limitu |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Element limitu |
| upperLimit | **bool** | Nastavuje umístění limitu nahoře |

### Návratová hodnota

nový matematický limit

## MathLimitFactory::CreateMathLimit(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) metoda

Vytváří [IMathLimit](../../imathlimit/) s limitem na spodku

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathLimitFactory::CreateMathLimit(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> limit) override
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
* Třída [IMathLimit](../../imathlimit/)
* Třída [IMathElement](../../imathelement/)
* Třída [MathLimitFactory](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)