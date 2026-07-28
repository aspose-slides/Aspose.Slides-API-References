---
title: CreateMathLimit()
second_title: Aspose.Slides C++ API referenciája
description: Létrehozza az IMathLimit
type: docs
weight: 1
url: /hu/aspose.slides.mathtext/imathlimitfactory/createmathlimit/
---
## IMathLimitFactory::CreateMathLimit(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, bool) method


Létrehozza [IMathLimit](../../imathlimit/)

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathLimitFactory::CreateMathLimit(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> limit, bool upperLimit)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| baseArg | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Az alap argumentum a korlát alkalmazásához |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Korlát elem |
| upperLimit | **bool** | Beállítja a korlát felső elhelyezését |

### Visszatérési érték

új matematikai határ

## IMathLimitFactory::CreateMathLimit(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) method


Létrehozza [IMathLimit](../../imathlimit/) alul lévő korláttal

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathLimitFactory::CreateMathLimit(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> limit)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| baseArg | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Az alap argumentum a korlát alkalmazásához |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Korlát elem |

### Visszatérési érték

új matematikai határ

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathLimit](../../imathlimit/)
* Osztály [IMathElement](../../imathelement/)
* Osztály [IMathLimitFactory](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)