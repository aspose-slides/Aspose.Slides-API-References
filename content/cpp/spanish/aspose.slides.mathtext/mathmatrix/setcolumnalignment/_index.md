---
title: SetColumnAlignment()
second_title: Referencia de la API de Aspose.Slides para C++
description: Establece la alineación horizontal de la columna especificada
type: docs
weight: 261
url: /es/aspose.slides.mathtext/mathmatrix/setcolumnalignment/
---
## MathMatrix::SetColumnAlignment(int32_t, MathHorizontalAlignment) método

Establece la alineación horizontal de la columna especificada

```cpp
void Aspose::Slides::MathText::MathMatrix::SetColumnAlignment(int32_t columnIndex, MathHorizontalAlignment val) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| columnIndex | **int32_t** | Índice de columna basado en cero |
| val | [MathHorizontalAlignment](../../mathhorizontalalignment/) | Nuevo valor de la alineación horizontal de la columna especificada |
## Observaciones



Ejemplo: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->SetColumnAlignment(0, MathHorizontalAlignment::Left);
```

## Ver también

* Enum [MathHorizontalAlignment](../../mathhorizontalalignment/)
* Clase [MathMatrix](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)