---
title: IChartSeriesGroup
second_title: Referencia de API de Aspose.Slides para C++
description: Representa un grupo de series.
type: docs
weight: 846
url: /es/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup clase

Representa un grupo de series.

```cpp
class IChartSeriesGroup : public Aspose::Slides::Charts::IChartComponent
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica de C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor al estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de coma flotante al estilo C# donde dos NaN se consideran iguales aunque, según IEC 60559:1989, NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de coma flotante al estilo C# donde dos NaN se consideran iguales aunque, según IEC 60559:1989, NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para uso interno. |
| virtual [BubbleSizeRepresentationType](../bubblesizerepresentationtype/) [get_BubbleSizeRepresentation](./get_bubblesizerepresentation/)() | Especifica cómo se representan los valores de tamaño de burbuja en el gráfico de burbujas. Lectura [BubbleSizeRepresentationType](../bubblesizerepresentationtype/). |
| virtual **int32_t** [get_BubbleSizeScale](./get_bubblesizescale/)() | Especifica el factor de escala para el gráfico de burbujas (puede estar entre 0 y 300 por ciento del tamaño predeterminado). Lectura **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Devuelve el gráfico. Solo lectura [IChart](../ichart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [get_ChartSeries](./get_chartseries/)(**int32_t**) | Devuelve la serie del gráfico en el grupo en el índice especificado. |
| virtual **uint8_t** [get_DoughnutHoleSize](./get_doughnutholesize/)() | Especifica el tamaño del agujero en un gráfico de dona (puede estar entre 10 y 90 por ciento del tamaño del área de trazado). Lectura **uint8_t**. |
| virtual **uint16_t** [get_FirstSliceAngle](./get_firstsliceangle/)() | Obtiene el ángulo de la primera porción de pastel o dona, en grados (en sentido horario desde arriba, de 0 a 360 grados). Lectura **uint16_t**. |
| virtual **uint16_t** [get_GapDepth](./get_gapdepth/)() | Devuelve la distancia, como porcentaje del ancho del marcador, entre las series de datos en un gráfico 3D. Lectura **uint16_t**. |
| virtual **uint16_t** [get_GapWidth](./get_gapwidth/)() | Especifica el espacio entre grupos de barras o columnas, como porcentaje del ancho de la barra o columna. Lectura **uint16_t**. |
| virtual **bool** [get_HasSeriesLines](./get_hasserieslines/)() | True si el gráfico tiene líneas de serie. Aplicado a gráficos de barras apiladas y OfPie. Lectura **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_HiLowLinesFormat](./get_hilowlinesformat/)() | Especifica el formato HiLowLines. HiLowLines se aplica con los tipos de gráfico HiLowClose, OpenHiLowClose, VolumeHiLowClose y VolumeOpenHiLowClose. |
| virtual **bool** [get_IsColorVaried](./get_iscolorvaried/)() | Especifica que cada marcador de datos en la serie tiene un color diferente. Lectura **bool**. |
| virtual **int8_t** [get_Overlap](./get_overlap/)() | Especifica cuánto se superponen las barras y columnas en gráficos 2D, como porcentaje (de -100% a 100%). |
| virtual [PieSplitType](../piesplittype/) [get_PieSplitBy](./get_piesplitby/)() | Especifica cómo determinar qué puntos de datos están en el segundo pastel o barra en un gráfico de pastel-sobre-pastel o barra-sobre-pastel. Lectura [PieSplitType](../piesplittype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\> [get_PieSplitCustomPoint](./get_piesplitcustompoint/)(**int32_t**) | La información de división personalizada para un gráfico de pastel-sobre-pastel o barra-sobre-pastel con una división personalizada. Devuelve el punto de datos que debe dibujarse en el segundo pastel o barra en un gráfico de pastel-sobre-pastel o barra-sobre-pastel por índice. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPieSplitCustomPointCollection](../ipiesplitcustompointcollection/)\> [get_PieSplitCustomPoints](./get_piesplitcustompoints/)() | La información de división personalizada para un gráfico de pastel-sobre-pastel o barra-sobre-pastel con una división personalizada. Contiene los puntos de datos que deben dibujarse en el segundo pastel o barra en un gráfico de pastel-sobre-pastel o barra-sobre-pastel. Solo lectura [IPieSplitCustomPointCollection](../ipiesplitcustompointcollection/). |
| virtual **double** [get_PieSplitPosition](./get_piesplitposition/)() | Especifica un valor que debe usarse para determinar qué puntos de datos están en el segundo pastel o barra en un gráfico de pastel-sobre-pastel o barra-sobre-pastel. Se usa junto con la propiedad PieSplitBy. Lectura **double**. |
| virtual **bool** [get_PlotOnSecondAxis](./get_plotonsecondaxis/)() | Indica si la serie de este grupo se representa en el eje secundario. Solo lectura **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Devuelve la presentación. Solo lectura [IPresentation](../../aspose.slides/ipresentation/). |
| virtual **uint16_t** [get_SecondPieSize](./get_secondpiesize/)() | Especifica el tamaño del segundo pastel o barra de un gráfico de pastel-sobre-pastel o barra-sobre-pastel, como porcentaje del tamaño del primer pastel (puede estar entre 5 y 200 por ciento). Lectura **uint16_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/)\> [get_Series](./get_series/)() | Devuelve una colección de solo lectura de series del gráfico. Solo lectura [IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Devuelve la diapositiva base. Solo lectura [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [CombinableSeriesTypesGroup](../combinableseriestypesgroup/) [get_Type](./get_type/)() | Devuelve el tipo de este grupo de series. Solo lectura [CombinableSeriesTypesGroup](../combinableseriestypesgroup/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IUpDownBarsManager](../iupdownbarsmanager/)\> [get_UpDownBars](./get_updownbars/)() | Proporciona acceso a las barras superiores/inferiores de un gráfico de líneas o de acciones. Solo lectura [IUpDownBarsManager](../iupdownbarsmanager/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo al método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Análogo a la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [idx_get](./idx_get/)(**int32_t**) | Obtiene el elemento en el índice especificado. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Análogo al operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la sentencia C# lock(). Llámese directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo al método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. Realmente no copia nada, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. Realmente no copia nada, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| virtual void [set_BubbleSizeRepresentation](./set_bubblesizerepresentation/)([BubbleSizeRepresentationType](../bubblesizerepresentationtype/)) | Especifica cómo se representan los valores de tamaño de burbuja en el gráfico de burbujas. Escritura [BubbleSizeRepresentationType](../bubblesizerepresentationtype/). |
| virtual void [set_BubbleSizeScale](./set_bubblesizescale/)(**int32_t**) | Especifica el factor de escala para el gráfico de burbujas (puede estar entre 0 y 300 por ciento del tamaño predeterminado). Escritura **int32_t**. |
| virtual void [set_DoughnutHoleSize](./set_doughnutholesize/)(**uint8_t**) | Especifica el tamaño del agujero en un gráfico de dona (puede estar entre 10 y 90 por ciento del tamaño del área de trazado). Escritura **uint8_t**. |
| virtual void [set_FirstSliceAngle](./set_firstsliceangle/)(**uint16_t**) | Establece el ángulo de la primera porción de pastel o dona, en grados (en sentido horario desde arriba, de 0 a 360 grados). Escritura **uint16_t**. |
| virtual void [set_GapDepth](./set_gapdepth/)(**uint16_t**) | Establece la distancia, como porcentaje del ancho del marcador, entre las series de datos en un gráfico 3D. Escritura **uint16_t**. |
| virtual void [set_GapWidth](./set_gapwidth/)(**uint16_t**) | Especifica el espacio entre grupos de barras o columnas, como porcentaje del ancho de la barra o columna. Escritura **uint16_t**. |
| virtual void [set_HasSeriesLines](./set_hasserieslines/)(**bool**) | True si el gráfico tiene líneas de serie. Aplicado a gráficos de barras apiladas y OfPie. Escritura **bool**. |
| virtual void [set_IsColorVaried](./set_iscolorvaried/)(**bool**) | Especifica que cada marcador de datos en la serie tiene un color diferente. Escritura **bool**. |
| virtual void [set_Overlap](./set_overlap/)(**int8_t**) | Especifica cuánto se superponen las barras y columnas en gráficos 2D, como porcentaje (de -100% a 100%). |
| virtual void [set_PieSplitBy](./set_piesplitby/)([PieSplitType](../piesplittype/)) | Especifica cómo determinar qué puntos de datos están en el segundo pastel o barra en un gráfico de pastel-sobre-pastel o barra-sobre-pastel. Escritura [PieSplitType](../piesplittype/). |
| virtual void [set_PieSplitPosition](./set_piesplitposition/)(**double**) | Especifica un valor que debe usarse para determinar qué puntos de datos están en el segundo pastel o barra en un gráfico de pastel-sobre-pastel o barra-sobre-pastel. Se usa junto con la propiedad PieSplitBy. Escritura **double**. |
| virtual void [set_SecondPieSize](./set_secondpiesize/)(**uint16_t**) | Especifica el tamaño del segundo pastel o barra de un gráfico de pastel-sobre-pastel o barra-sobre-pastel, como porcentaje del tamaño del primer pastel (puede estar entre 5 y 200 por ciento). Escritura **uint16_t**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como un puntero débil (en lugar de compartido). Permite cambiar los punteros en contenedores a modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo al método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la sentencia C# lock(). Llámese directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |

## Observaciones

1) Consulte el resumen y las observaciones de la clase ChartSeriesGroupCollection y del enum CombinableSeriesTypesGroup. 2) El grupo de series contiene algunas propiedades de series que son comunes a cada serie en el grupo ("propiedades del grupo de series"). Las "propiedades del grupo de series" en la clase [ChartSeriesGroup](../chartseriesgroup/) son lectura/escritura. Cada una de las "propiedades del grupo de series" puede tener una proyección de solo lectura en la clase [ChartSeries](../chartseries/).

## Véase también

* Clase [IChartComponent](../ichartcomponent/)
* Espacio de nombres [Aspose::Slides::Charts](../)
* Biblioteca [Aspose.Slides](../../)