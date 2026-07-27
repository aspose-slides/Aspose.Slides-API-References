---
title: DataLabel
second_title: Referencia de la API de Aspose.Slides para C++
description: Representa las etiquetas de una serie.
type: docs
weight: 365
url: /es/aspose.slides.charts/datalabel/
---
## DataLabel clase

Representa las etiquetas de una serie.

```cpp
class DataLabel : public Aspose::Slides::Charts::IDataLabel,
                  public Aspose::Slides::IDOMObject
```

## Métodos

| Method | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](./addtextframeforoverriding/)([System::String](../../system/string/)) override | Inicializa TextFrameForOverriding con el texto en el parámetro \"text\". Si TextFrameForOverriding ya está inicializado, simplemente cambia su texto. |
|  [DataLabel](./datalabel/)([System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\>) | Crea una nueva instancia de la clase [DataLabel](./). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor al estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C#, donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C#, donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para uso interno. |
| **float** [get_ActualHeight](./get_actualheight/)() override | Especifica la altura real del elemento del gráfico. Llame al método [IChart::ValidateChartLayout](../ichart/validatechartlayout/) antes para obtener los valores reales. Lectura **float**. |
| **float** [get_ActualWidth](./get_actualwidth/)() override | Especifica el ancho real del elemento del gráfico. Llame al método [IChart::ValidateChartLayout](../ichart/validatechartlayout/) antes para obtener los valores reales. Lectura **float**. |
| **float** [get_ActualX](./get_actualx/)() override | Especifica la posición x real (izquierda) del elemento del gráfico relativa a la esquina superior izquierda del gráfico. Llame al método [IChart::ValidateChartLayout](../ichart/validatechartlayout/) antes para obtener los valores reales. Lectura **float**. |
| **float** [get_ActualY](./get_actualy/)() override | Especifica la parte superior real del elemento del gráfico relativa a la esquina superior izquierda del gráfico. Llame al método [IChart::ValidateChartLayout](../ichart/validatechartlayout/) antes para obtener los valores reales. Lectura **float**. |
| **float** [get_Bottom](./get_bottom/)() override | Parte inferior. Sólo lectura **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Devuelve el gráfico padre. Sólo lectura [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IDataLabelFormat](../idatalabelformat/)\> [get_DataLabelFormat](./get_datalabelformat/)() override | Devuelve el formato de etiqueta de datos. Sólo lectura [IDataLabelFormat](../idatalabelformat/). |
| **float** [get_Height](./get_height/)() override | Devuelve la altura de un título como una fracción de la altura del gráfico. Lectura **float**. |
| **bool** [get_IsVisible](./get_isvisible/)() override | False indica que la etiqueta de datos no es visible (y por lo tanto todas las banderas Show* (ShowValue, ...) son falsas). Sólo lectura **bool**. |
| **float** [get_Right](./get_right/)() override | Derecha. Sólo lectura **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | Devuelve el formato de texto. Sólo lectura [IChartTextFormat](../icharttextformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](./get_textframeforoverriding/)() override | Puede contener un texto con formato enriquecido. Si esta propiedad no es nula, entonces este valor de texto con formato sobrescribe el texto autogenerado de la etiqueta de datos. El texto autogenerado de la etiqueta de datos significa el texto gestionado por las propiedades ShowSeriesName, ShowValue, ... y formateado con la propiedad TextFormatManager.TextFormat. Sólo lectura [ITextFrame](../../aspose.slides/itextframe/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\> [get_ValueFromCell](./get_valuefromcell/)() override | Obtiene la celda de datos del libro de trabajo. Se aplica si la propiedad IDataLabelFormat::get(set)_ShowLabelValueFromCell es verdadera. |
| **float** [get_Width](./get_width/)() override | Devuelve el ancho de un título como una fracción del ancho del gráfico. Lectura **float**. |
| **float** [get_X](./get_x/)() override | Devuelve la coordenada x de un título como una fracción del ancho del gráfico. Lectura **float**. |
| **float** [get_Y](./get_y/)() override | Devuelve la coordenada y de un título como una fracción de la altura del gráfico. Lectura **float**. |
| [System::String](../../system/string/) [GetActualLabelText](./getactuallabeltext/)() override | Devuelve el texto real de la etiqueta basado en la configuración [DataLabelFormat](../datalabelformat/) o el valor [get_TextFrameForOverriding()](./get_textframeforoverriding/)->get(set)_Text(). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo al método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite el hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Análogo a la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| void [Hide](./hide/)() override | Oculta la etiqueta de datos estableciendo todas las banderas Show* (ShowValue, ...) a estado falso. IsVisible será false después de esto. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Análogo al operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la sentencia C# lock(). Llamar directamente o usar el objeto centinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo al método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. No copia nada, en realidad, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. No copia nada, en realidad, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de string y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| void [set_Height](./set_height/)(**float**) override | Establece la altura de un título como una fracción de la altura del gráfico. Escritura **float**. |
| void [set_ValueFromCell](./set_valuefromcell/)([System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\>) override | Establece la celda de datos del libro de trabajo. Se aplica si la propiedad IDataLabelFormat::get(set)_ShowLabelValueFromCell es verdadera. |
| void [set_Width](./set_width/)(**float**) override | Establece el ancho de un título como una fracción del ancho del gráfico. Escritura **float**. |
| void [set_X](./set_x/)(**float**) override | Establece la coordenada x de un título como una fracción del ancho del gráfico. Escritura **float**. |
| void [set_Y](./set_y/)(**float**) override | Establece la coordenada y de un título como una fracción de la altura del gráfico. Escritura **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como un puntero débil (en lugar de compartido). Permite cambiar punteros en contenedores a modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo al método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la sentencia C# lock(). Llamar directamente o usar el objeto centinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |

## Ver también

* Clase [IDataLabel](../idatalabel/)
* Clase [IDOMObject](../../aspose.slides/idomobject/)
* Espacio de nombres [Aspose::Slides::Charts](../)
* Biblioteca [Aspose.Slides](../../)