---
title: IDataLabelFormat
second_title: Referencia de API de Aspose.Slides para C++
description: Representa opciones de formato para DataLabel.
type: docs
weight: 963
url: /es/aspose.slides.charts/idatalabelformat/
---
## IDataLabelFormat clase

Representa opciones de formato para [DataLabel](../datalabel/).

```cpp
class IDataLabelFormat : public Aspose::Slides::Charts::IFormattedTextContainer
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor al estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aun cuando, según IEC 60559:1989, NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aun cuando, según IEC 60559:1989, NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para propósitos internos. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Devuelve el gráfico. Solo lectura [IChart](../ichart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | Representa el formato de la etiqueta de datos. Solo lectura [IFormat](../iformat/). |
| virtual **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() | Lectura **bool**. |
| virtual [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() | Representa la cadena de formato para el objeto DataLabels. Lectura [System::String](../../system/string/). |
| virtual [LegendDataLabelPosition](../legenddatalabelposition/) [get_Position](./get_position/)() | Representa la posición de la etiqueta de datos. Lectura [LegendDataLabelPosition](../legenddatalabelposition/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Devuelve la presentación. Solo lectura [IPresentation](../../aspose.slides/ipresentation/). |
| virtual [System::String](../../system/string/) [get_Separator](./get_separator/)() | Establece o devuelve un Variant que representa el separador usado para las etiquetas de datos en un gráfico. Lectura [System::String](../../system/string/). |
| virtual **bool** [get_ShowBubbleSize](./get_showbubblesize/)() | Representa el comportamiento de visualización del valor del tamaño de burbuja de la etiqueta de datos de un gráfico especificado. True muestra el valor del tamaño de burbuja. False lo oculta. Lectura **bool**. |
| virtual **bool** [get_ShowCategoryName](./get_showcategoryname/)() | Representa el comportamiento de visualización del nombre de categoría de la etiqueta de datos de un gráfico especificado. True muestra el nombre de categoría. False lo oculta. Lectura **bool**. |
| virtual **bool** [get_ShowLabelAsDataCallout](./get_showlabelasdatacallout/)() | Determina si la etiqueta de datos de un gráfico especificado se mostrará como una llamada de datos o como una etiqueta de datos. |
| virtual **bool** [get_ShowLabelValueFromCell](./get_showlabelvaluefromcell/)() | Representa el comportamiento de visualización del valor de la celda de la etiqueta de datos de un gráfico especificado. True muestra el valor de la celda. False lo oculta. Lectura **bool**. |
| virtual **bool** [get_ShowLeaderLines](./get_showleaderlines/)() | Representa el comportamiento de visualización de las líneas guía de la etiqueta de datos de un gráfico especificado. True muestra las líneas guía. False las oculta. Lectura **bool**. |
| virtual **bool** [get_ShowLegendKey](./get_showlegendkey/)() | Representa el comportamiento de visualización de la clave de leyenda de la etiqueta de datos de un gráfico especificado. True si la clave de leyenda es visible. Lectura **bool**. |
| virtual **bool** [get_ShowPercentage](./get_showpercentage/)() | Representa el comportamiento de visualización del valor de porcentaje de la etiqueta de datos de un gráfico especificado. True muestra el valor de porcentaje. False lo oculta. Lectura **bool**. |
| virtual **bool** [get_ShowSeriesName](./get_showseriesname/)() | Devuelve un Boolean para indicar el comportamiento de visualización del nombre de serie para las etiquetas de datos en un gráfico. True muestra el nombre de serie. False lo oculta. Lectura **bool**. |
| virtual **bool** [get_ShowValue](./get_showvalue/)() | Representa el comportamiento de visualización del valor de porcentaje de la etiqueta de datos de un gráfico especificado. True muestra el valor de porcentaje. False lo oculta. Lectura **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Devuelve la diapositiva base. Solo lectura [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | Devuelve el formato de texto del gráfico. Solo lectura [IChartTextFormat](../icharttextformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo del método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite generar hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Análogo de la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Análogo del operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la sentencia C# lock(). Llame directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo del método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. No copia nada, en realidad, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. No copia nada, en realidad, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| virtual void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) | Escribe **bool**. |
| virtual void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) | Representa la cadena de formato para el objeto DataLabels. Escritura [System::String](../../system/string/). |
| virtual void [set_Position](./set_position/)([LegendDataLabelPosition](../legenddatalabelposition/)) | Representa la posición de la etiqueta de datos. Escritura [LegendDataLabelPosition](../legenddatalabelposition/). |
| virtual void [set_Separator](./set_separator/)([System::String](../../system/string/)) | Establece o devuelve un Variant que representa el separador usado para las etiquetas de datos en un gráfico. Escritura [System::String](../../system/string/). |
| virtual void [set_ShowBubbleSize](./set_showbubblesize/)(**bool**) | Representa el comportamiento de visualización del valor del tamaño de burbuja de la etiqueta de datos de un gráfico especificado. True muestra el valor del tamaño de burbuja. False lo oculta. Escribe **bool**. |
| virtual void [set_ShowCategoryName](./set_showcategoryname/)(**bool**) | Representa el comportamiento de visualización del nombre de categoría de la etiqueta de datos de un gráfico especificado. True muestra el nombre de categoría. False lo oculta. Escribe **bool**. |
| virtual void [set_ShowLabelAsDataCallout](./set_showlabelasdatacallout/)(**bool**) | Determina si la etiqueta de datos de un gráfico especificado se mostrará como una llamada de datos o como una etiqueta de datos. |
| virtual void [set_ShowLabelValueFromCell](./set_showlabelvaluefromcell/)(**bool**) | Representa el comportamiento de visualización del valor de la celda de la etiqueta de datos de un gráfico especificado. True muestra el valor de la celda. False lo oculta. Escribe **bool**. |
| virtual void [set_ShowLeaderLines](./set_showleaderlines/)(**bool**) | Representa el comportamiento de visualización de las líneas guía de la etiqueta de datos de un gráfico especificado. True muestra las líneas guía. False las oculta. Escribe **bool**. |
| virtual void [set_ShowLegendKey](./set_showlegendkey/)(**bool**) | Representa el comportamiento de visualización de la clave de leyenda de la etiqueta de datos de un gráfico especificado. True si la clave de leyenda es visible. Escribe **bool**. |
| virtual void [set_ShowPercentage](./set_showpercentage/)(**bool**) | Representa el comportamiento de visualización del valor de porcentaje de la etiqueta de datos de un gráfico especificado. True muestra el valor de porcentaje. False lo oculta. Escribe **bool**. |
| virtual void [set_ShowSeriesName](./set_showseriesname/)(**bool**) | Establece un Boolean para indicar el comportamiento de visualización del nombre de serie para las etiquetas de datos en un gráfico. True muestra el nombre de serie. False lo oculta. Escribe **bool**. |
| virtual void [set_ShowValue](./set_showvalue/)(**bool**) | Representa el comportamiento de visualización del valor de porcentaje de la etiqueta de datos de un gráfico especificado. True muestra el valor de porcentaje. False lo oculta. Escribe **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como un puntero débil (en lugar de compartido). Permite cambiar punteros en contenedores a modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo del método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la sentencia C# lock(). Llame directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |

## Ver también

* Clase [IFormattedTextContainer](../iformattedtextcontainer/)
* Espacio de nombres [Aspose::Slides::Charts](../)
* Biblioteca [Aspose.Slides](../../)