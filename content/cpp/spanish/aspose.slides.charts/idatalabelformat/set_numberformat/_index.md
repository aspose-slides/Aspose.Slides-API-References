---
title: set_NumberFormat()
second_title: Referencia de API de Aspose.Slides para C++
description: "Representa la cadena de formato para el objeto DataLabels. Escriba System::String."
type: docs
weight: 40
url: /es/aspose.slides.charts/idatalabelformat/set_numberformat/
---
## IDataLabelFormat::set_NumberFormat(System::String) método

Representa la cadena de formato para el objeto DataLabels. Escriba [System::String](../../../system/string/).

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_NumberFormat(System::String value)=0
```

## Observaciones



```cpp
auto defaultDataLabelFormat = series->get_Labels()->get_DefaultDataLabelFormat();
defaultDataLabelFormat->set_ShowValue(true);
defaultDataLabelFormat->set_IsNumberFormatLinkedToSource(false);
defaultDataLabelFormat->set_NumberFormat(u"0.0%");
```





Si el elemento principal de este [DataLabelFormat](../../datalabelformat/) objeto es una colección [DataLabelCollection](../../datalabelcollection/) de etiquetas de datos, entonces esta propiedad obtiene o establece el valor predeterminado de la propiedad NumberFormat para las nuevas etiquetas de datos en la colección [DataLabelCollection](../../datalabelcollection/). Cuando esta propiedad se establece con un valor, ese valor también se establece para la propiedad NumberFormat de todas las etiquetas de datos en la colección [DataLabelCollection](../../datalabelcollection/) (es decir, "DataLabels.DefaultDataLabelFormat.NumberFormat = val;" hace que todas las etiquetas DataLabels[i].NumberFormat sean iguales a val). 
## Ver también

* Clase [String](../../../system/string/)
* Clase [IDataLabelFormat](../)
* Espacio de nombres [Aspose::Slides::Charts](../../)
* Biblioteca [Aspose.Slides](../../../)