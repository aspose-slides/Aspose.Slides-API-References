---
title: SetColumnsAlignment()
second_title: Aspose.Slides para C++ Referencia de API
description: Establece la alineación horizontal de las columnas especificadas
type: docs
weight: 261
url: /es/aspose.slides.mathtext/imathmatrix/setcolumnsalignment/
---
## IMathMatrix::SetColumnsAlignment(int32_t, uint32_t, MathHorizontalAlignment) método

Establece la alineación horizontal de las columnas especificadas

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::SetColumnsAlignment(int32_t columnIndex, uint32_t columnsCount, MathHorizontalAlignment val)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| columnIndex | **int32_t** | Índice basado en cero de la primera columna a la que se establecerá la alineación |
| columnsCount | **uint32_t** | El número de columnas para especificar la alineación |
| val | [MathHorizontalAlignment](../../mathhorizontalalignment/) | Nuevo valor de la alineación horizontal de la columna especificada |
## Observaciones



Ejemplo: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->SetColumnsAlignment(0, 3, MathHorizontalAlignment::Left);
```

## Ver también

* Enumeración [MathHorizontalAlignment](../../mathhorizontalalignment/)
* Clase [IMathMatrix](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)