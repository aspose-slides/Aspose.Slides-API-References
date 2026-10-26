---
title: CreateMathRightSubSuperscriptElement()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea un'istanza di IMathRightSubSuperscriptElementFactory
type: docs
weight: 1
url: /it/aspose.slides.mathtext/mathrightsubsuperscriptelementfactory/createmathrightsubsuperscriptelement/
---
## MathRightSubSuperscriptElementFactory::CreateMathRightSubSuperscriptElement(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) metodo

Crea un'istanza di [IMathRightSubSuperscriptElementFactory](../../imathrightsubsuperscriptelementfactory/)

```cpp
System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::MathRightSubSuperscriptElementFactory::CreateMathRightSubSuperscriptElement(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> subScript, System::SharedPtr<IMathElement> superScript) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| baseArg | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Argomento di base a cui applicare gli indici |
| subScript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | indice inferiore destro |
| superScript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | indice superiore destro |

### Valore di ritorno

new [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathRightSubSuperscriptElementFactory](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)