---
title: GetEffective()
second_title: Referencia de API de Aspose.Slides para C++
description: Obtiene las propiedades de formato de fila de tabla efectivas con herencia y estilos de tabla aplicados.
type: docs
weight: 1
url: /es/aspose.slides/rowformat/geteffective/
---
## RowFormat::GetEffective() método


Obtiene las propiedades de formato de fila de tabla efectivas con herencia y estilos de tabla aplicados.

```cpp
System::SharedPtr<IRowFormatEffectiveData> Aspose::Slides::RowFormat::GetEffective() override
```


### Valor devuelto

Un [IRowFormatEffectiveData](../../irowformateffectivedata/).
## Observaciones



Este ejemplo demuestra cómo obtener el formato de relleno efectivo para diferentes partes lógicas de la tabla. Tenga en cuenta que el formato de celda siempre tiene mayor prioridad que el formato de fila, la fila es mayor que la columna, y la columna es mayor que toda la tabla. Por lo tanto, finalmente se utilizan siempre las propiedades CellFormatEffectiveData para dibujar la tabla. El siguiente código es solo un ejemplo de la API. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto tbl = AsCast<Table>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto tableFillFormatEffective = tbl->get_TableFormat()->GetEffective()->get_FillFormat();
auto rowFillFormatEffective = tbl->get_Rows()->idx_get(0)->get_RowFormat()->GetEffective()->get_FillFormat();
auto columnFillFormatEffective = tbl->get_Columns()->idx_get(0)->get_ColumnFormat()->GetEffective()->get_FillFormat();
auto cellFillFormatEffective = tbl->idx_get(0, 0)->get_CellFormat()->GetEffective()->get_FillFormat();
// Salida y comparación
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IRowFormatEffectiveData](../../irowformateffectivedata/)
* Clase [RowFormat](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)