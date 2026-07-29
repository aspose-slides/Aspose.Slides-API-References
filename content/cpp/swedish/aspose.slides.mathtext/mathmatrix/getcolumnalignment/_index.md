---
title: GetColumnAlignment()
second_title: Aspose.Slides för C++ API-referens
description: Hämta den horisontella justeringen för den angivna kolumnen
type: docs
weight: 248
url: /sv/aspose.slides.mathtext/mathmatrix/getcolumnalignment/
---
## MathMatrix::GetColumnAlignment(int32_t) metod


Hämta den horisontella justeringen för den angivna kolumnen

```cpp
MathHorizontalAlignment Aspose::Slides::MathText::MathMatrix::GetColumnAlignment(int32_t columnIndex) override
```

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | **int32_t** | Nollbaserat kolumnindex |

### Returvärde

Horisontell justering av angiven kolumn
## Anmärkningar



Exempel: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
auto alignment = matrix->GetColumnAlignment(0);
```

## Se även

* Enum [MathHorizontalAlignment](../../mathhorizontalalignment/)
* klass [MathMatrix](../)
* namnrymd [Aspose::Slides::MathText](../../)
* bibliotek [Aspose.Slides](../../../)