---
title: CreateMathLimit()
second_title: Aspose.Slides for C++ API referenciája
description: Létrehozza az IMathLimit-et
type: docs
weight: 1
url: /hu/aspose.slides.mathtext/mathlimitfactory/createmathlimit/
---
## MathLimitFactory::CreateMathLimit(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, bool) metódus

Létrehozza [IMathLimit](../../imathlimit/)

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathLimitFactory::CreateMathLimit(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> limit, bool upperLimit) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| baseArg | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Az alap argumentum a limit alkalmazásához |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Limit elem |
| upperLimit | **bool** | Beállítja a limit elhelyezését felül |

### Visszatérési érték

új matematikai limit

## MathLimitFactory::CreateMathLimit(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) metódus

Létrehozza [IMathLimit](../../imathlimit/) a limit alján

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathLimitFactory::CreateMathLimit(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> limit) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| baseArg | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Az alap argumentum a limit alkalmazásához |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Limit elem |

### Visszatérési érték

új matematikai limit

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathLimit](../../imathlimit/)
* Osztály [IMathElement](../../imathelement/)
* Osztály [MathLimitFactory](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)