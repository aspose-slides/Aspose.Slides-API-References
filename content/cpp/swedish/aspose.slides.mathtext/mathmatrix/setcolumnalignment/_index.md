---
title: SetColumnAlignment()
second_title: Aspose.Slides för C++ API-referens
description: Ställ in den horisontella justeringen för den angivna kolumnen
type: docs
weight: 261
url: /sv/aspose.slides.mathtext/mathmatrix/setcolumnalignment/
---
## MathMatrix::SetColumnAlignment(int32_t, MathHorizontalAlignment) metod

Ställ in den horisontella justeringen för den angivna kolumnen

```cpp
void Aspose::Slides::MathText::MathMatrix::SetColumnAlignment(int32_t columnIndex, MathHorizontalAlignment val) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| columnIndex | **int32_t** | Nollbaserat kolumnindex |
| val | [MathHorizontalAlignment](../../mathhorizontalalignment/) | Nytt värde för horisontell justering av angiven kolumn |
## Anmärkningar



Exempel: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->SetColumnAlignment(0, MathHorizontalAlignment::Left);
```

## Se även

* Enum [MathHorizontalAlignment](../../mathhorizontalalignment/)
* Klass [MathMatrix](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)