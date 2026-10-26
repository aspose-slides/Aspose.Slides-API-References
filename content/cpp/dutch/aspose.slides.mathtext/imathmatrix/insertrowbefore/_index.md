---
title: InsertRowBefore()
second_title: Aspose.Slides voor C++ API-referentie
description: Voegt een nieuwe rij in vóór de opgegeven rij. Aanvankelijk zijn alle elementen in de nieuwe rij null.
type: docs
weight: 274
url: /nl/aspose.slides.mathtext/imathmatrix/insertrowbefore/
---
## IMathMatrix::InsertRowBefore(int32_t) methode


Voeg een nieuwe rij in vóór de opgegeven rij. Aanvankelijk zijn alle elementen in de nieuwe rij null.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertRowBefore(int32_t rowIndex)=0
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

* Klasse [IMathMatrix](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)