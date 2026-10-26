---
title: SetColumnAlignment()
second_title: Aspose.Slides voor C++ API-referentie
description: Stel de horizontale uitlijning van de opgegeven kolom in
type: docs
weight: 248
url: /nl/aspose.slides.mathtext/imathmatrix/setcolumnalignment/
---
## IMathMatrix::SetColumnAlignment(int32_t, MathHorizontalAlignment) methode


Stel de horizontale uitlijning van de opgegeven kolom in

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::SetColumnAlignment(int32_t columnIndex, MathHorizontalAlignment val)=0
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
* Klasse [IMathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)