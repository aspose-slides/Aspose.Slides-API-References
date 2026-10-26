---
title: AddTable()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea una nueva tabla y la agrega al final de la colección de formas.
type: docs
weight: 469
url: /es/aspose.slides/shapecollection/addtable/
---
## ShapeCollection::AddTable(float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) method

Crea una tabla nueva y la agrega al final de la colección de formas.

```cpp
System::SharedPtr<ITable> Aspose::Slides::ShapeCollection::AddTable(float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | **float** | La coordenada x de la tabla, en puntos. |
| y | **float** | La coordenada y de la tabla, en puntos. |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Una matriz de dobles que representa los anchos de las columnas de la tabla, en puntos. |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Una matriz de dobles que representa las alturas de las filas de la tabla, en puntos. |

### Valor devuelto

El [ITable](../../itable/) recién creado.

## Observaciones

El siguiente ejemplo muestra cómo agregar una tabla en PowerPoint [Presentation](../../presentation/). 
```cpp
// Instanciar la clase Presentation que representa un archivo PPTX
auto pres = System::MakeObject<Presentation>();
// Acceder a la primera diapositiva
auto slide = pres->get_Slides()->idx_get(0);
// Definir columnas con anchos y filas con alturas
System::ArrayPtr<double> dblCols = System::MakeArray<double>({50, 50, 50});
System::ArrayPtr<double> dblRows = System::MakeArray<double>({50, 30, 30, 30, 30});
// Agregar la forma de tabla a la diapositiva
System::SharedPtr<ITable> table = slide->get_Shapes()->AddTable(100.0f, 50.0f, dblCols, dblRows);
// Establecer el formato de borde para cada celda
for (int32_t row = 0; row < table->get_Rows()->get_Count(); row++)
{
    auto currentRow = table->get_Rows()->idx_get(row);
    for (int32_t col = 0; col < currentRow->get_Count(); col++)
    {
        auto cell = currentRow->idx_get(col);
        auto cellFormat = cell->get_CellFormat();
        cellFormat->get_BorderTop()->get_FillFormat()->set_FillType(FillType::Solid);
        cellFormat->get_BorderTop()->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Red());
        cellFormat->get_BorderTop()->set_Width(5);
        cellFormat->get_BorderBottom()->get_FillFormat()->set_FillType(FillType::Solid);
        cellFormat->get_BorderBottom()->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Red());
        cellFormat->get_BorderBottom()->set_Width(5);
        cellFormat->get_BorderLeft()->get_FillFormat()->set_FillType(FillType::Solid);
        cellFormat->get_BorderLeft()->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Red());
        cellFormat->get_BorderLeft()->set_Width(5);
        cellFormat->get_BorderRight()->get_FillFormat()->set_FillType(FillType::Solid);
        cellFormat->get_BorderRight()->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Red());
        cellFormat->get_BorderRight()->set_Width(5);
    }
}

// Fusionar las celdas 1 y 2 de la fila 1
table->MergeCells(table->get_Rows()->idx_get(0)->idx_get(0), table->get_Rows()->idx_get(1)->idx_get(1), false);
// Añadir texto a la celda fusionada
table->get_Rows()->idx_get(0)->idx_get(0)->get_TextFrame()->set_Text(u"Merged Cells");
// Guardar el PPTX en el disco
pres->Save(u"table.pptx", SaveFormat::Pptx);
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [ITable](../../itable/)
* Clase [ShapeCollection](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)