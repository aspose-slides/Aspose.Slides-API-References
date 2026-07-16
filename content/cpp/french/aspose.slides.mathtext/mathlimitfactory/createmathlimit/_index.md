---
title: CreateMathLimit()
second_title: Référence de l'API Aspose.Slides for C++
description: Crée IMathLimit
type: docs
weight: 1
url: /fr/aspose.slides.mathtext/mathlimitfactory/createmathlimit/
---
## MathLimitFactory::CreateMathLimit(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, bool) méthode

Crée [IMathLimit](../../imathlimit/)

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathLimitFactory::CreateMathLimit(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> limit, bool upperLimit) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| baseArg | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Argument de base auquel appliquer la limite |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Élément de limite |
| upperLimit | **bool** | Définit le placement de la limite en haut |

### Valeur de retour

nouvelle limite mathématique

## MathLimitFactory::CreateMathLimit(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) méthode

Crée [IMathLimit](../../imathlimit/) avec la limite en bas

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathLimitFactory::CreateMathLimit(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> limit) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| baseArg | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Argument de base auquel appliquer la limite |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Élément de limite |

### Valeur de retour

nouvelle limite mathématique

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathLimit](../../imathlimit/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathLimitFactory](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)