---
title: InsertTable()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea una tabla nueva e inserta la tabla en la colección de formas en el índice especificado.
type: docs
weight: 482
url: /es/aspose.slides/shapecollection/inserttable/
---
## ShapeCollection::InsertTable(int32_t, float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) método


Crea una tabla nueva e inserta la tabla en la colección de formas en el índice especificado.

```cpp
System::SharedPtr<ITable> Aspose::Slides::ShapeCollection::InsertTable(int32_t index, float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | **int32_t** | El índice basado en cero en el que se insertará la tabla. |
| x | **float** | La coordenada x de la tabla, en puntos. |
| y | **float** | La coordenada y de la tabla, en puntos. |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Una matriz de dobles que representa los anchos de las columnas de la tabla, en puntos. |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Una matriz de dobles que representa las alturas de las filas de la tabla, en puntos. |

### Valor de retorno

El [ITable](../../itable/) recién creado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [ITable](../../itable/)
* Clase [ShapeCollection](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)