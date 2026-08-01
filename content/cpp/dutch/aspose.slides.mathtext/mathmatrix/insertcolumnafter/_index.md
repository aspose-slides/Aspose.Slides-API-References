---
title: InsertColumnAfter()
second_title: Aspose.Slides voor C++ API-referentie
description: Voegt een nieuwe kolom toe na de opgegeven kolom. Aanvankelijk zijn alle elementen in de nieuwe kolom null.
type: docs
weight: 339
url: /nl/aspose.slides.mathtext/mathmatrix/insertcolumnafter/
---
## MathMatrix::InsertColumnAfter(int32_t) method

Voegt een nieuwe kolom toe na de opgegeven kolom. Aanvankelijk zijn alle elementen in de nieuwe kolom null.

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertColumnAfter(int32_t columnIndex) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| columnIndex | **int32_t** | Index van de kolom waarna een nieuwe kolom moet worden ingevoegd |
## Opmerkingen



Voorbeeld: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertColumnAfter(0);
```

## Zie ook

* Klasse [MathMatrix](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)