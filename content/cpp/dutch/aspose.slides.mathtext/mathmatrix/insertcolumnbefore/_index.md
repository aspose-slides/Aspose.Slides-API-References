---
title: InsertColumnBefore()
second_title: Aspose.Slides voor C++ API-referentie
description: Voeg een nieuwe kolom in vóór de opgegeven kolom. Aanvankelijk zijn alle elementen in de nieuwe kolom null.
type: docs
weight: 326
url: /nl/aspose.slides.mathtext/mathmatrix/insertcolumnbefore/
---
## MathMatrix::InsertColumnBefore(int32_t) methode


Voeg een nieuwe kolom in vóór de opgegeven kolom. Aanvankelijk zijn alle elementen in de nieuwe kolom null.

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertColumnBefore(int32_t columnIndex) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| columnIndex | **int32_t** | Index van de kolom vóór welke een nieuwe moet worden ingevoegd |
## Opmerkingen



Voorbeeld: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertColumnBefore(0);
```

## Zie ook

* Klasse [MathMatrix](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)