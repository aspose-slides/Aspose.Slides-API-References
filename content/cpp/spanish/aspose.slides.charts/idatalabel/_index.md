---
title: IDataLabel
second_title: Referencia de la API de Aspose.Slides para C++
description: Representa etiquetas de serie.
type: docs
weight: 937
url: /es/aspose.slides.charts/idatalabel/
---
## IDataLabel clase

Representa etiquetas de serie.

```cpp
class IDataLabel : public Aspose::Slides::Charts::ILayoutable,
                   public Aspose::Slides::Charts::IOverridableText,
                   public Aspose::Slides::Charts::IActualLayout
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](../ioverridabletext/addtextframeforoverriding/)([System::String](../../system/string/)) | Inicializa TextFrameForOverriding con el texto del parámetro \"text\". Si TextFrameForOverriding ya está inicializado, simplemente cambia su texto. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica de C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia en estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor en estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque, según IEC 60559:1989, NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque, según IEC 60559:1989, NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para uso interno. |
| virtual **float** [get_ActualHeight](../iactuallayout/get_actualheight/)() | Especifica la altura real del elemento del gráfico. Llame al método [IChart::ValidateChartLayout](../ichart/validatechartlayout/) antes para obtener los valores reales. Lectura **float**. |
| virtual **float** [get_ActualWidth](../iactuallayout/get_actualwidth/)() | Especifica el ancho real del elemento del gráfico. Llame al método [IChart::ValidateChartLayout](../ichart/validatechartlayout/) antes para obtener los valores reales. Lectura **float**. |
| virtual **float** [get_ActualX](../iactuallayout/get_actualx/)() | Especifica la ubicación x real (izquierda) del elemento del gráfico relativa a la esquina superior izquierda del gráfico. Llame al método [IChart::ValidateChartLayout](../ichart/validatechartlayout/) antes para obtener los valores reales. Lectura **float**. |
| virtual **float** [get_ActualY](../iactuallayout/get_actualy/)() | Especifica la parte superior real del elemento del gráfico relativa a la esquina superior izquierda del gráfico. Llame al método [IChart::ValidateChartLayout](../ichart/validatechartlayout/) antes para obtener los valores reales. Lectura **float**. |
| virtual **float** [get_Bottom](../ilayoutable/get_bottom/)() | Obtiene la parte superior del elemento del gráfico como una fracción de la altura del gráfico. Sólo lectura **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Devuelve el gráfico. Sólo lectura [IChart](../ichart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDataLabelFormat](../idatalabelformat/)\> [get_DataLabelFormat](./get_datalabelformat/)() | Devuelve el formato de la etiqueta de datos. Sólo lectura [IDataLabelFormat](../idatalabelformat/). |
| virtual **float** [get_Height](../ilayoutable/get_height/)() | Especifica la altura del elemento del gráfico como una fracción de la altura del gráfico. Lectura **float**. |
| virtual **bool** [get_IsVisible](./get_isvisible/)() | False indica que la etiqueta de datos no es visible (y por lo tanto todas las banderas Show* (ShowValue, ...) son falsas). Sólo lectura **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Devuelve la presentación. Sólo lectura [IPresentation](../../aspose.slides/ipresentation/). |
| virtual **float** [get_Right](../ilayoutable/get_right/)() | Obtiene el lado derecho del elemento del gráfico como una fracción del ancho del gráfico. Sólo lectura **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Devuelve la diapositiva base. Sólo lectura [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | Devuelve el formato de texto del gráfico. Sólo lectura [IChartTextFormat](../icharttextformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](../ioverridabletext/get_textframeforoverriding/)() | Puede contener un texto con formato enriquecido. Si esta propiedad no es nula, entonces este valor de texto con formato sobrescribe el texto autogenerado. El texto autogenerado es una propiedad implícita de la etiqueta de datos, la etiqueta de unidad de visualización del eje de valores, el título del eje, el título del gráfico, la etiqueta de la línea de tendencia. El texto autogenerado se forma con la propiedad [IFormattedTextContainer::get_TextFormat](../iformattedtextcontainer/get_textformat/). Sólo lectura [ITextFrame](../../aspose.slides/itextframe/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\> [get_ValueFromCell](./get_valuefromcell/)() | Obtiene la celda de datos del libro de trabajo. Se aplica si la propiedad IDataLabelFormat::get(set)_ShowLabelValueFromCell es verdadera. |
| virtual **float** [get_Width](../ilayoutable/get_width/)() | Especifica el ancho del elemento del gráfico como una fracción del ancho del gráfico. Lectura **float**. |
| virtual **float** [get_X](../ilayoutable/get_x/)() | Especifica la ubicación x (izquierda) del elemento del gráfico como una fracción del ancho del gráfico. Lectura **float**. |
| virtual **float** [get_Y](../ilayoutable/get_y/)() | Especifica la parte superior del elemento del gráfico como una fracción de la altura del gráfico. Lectura **float**. |
| virtual [System::String](../../system/string/) [GetActualLabelText](./getactuallabeltext/)() | Devuelve el texto real de la etiqueta basado en la configuración [DataLabelFormat](../datalabelformat/) o el valor TextFrameForOverriding.Text. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociado al objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo al método C# [Object.GetHashCode()](../../system/object/gethashcode/). Habilita el hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Análogo a la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual void [Hide](./hide/)() | Oculta la etiqueta de datos estableciendo todas las banderas Show* (ShowValue, ...) al estado falso. IsVisible será falso después de esto. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Análogo al operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la sentencia C# lock(). Llámele directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo al método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Habilita la clonación de tipos personalizados. |
|  [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. En realidad no copia nada, solo inicializa un nuevo objeto y permite la construcción de copias de subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. En realidad no copia nada, solo inicializa un nuevo objeto y permite la construcción de copias de subclases. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| virtual void [set_Height](../ilayoutable/set_height/)(**float**) | Especifica la altura del elemento del gráfico como una fracción de la altura del gráfico. Escritura **float**. |
| virtual void [set_ValueFromCell](./set_valuefromcell/)([System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\>) | Establece la celda de datos del libro de trabajo. Se aplica si la propiedad IDataLabelFormat::get(set)_ShowLabelValueFromCell es verdadera. |
| virtual void [set_Width](../ilayoutable/set_width/)(**float**) | Especifica el ancho del elemento del gráfico como una fracción del ancho del gráfico. Escritura **float**. |
| virtual void [set_X](../ilayoutable/set_x/)(**float**) | Especifica la ubicación x (izquierda) del elemento del gráfico como una fracción del ancho del gráfico. Escritura **float**. |
| virtual void [set_Y](../ilayoutable/set_y/)(**float**) | Especifica la parte superior del elemento del gráfico como una fracción de la altura del gráfico. Escritura **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como un puntero débil (en lugar de compartido). Permite cambiar los punteros en contenedores a modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo al método C# [Object.ToString()](../../system/object/tostring/). Habilita la conversión de objetos personalizados a cadena. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la sentencia C# lock(). Llámele directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |

## Ver también

* Clase [ILayoutable](../ilayoutable/)
* Clase [IOverridableText](../ioverridabletext/)
* Clase [IActualLayout](../iactuallayout/)
* Espacio de nombres [Aspose::Slides::Charts](../)
* Biblioteca [Aspose.Slides](../../)