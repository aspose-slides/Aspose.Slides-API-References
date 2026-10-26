---
title: ChartSeriesGroup
second_title: Referencia de API de Aspose.Slides para C++
description: Representa un grupo de series.
type: docs
weight: 300
url: /es/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup clase

Representa un grupo de series.

```cpp
class ChartSeriesGroup : public Aspose::Slides::Charts::IChartSeriesGroup,
                         public Aspose::Slides::IDOMObject
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica de C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor al estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para uso interno. |
| [BubbleSizeRepresentationType](../bubblesizerepresentationtype/) [get_BubbleSizeRepresentation](./get_bubblesizerepresentation/)() override | Especifica cómo se representan los valores del tamaño de las burbujas en el gráfico de burbujas. Lea [BubbleSizeRepresentationType](../bubblesizerepresentationtype/). |
| **int32_t** [get_BubbleSizeScale](./get_bubblesizescale/)() override | Especifica el factor de escala para el gráfico de burbujas (puede estar entre 0 y 300 por ciento del tamaño predeterminado). Lea **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Devuelve el gráfico padre. Solo lectura [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [get_ChartSeries](./get_chartseries/)(**int32_t**) override | Devuelve la serie de gráfico en el grupo en el índice especificado. |
| **uint8_t** [get_DoughnutHoleSize](./get_doughnutholesize/)() override | Especifica el tamaño del agujero en un gráfico de dona (puede estar entre 0 y 90 por ciento del tamaño del área de trazado). Lea **uint8_t**. |
| **uint16_t** [get_FirstSliceAngle](./get_firstsliceangle/)() override | Obtiene el ángulo de la primera porción del gráfico de pastel o dona, en grados (en sentido horario desde arriba, de 0 a 360 grados). Lea **uint16_t**. |
| **uint16_t** [get_GapDepth](./get_gapdepth/)() override | Devuelve la distancia, como porcentaje del ancho del marcador, entre las series de datos en un gráfico 3D. Lea **uint16_t**. |
| **uint16_t** [get_GapWidth](./get_gapwidth/)() override | Especifica el espacio entre grupos de barras o columnas, como porcentaje del ancho de la barra o columna. Lea **uint16_t**. |
| **bool** [get_HasSeriesLines](./get_hasserieslines/)() override | Verdadero si el gráfico tiene líneas de serie. Aplicado a gráficos de barras apiladas y OfPie. Lea **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_HiLowLinesFormat](./get_hilowlinesformat/)() override | Especifica el formato HiLowLines. HiLowLines se aplica con los tipos de gráfico HiLowClose, OpenHiLowClose, VolumeHiLowClose y VolumeOpenHiLowClose. |
| **bool** [get_IsColorVaried](./get_iscolorvaried/)() override | Especifica que cada marcador de datos en la serie tiene un color diferente. Lea **bool**. |
| **int8_t** [get_Overlap](./get_overlap/)() override | Especifica cuánto se superponen las barras y columnas en gráficos 2D, como porcentaje (de -100% a 100%). |
| [PieSplitType](../piesplittype/) [get_PieSplitBy](./get_piesplitby/)() override | Especifica cómo determinar qué puntos de datos están en el segundo pastel o barra en un gráfico de pastel-de-pastel o barra-de-pastel. Lea [PieSplitType](../piesplittype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\> [get_PieSplitCustomPoint](./get_piesplitcustompoint/)(**int32_t**) override | La información de división personalizada para un gráfico de pastel-de-pastel o barra-de-pastel con una división personalizada. Devuelve el punto de datos que debe dibujarse en el segundo pastel o barra en un gráfico de pastel-de-pastel o barra-de-pastel por índice. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPieSplitCustomPointCollection](../ipiesplitcustompointcollection/)\> [get_PieSplitCustomPoints](./get_piesplitcustompoints/)() override | La información de división personalizada para un gráfico de pastel-de-pastel o barra-de-pastel con una división personalizada. Contiene los puntos de datos que deben dibujarse en el segundo pastel o barra en un gráfico de pastel-de-pastel o barra-de-pastel. Solo lectura [PieSplitCustomPointCollection](../piesplitcustompointcollection/). |
| **double** [get_PieSplitPosition](./get_piesplitposition/)() override | Especifica un valor que se usará para determinar qué puntos de datos están en el segundo pastel o barra en un gráfico de pastel-de-pastel o barra-de-pastel. Se usa junto con la propiedad PieSplitBy. Lea **double**. |
| **bool** [get_PlotOnSecondAxis](./get_plotonsecondaxis/)() override | Indica si la serie de este grupo se dibuja en el eje secundario. Solo lectura **bool**. |
| **uint16_t** [get_SecondPieSize](./get_secondpiesize/)() override | Especifica el tamaño del segundo pastel o barra de un gráfico de pastel-de-pastel o barra-de-pastel, como porcentaje del tamaño del primer pastel (puede estar entre 5 y 200 por ciento). Lea **uint16_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/)\> [get_Series](./get_series/)() override | Devuelve una colección de series. Solo lectura [IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/). |
| [CombinableSeriesTypesGroup](../combinableseriestypesgroup/) [get_Type](./get_type/)() override | Devuelve un tipo de este grupo de series. Solo lectura [CombinableSeriesTypesGroup](../combinableseriestypesgroup/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IUpDownBarsManager](../iupdownbarsmanager/)\> [get_UpDownBars](./get_updownbars/)() override | Proporciona acceso a barras de subida/bajada de gráfico de línea o de acciones. Solo lectura [IUpDownBarsManager](../iupdownbarsmanager/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo al método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite generar hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Analogo a la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [idx_get](./idx_get/)(**int32_t**) override | Obtiene el elemento en el índice especificado. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Analogo al operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la sentencia C# lock(). Llame directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo al método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. En realidad no copia nada, solo inicializa un nuevo objeto y permite copiar construyendo subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. En realidad no copia nada, solo inicializa un nuevo objeto y permite copiar construyendo subclases. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| void [set_BubbleSizeRepresentation](./set_bubblesizerepresentation/)([BubbleSizeRepresentationType](../bubblesizerepresentationtype/)) override | Especifica cómo se representan los valores de tamaño de burbuja en el gráfico de burbujas. Escriba [BubbleSizeRepresentationType](../bubblesizerepresentationtype/). |
| void [set_BubbleSizeScale](./set_bubblesizescale/)(**int32_t**) override | Especifica el factor de escala para el gráfico de burbujas (puede estar entre 0 y 300 por ciento del tamaño predeterminado). Escriba **int32_t**. |
| void [set_DoughnutHoleSize](./set_doughnutholesize/)(**uint8_t**) override | Especifica el tamaño del agujero en un gráfico de dona (puede estar entre 0 y 90 por ciento del tamaño del área de trazado). Escriba **uint8_t**. |
| void [set_FirstSliceAngle](./set_firstsliceangle/)(**uint16_t**) override | Establece el ángulo de la primera porción del gráfico de pastel o dona, en grados (en sentido horario desde arriba, de 0 a 360 grados). Escriba **uint16_t**. |
| void [set_GapDepth](./set_gapdepth/)(**uint16_t**) override | Establece la distancia, como porcentaje del ancho del marcador, entre las series de datos en un gráfico 3D. Escriba **uint16_t**. |
| void [set_GapWidth](./set_gapwidth/)(**uint16_t**) override | Especifica el espacio entre grupos de barras o columnas, como porcentaje del ancho de la barra o columna. Escriba **uint16_t**. |
| void [set_HasSeriesLines](./set_hasserieslines/)(**bool**) override | Verdadero si el gráfico tiene líneas de serie. Aplicado a gráficos de barras apiladas y OfPie. Escriba **bool**. |
| void [set_IsColorVaried](./set_iscolorvaried/)(**bool**) override | Especifica que cada marcador de datos en la serie tiene un color diferente. Escriba **bool**. |
| void [set_Overlap](./set_overlap/)(**int8_t**) override | Especifica cuánto se superponen las barras y columnas en gráficos 2D, como porcentaje (de -100% a 100%). |
| void [set_PieSplitBy](./set_piesplitby/)([PieSplitType](../piesplittype/)) override | Especifica cómo determinar qué puntos de datos están en el segundo pastel o barra en un gráfico de pastel-de-pastel o barra-de-pastel. Escriba [PieSplitType](../piesplittype/). |
| void [set_PieSplitPosition](./set_piesplitposition/)(**double**) override | Especifica un valor que se usará para determinar qué puntos de datos están en el segundo pastel o barra en un gráfico de pastel-de-pastel o barra-de-pastel. Se usa junto con la propiedad PieSplitBy. Escriba **double**. |
| void [set_SecondPieSize](./set_secondpiesize/)(**uint16_t**) override | Especifica el tamaño del segundo pastel o barra de un gráfico de pastel-de-pastel o barra-de-pastel, como porcentaje del tamaño del primer pastel (puede estar entre 5 y 200 por ciento). Escriba **uint16_t**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como un puntero débil (en lugar de compartido). Permite cambiar punteros en contenedores a modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrece y devuelve el contador de referencias compartidas. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo al método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la sentencia C# lock(). Llame directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrece el contador de referencias débiles. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |

## Observaciones

1) Consulte el resumen y las observaciones de la clase ChartSeriesGroupCollection y el enum CombinableSeriesTypesGroup. 2) El grupo de series contiene algunas propiedades de series que son comunes para cada serie en el grupo ("propiedades del grupo de series"). "Propiedades del grupo de series" en la clase [ChartSeriesGroup](./) es lectura/escritura. Cada una de las "propiedades del grupo de series" puede tener una proyección solo lectura en la clase [ChartSeries](../chartseries/).

## Ver también

* Clase [IChartSeriesGroup](../ichartseriesgroup/)
* Clase [IDOMObject](../../aspose.slides/idomobject/)
* Espacio de nombres [Aspose::Slides::Charts](../)
* Biblioteca [Aspose.Slides](../../)