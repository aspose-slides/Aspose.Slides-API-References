---
title: InsertColumnAfter()
second_title: Aspose.Slides för C++ API-referens
description: Infoga en ny kolumn efter den angivna. Initialt är alla element i den nya kolumnen null.
type: docs
weight: 326
url: /sv/aspose.slides.mathtext/imathmatrix/insertcolumnafter/
---
## IMathMatrix::InsertColumnAfter(int32_t) metod


Infoga en ny kolumn efter den angivna. Initialt är alla element i den nya kolumnen null.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertColumnAfter(int32_t columnIndex)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| columnIndex | **int32_t** | Index för kolumnen efter vilken en ny ska infogas |
## Anmärkningar



Exempel: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertColumnAfter(0);
```

## Se även

* Klass [IMathMatrix](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)