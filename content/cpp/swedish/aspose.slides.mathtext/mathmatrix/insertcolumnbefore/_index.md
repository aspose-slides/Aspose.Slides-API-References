---
title: InsertColumnBefore()
second_title: Aspose.Slides för C++ API-referens
description: Infoga en ny kolumn före den angivna. Initialt är alla element i den nya kolumnen null.
type: docs
weight: 326
url: /sv/aspose.slides.mathtext/mathmatrix/insertcolumnbefore/
---
## MathMatrix::InsertColumnBefore(int32_t) metod


Infoga en ny kolumn före den angivna. Initialt är alla element i den nya kolumnen null.

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertColumnBefore(int32_t columnIndex) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| columnIndex | **int32_t** | Index för kolumnen innan vilken en ny ska infogas |
## Anmärkningar



Exempel: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertColumnBefore(0);
```

## Se även

* Klass [MathMatrix](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)