---
title: InsertColumnBefore()
second_title: Aspose.Slides för C++ API-referens
description: Infoga en ny kolumn före den angivna. Alla element i den nya kolumnen är initialt null.
type: docs
weight: 313
url: /sv/aspose.slides.mathtext/imathmatrix/insertcolumnbefore/
---
## IMathMatrix::InsertColumnBefore(int32_t) metod

Infoga en ny kolumn före den angivna. Alla element i den nya kolumnen är initialt null.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertColumnBefore(int32_t columnIndex)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| columnIndex | **int32_t** | Index för kolumnen före vilken en ny ska infogas |

## Anmärkningar

Exempel: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertColumnBefore(0);
```

## Se även

* Klass [IMathMatrix](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)