---
title: InsertRowBefore()
second_title: Aspose.Slides voor C++ API-referentie
description: Voeg een nieuwe rij in vóór de opgegeven rij. Aanvankelijk zijn alle elementen in de nieuwe rij null.
type: docs
weight: 287
url: /nl/aspose.slides.mathtext/mathmatrix/insertrowbefore/
---
## MathMatrix::InsertRowBefore(int32_t) methode

Voeg een nieuwe rij in vóór de opgegeven rij. Alle elementen in de nieuwe rij zijn aanvankelijk null.

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertRowBefore(int32_t rowIndex) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rowIndex | **int32_t** | Index van de rij vóór welke een nieuwe moet worden ingevoegd |
## Opmerkingen



Voorbeeld: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertRowBefore(1);
```

## Zie ook

* Klasse [MathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)