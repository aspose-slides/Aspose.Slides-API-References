---
title: SetColumnAlignment()
second_title: Aspose.Slides för C++ API-referens
description: Ställ in den horisontella justeringen för den angivna kolumnen
type: docs
weight: 248
url: /sv/aspose.slides.mathtext/imathmatrix/setcolumnalignment/
---
## IMathMatrix::SetColumnAlignment(int32_t, MathHorizontalAlignment) method


Ställ in den horisontella justeringen för den angivna kolumnen

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::SetColumnAlignment(int32_t columnIndex, MathHorizontalAlignment val)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| columnIndex | **int32_t** | Nollbaserat kolumnindex |
| val | [MathHorizontalAlignment](../../mathhorizontalalignment/) | Nytt värde för horisontell justering av den angivna kolumnen |
## Anmärkningar



Exempel: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->SetColumnAlignment(0, MathHorizontalAlignment::Left);
```

## Se också

* Enum [MathHorizontalAlignment](../../mathhorizontalalignment/)
* Klass [IMathMatrix](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)