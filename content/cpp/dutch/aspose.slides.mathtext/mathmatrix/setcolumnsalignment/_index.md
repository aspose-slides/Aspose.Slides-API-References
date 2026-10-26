---
title: SetColumnsAlignment()
second_title: Aspose.Slides voor C++ API-referentie
description: Stel de horizontale uitlijning van de opgegeven kolommen in
type: docs
weight: 274
url: /nl/aspose.slides.mathtext/mathmatrix/setcolumnsalignment/
---
## MathMatrix::SetColumnsAlignment(int32_t, uint32_t, MathHorizontalAlignment) method


Stel de horizontale uitlijning van de opgegeven kolommen in

```cpp
void Aspose::Slides::MathText::MathMatrix::SetColumnsAlignment(int32_t columnIndex, uint32_t columnsCount, MathHorizontalAlignment val) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| columnIndex | **int32_t** | Nulgebaseerde index van de eerste kolom om de uitlijning in te stellen |
| columnsCount | **uint32_t** | Het aantal kolommen waarvoor de uitlijning moet worden opgegeven |
| val | [MathHorizontalAlignment](../../mathhorizontalalignment/) | Nieuwe waarde van de horizontale uitlijning van de opgegeven kolom |
## Opmerkingen



Voorbeeld: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->SetColumnsAlignment(0, 3, MathHorizontalAlignment::Left);
```

## Zie ook

* Enum [MathHorizontalAlignment](../../mathhorizontalalignment/)
* Klasse [MathMatrix](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)