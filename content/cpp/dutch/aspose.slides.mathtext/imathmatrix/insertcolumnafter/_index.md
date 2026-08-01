---
title: InsertColumnAfter()
second_title: Aspose.Slides voor C++ API-referentie
description: Voeg een nieuwe kolom toe na de opgegeven kolom. Aanvankelijk zijn alle elementen in de nieuwe kolom null.
type: docs
weight: 326
url: /nl/aspose.slides.mathtext/imathmatrix/insertcolumnafter/
---
## IMathMatrix::InsertColumnAfter(int32_t) methode


Voeg een nieuwe kolom in na de opgegeven kolom. Aanvankelijk zijn alle elementen in de nieuwe kolom null.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertColumnAfter(int32_t columnIndex)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| columnIndex | **int32_t** | Index van de kolom waarna een nieuwe moet worden ingevoegd |
## Opmerkingen



Voorbeeld: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertColumnAfter(0);
```

## Zie ook

* Klasse [IMathMatrix](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)