---
title: CreateMathLimit()
second_title: Aspose.Slides för C++ API-referens
description: Skapar IMathLimit
type: docs
weight: 1
url: /sv/aspose.slides.mathtext/imathlimitfactory/createmathlimit/
---
## IMathLimitFactory::CreateMathLimit(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, bool) metod

Skapar [IMathLimit](../../imathlimit/)

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathLimitFactory::CreateMathLimit(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> limit, bool upperLimit)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| baseArg | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Basargument för att tillämpa gränsen |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Begränsningselement |
| upperLimit | **bool** | Anger placeringen av begränsningen högst upp |

### Returvärde

ny matematisk gräns

## IMathLimitFactory::CreateMathLimit(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) metod

Skapar [IMathLimit](../../imathlimit/) med begränsning längst ner

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathLimitFactory::CreateMathLimit(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> limit)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| baseArg | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Basargument för att tillämpa gränsen |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Begränsningselement |

### Returvärde

ny matematisk gräns

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IMathLimit](../../imathlimit/)
* Klass [IMathElement](../../imathelement/)
* Klass [IMathLimitFactory](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)