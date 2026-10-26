---
title: set_NumberFormat()
second_title: Referencia de API de Aspose.Slides para C++
description: "Representa la cadena de formato para el objeto DataLabels. Escriba System::String."
type: docs
weight: 40
url: /es/aspose.slides.charts/datalabelformat/set_numberformat/
---
## DataLabelFormat::set_NumberFormat(System::String) method


Representa la cadena de formato para el objeto DataLabels. Escriba [System::String](../../../system/string/).

```cpp
void Aspose::Slides::Charts::DataLabelFormat::set_NumberFormat(System::String value) override
```

## Observaciones



```cpp
auto defaultDataLabelFormat = series->get_Labels()->get_DefaultDataLabelFormat();
defaultDataLabelFormat->set_ShowValue(true);
defaultDataLabelFormat->set_IsNumberFormatLinkedToSource(false);
defaultDataLabelFormat->set_NumberFormat(u"0.0%");
```




Si el padre de este objeto [DataLabelFormat](../) es una colección [DataLabelCollection](../../datalabelcollection/) de etiquetas de datos, entonces esta propiedad obtiene o establece el valor predeterminado de la propiedad NumberFormat para las nuevas etiquetas de datos en la colección [DataLabelCollection](../../datalabelcollection/). Cuando esta propiedad se establece con un valor, ese valor también se asigna a la propiedad NumberFormat para todas las etiquetas de datos en la colección [DataLabelCollection](../../datalabelcollection/) (por ejemplo, "DataLabels.DefaultDataLabelFormat.NumberFormat = val;" hace que todos los DataLabels[i].NumberFormat sean iguales a val). 


## Ver también

* Clase [String](../../../system/string/)
* Clase [DataLabelFormat](../)
* Espacio de nombres [Aspose::Slides::Charts](../../)
* Biblioteca [Aspose.Slides](../../../)