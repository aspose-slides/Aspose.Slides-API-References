---
title: SetColumnsAlignment()
second_title: Aspose.Slides för C++ API-referens
description: Ställ in den horisontella justeringen för de angivna kolumnerna
type: docs
weight: 274
url: /sv/aspose.slides.mathtext/mathmatrix/setcolumnsalignment/
---
## MathMatrix::SetColumnsAlignment(int32_t, uint32_t, MathHorizontalAlignment) metod

Ställ in den horisontella justeringen för de angivna kolumnerna

```cpp
void Aspose::Slides::MathText::MathMatrix::SetColumnsAlignment(int32_t columnIndex, uint32_t columnsCount, MathHorizontalAlignment val) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| columnIndex | **int32_t** | Nollbaserat index för den första kolumnen som ska få justeringen |
| columnsCount | **uint32_t** | Antalet kolumner för vilka justeringen ska anges |
| val | [MathHorizontalAlignment](../../mathhorizontalalignment/) | Nytt värde för horisontell justering av den angivna kolumnen |
## Anmärkningar



Exempel: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->SetColumnsAlignment(0, 3, MathHorizontalAlignment::Left);
```

## Se även

* Enum [MathHorizontalAlignment](../../mathhorizontalalignment/)
* Klass [MathMatrix](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)