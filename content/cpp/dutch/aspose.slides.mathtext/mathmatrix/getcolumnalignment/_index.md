---
title: GetColumnAlignment()
second_title: Aspose.Slides voor C++ API-referentie
description: Haal de horizontale uitlijning van de opgegeven kolom op
type: docs
weight: 248
url: /nl/aspose.slides.mathtext/mathmatrix/getcolumnalignment/
---
## MathMatrix::GetColumnAlignment(int32_t) methode


Haal de horizontale uitlijning van de opgegeven kolom op

```cpp
MathHorizontalAlignment Aspose::Slides::MathText::MathMatrix::GetColumnAlignment(int32_t columnIndex) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| columnIndex | **int32_t** | Nulgebaseerde kolomindex |

### Retourwaarde

Horizontale uitlijning van opgegeven kolom
## Opmerkingen



Voorbeeld: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
auto alignment = matrix->GetColumnAlignment(0);
```

## Zie ook

* Enum [MathHorizontalAlignment](../../mathhorizontalalignment/)
* Klasse [MathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)