---
title: SetColumnAlignment()
second_title: Aspose.Slides voor C++ API-referentie
description: Stel de horizontale uitlijning van de opgegeven kolom in
type: docs
weight: 261
url: /nl/aspose.slides.mathtext/mathmatrix/setcolumnalignment/
---
## MathMatrix::SetColumnAlignment(int32_t, MathHorizontalAlignment) methode


Stel de horizontale uitlijning van de opgegeven kolom in

```cpp
void Aspose::Slides::MathText::MathMatrix::SetColumnAlignment(int32_t columnIndex, MathHorizontalAlignment val) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| columnIndex | **int32_t** | Nulgebaseerde kolomindex |
| val | [MathHorizontalAlignment](../../mathhorizontalalignment/) | Nieuwe waarde van de horizontale uitlijning van de opgegeven kolom |
## Opmerkingen



Voorbeeld: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->SetColumnAlignment(0, MathHorizontalAlignment::Left);
```

## Zie ook

* Enum [MathHorizontalAlignment](../../mathhorizontalalignment/)
* Klasse [MathMatrix](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)