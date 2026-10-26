---
title: InsertRowAfter()
second_title: Aspose.Slides för C++ API-referens
description: Infoga en ny rad efter den angivna. Alla element i den nya raden är initialt null.
type: docs
weight: 300
url: /sv/aspose.slides.mathtext/mathmatrix/insertrowafter/
---
## MathMatrix::InsertRowAfter(int32_t) metod

Infoga en ny rad efter den angivna. Alla element i den nya raden är initialt null.

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertRowAfter(int32_t rowIndex) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rowIndex | **int32_t** | Index för raden efter vilken en ny ska infogas |
## Anmärkningar



Exempel: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertRowAfter(1);
```

## Se även

* Klass [MathMatrix](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)