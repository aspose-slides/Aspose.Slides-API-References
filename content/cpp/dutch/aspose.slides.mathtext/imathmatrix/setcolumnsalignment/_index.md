---
title: SetColumnsAlignment()
second_title: Aspose.Slides voor C++ API-referentie
description: Stel de horizontale uitlijning van de opgegeven kolommen in
type: docs
weight: 261
url: /nl/aspose.slides.mathtext/imathmatrix/setcolumnsalignment/
---
## IMathMatrix::SetColumnsAlignment(int32_t, uint32_t, MathHorizontalAlignment) methode

Stel de horizontale uitlijning van de opgegeven kolommen in

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::SetColumnsAlignment(int32_t columnIndex, uint32_t columnsCount, MathHorizontalAlignment val)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| columnIndex | **int32_t** | Nulgebaseerde index van de eerste kolom waarvoor de uitlijning wordt ingesteld |
| columnsCount | **uint32_t** | Het aantal kolommen waarvoor de uitlijning wordt gespecificeerd |
| val | [MathHorizontalAlignment](../../mathhorizontalalignment/) | Nieuwe waarde van de horizontale uitlijning van de opgegeven kolom |
## Opmerkingen



Voorbeeld: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->SetColumnsAlignment(0, 3, MathHorizontalAlignment::Left);
```

## Zie ook

* Enum [MathHorizontalAlignment](../../mathhorizontalalignment/)
* Klasse [IMathMatrix](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)