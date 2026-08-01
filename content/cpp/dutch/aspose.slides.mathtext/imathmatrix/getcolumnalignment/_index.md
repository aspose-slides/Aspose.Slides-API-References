---
title: GetColumnAlignment()
second_title: Aspose.Slides voor C++ API-referentie
description: Haal de horizontale uitlijning van de opgegeven kolom op
type: docs
weight: 235
url: /nl/aspose.slides.mathtext/imathmatrix/getcolumnalignment/
---
## IMathMatrix::GetColumnAlignment(int32_t) methode

Haal de horizontale uitlijning van de opgegeven kolom op

```cpp
virtual MathHorizontalAlignment Aspose::Slides::MathText::IMathMatrix::GetColumnAlignment(int32_t columnIndex)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| columnIndex | **int32_t** | Nulgebaseerde kolomindex |

### Retourwaarde

Horizontale uitlijning van de opgegeven kolom
## Opmerkingen



Voorbeeld: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
auto alignment = matrix->GetColumnAlignment(0);
```

## Zie ook

* Enum [MathHorizontalAlignment](../../mathhorizontalalignment/)
* Klasse [IMathMatrix](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)