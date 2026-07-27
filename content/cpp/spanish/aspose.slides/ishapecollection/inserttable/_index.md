---
title: InsertTable()
second_title: Aspose.Slides para C++ Referencia de la API
description: Crea una tabla nueva y la inserta en la colección de formas en el índice especificado.
type: docs
weight: 443
url: /es/aspose.slides/ishapecollection/inserttable/
---
## IShapeCollection::InsertTable(int32_t, float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) método

Crea una nueva tabla y la inserta en la colección de formas en el índice especificado.

```cpp
virtual System::SharedPtr<ITable> Aspose::Slides::IShapeCollection::InsertTable(int32_t index, float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | **int32_t** | El índice basado en cero en el que se inserta la tabla. |
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
* Clase [IShapeCollection](../)
* Espacio de nombres [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)