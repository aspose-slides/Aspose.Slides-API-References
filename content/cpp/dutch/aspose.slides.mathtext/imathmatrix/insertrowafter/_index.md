---
title: InsertRowAfter()
second_title: Aspose.Slides voor C++ API-referentie
description: Voeg een nieuwe rij toe na de opgegeven rij. In eerste instantie zijn alle elementen in de nieuwe rij null.
type: docs
weight: 287
url: /nl/aspose.slides.mathtext/imathmatrix/insertrowafter/
---
## IMathMatrix::InsertRowAfter(int32_t) methode

Voeg een nieuwe rij toe na de opgegeven rij. In eerste instantie zijn alle elementen in de nieuwe rij null.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertRowAfter(int32_t rowIndex)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rowIndex | **int32_t** | Index van de rij waarna een nieuw moet worden ingevoegd |
## Opmerkingen



Voorbeeld: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertRowAfter(1);
```

## Zie ook

* Klasse [IMathMatrix](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)