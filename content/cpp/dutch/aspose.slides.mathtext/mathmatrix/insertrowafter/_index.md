---
title: InsertRowAfter()
second_title: Aspose.Slides voor C++ API-referentie
description: Voeg een nieuwe rij toe na de opgegeven rij. Aanvankelijk zijn alle elementen in de nieuwe rij null.
type: docs
weight: 300
url: /nl/aspose.slides.mathtext/mathmatrix/insertrowafter/
---
## MathMatrix::InsertRowAfter(int32_t) methode

Voeg een nieuwe rij toe na de opgegeven rij. Aanvankelijk zijn alle elementen in de nieuwe rij null.

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertRowAfter(int32_t rowIndex) override
```

### Arguments

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rowIndex | **int32_t** | Index van de rij waarna een nieuwe moet worden ingevoegd |
## Opmerkingen



Voorbeeld: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertRowAfter(1);
```

## Zie ook

* Klasse [MathMatrix](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)