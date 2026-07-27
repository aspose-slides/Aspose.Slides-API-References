---
title: SetColumnsAlignment()
second_title: Referencia de API de Aspose.Slides para C++
description: Establece la alineación horizontal de las columnas especificadas
type: docs
weight: 274
url: /es/aspose.slides.mathtext/mathmatrix/setcolumnsalignment/
---
## MathMatrix::SetColumnsAlignment(int32_t, uint32_t, MathHorizontalAlignment) método

Establece la alineación horizontal de las columnas especificadas

```cpp
void Aspose::Slides::MathText::MathMatrix::SetColumnsAlignment(int32_t columnIndex, uint32_t columnsCount, MathHorizontalAlignment val) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| columnIndex | **int32_t** | Índice basado en cero de la primera columna a la que se le establece la alineación |
| columnsCount | **uint32_t** | Número de columnas para las que se especifica la alineación |
| val | [MathHorizontalAlignment](../../mathhorizontalalignment/) | Nuevo valor de la alineación horizontal de la columna especificada |
## Comentarios



Ejemplo: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->SetColumnsAlignment(0, 3, MathHorizontalAlignment::Left);
```

## Ver también

* Enum [MathHorizontalAlignment](../../mathhorizontalalignment/)
* Class [MathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)