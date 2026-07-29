---
title: InsertRowBefore()
second_title: Aspose.Slides för C++ API-referens
description: Infoga en ny rad före den angivna. Alla element i den nya raden är initialt null.
type: docs
weight: 287
url: /sv/aspose.slides.mathtext/mathmatrix/insertrowbefore/
---
## MathMatrix::InsertRowBefore(int32_t) metod


Infoga en ny rad före den angivna. Alla element i den nya raden är initialt null.

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertRowBefore(int32_t rowIndex) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rowIndex | **int32_t** | Index för raden före vilken en ny rad ska infogas |
## Anmärkningar



Exempel: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertRowBefore(1);
```

## Se även

* Klass [MathMatrix](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)