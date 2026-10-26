---
title: InsertColumnBefore()
second_title: Aspose.Slides voor C++ API-referentie
description: Voeg een nieuwe kolom in vóór de opgegeven kolom. Initieel zijn alle elementen in de nieuwe kolom null.
type: docs
weight: 313
url: /nl/aspose.slides.mathtext/imathmatrix/insertcolumnbefore/
---
## IMathMatrix::InsertColumnBefore(int32_t) methode


Voeg een nieuwe kolom in vóór de opgegeven kolom. Standaard zijn alle elementen in de nieuwe kolom null.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertColumnBefore(int32_t columnIndex)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| columnIndex | **int32_t** | Index van de kolom vóór welke een nieuwe kolom moet worden ingevoegd |
## Opmerkingen



Voorbeeld: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertColumnBefore(0);
```

## Zie ook

* Klasse [IMathMatrix](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)