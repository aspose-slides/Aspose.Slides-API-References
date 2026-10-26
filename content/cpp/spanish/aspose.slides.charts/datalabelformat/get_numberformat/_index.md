---
title: get_NumberFormat()
second_title: Referencia de la API de Aspose.Slides para C++
description: "Representa la cadena de formato para el objeto DataLabels. Lea System::String."
type: docs
weight: 27
url: /es/aspose.slides.charts/datalabelformat/get_numberformat/
---
## DataLabelFormat::get_NumberFormat() método


Representa la cadena de formato para el objeto DataLabels. Lea [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::Charts::DataLabelFormat::get_NumberFormat() override
```

## Observaciones



```cpp
auto defaultDataLabelFormat = series->get_Labels()->get_DefaultDataLabelFormat();
defaultDataLabelFormat->set_ShowValue(true);
defaultDataLabelFormat->set_IsNumberFormatLinkedToSource(false);
defaultDataLabelFormat->set_NumberFormat(u"0.0%");
```





Si el padre de este objeto [DataLabelFormat](../) es una colección [DataLabelCollection](../../datalabelcollection/) de etiquetas de datos, entonces esta propiedad obtiene o establece el valor predeterminado de la propiedad NumberFormat para las nuevas etiquetas de datos en la colección [DataLabelCollection](../../datalabelcollection/). Cuando esta propiedad se establece con un valor, ese valor también se asigna a la propiedad NumberFormat para todas las etiquetas de datos en la colección [DataLabelCollection](../../datalabelcollection/) (por ejemplo, \"DataLabels.DefaultDataLabelFormat.NumberFormat = val;\" hace que todos DataLabels[i].NumberFormat sean iguales a val). 


## Ver también

* Clase [String](../../../system/string/)
* Clase [DataLabelFormat](../)
* Espacio de nombres [Aspose::Slides::Charts](../../)
* Biblioteca [Aspose.Slides](../../../)