---
title: AddTable()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea una tabla nueva y la agrega al final de la colección de formas.
type: docs
weight: 430
url: /es/aspose.slides/ishapecollection/addtable/
---
## IShapeCollection::AddTable(float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) método

Crea una tabla nueva y la agrega al final de la colección de formas.

```cpp
virtual System::SharedPtr<ITable> Aspose::Slides::IShapeCollection::AddTable(float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | **float** | La coordenada x de la tabla, en puntos. |
| y | **float** | La coordenada y de la tabla, en puntos. |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Una matriz de double que representa los anchos de las columnas de la tabla, en puntos. |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Una matriz de double que representa las alturas de las filas de la tabla, en puntos. |

### Valor devuelto

El [ITable](../../itable/) recién creado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [ITable](../../itable/)
* Clase [IShapeCollection](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)