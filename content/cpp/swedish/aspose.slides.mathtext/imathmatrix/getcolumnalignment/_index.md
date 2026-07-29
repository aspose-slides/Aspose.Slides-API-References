---
title: GetColumnAlignment()
second_title: Aspose.Slides för C++ API-referens
description: Hämta den horisontella justeringen för den angivna kolumnen
type: docs
weight: 235
url: /sv/aspose.slides.mathtext/imathmatrix/getcolumnalignment/
---
## IMathMatrix::GetColumnAlignment(int32_t) method


Hämta den horisontella justeringen för den angivna kolumnen

```cpp
virtual MathHorizontalAlignment Aspose::Slides::MathText::IMathMatrix::GetColumnAlignment(int32_t columnIndex)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| columnIndex | **int32_t** | Nollbaserat kolumnindex |

### Returvärde

Horisontell justering för angiven kolumn
## Anmärkningar



Exempel: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
auto alignment = matrix->GetColumnAlignment(0);
```

## Se även

* Enum [MathHorizontalAlignment](../../mathhorizontalalignment/)
* Klass [IMathMatrix](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)