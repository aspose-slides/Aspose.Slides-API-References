---
title: ITrendline
second_title: Referencia de API de Aspose.Slides para C++
description: Clase que representa la línea de tendencia de la serie del gráfico
type: docs
weight: 1223
url: /es/aspose.slides.charts/itrendline/
---
## ITrendline clase

Class representa la línea de tendencia de la serie del gráfico

```cpp
class ITrendline : public Aspose::Slides::Charts::IOverridableText
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](../ioverridabletext/addtextframeforoverriding/)([System::String](../../system/string/)) | Inicializa TextFrameForOverriding con el texto en el parámetro \"text\". Si TextFrameForOverriding ya está inicializado, simplemente cambia su texto. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica de C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo de C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor al estilo de C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo de C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo de C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para uso interno. |
| virtual **double** [get_Backward](./get_backward/)() | Especifica el número de categorías (o unidades en un gráfico de dispersión) que la línea de tendencia se extiende antes de los datos de la serie que se está tendiendo. En gráficos de dispersión y no dispersión, el valor debe ser cualquier valor no negativo. Leer **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Devuelve el gráfico. Solo lectura [IChart](../ichart/). |
| virtual **bool** [get_DisplayEquation](./get_displayequation/)() | Especifica que la ecuación de la línea de tendencia se muestra en el gráfico (en la misma etiqueta que Rsquaredvalue). Leer **bool**. |
| virtual **bool** [get_DisplayRSquaredValue](./get_displayrsquaredvalue/)() | Especifica que el valor R-cuadrado de la línea de tendencia se muestra en el gráfico (en la misma etiqueta que la ecuación). Leer **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | Representa el formato de la línea de tendencia. Leer [IFormat](../iformat/). |
| virtual **double** [get_Forward](./get_forward/)() | Especifica el número de categorías (o unidades en un gráfico de dispersión) que la línea de tendencia se extiende después de los datos de la serie que se está tendiendo. En gráficos de dispersión y no dispersión, el valor debe ser cualquier valor no negativo. Leer **double**. |
| virtual **double** [get_Intercept](./get_intercept/)() | Especifica el valor donde la línea de tendencia debe cruzar el eje y. Esta propiedad solo se admite cuando el tipo de línea de tendencia es exp, linear o poly. Leer **double**. |
| virtual **uint8_t** [get_Order](./get_order/)() | Especifica el orden de la línea de tendencia polinómica. Se ignora para otros tipos de línea de tendencia. El valor debe estar entre 2 y 6. Leer **uint8_t**. |
| virtual **uint8_t** [get_Period](./get_period/)() | Especifica el período de la línea de tendencia para una línea de tendencia de media móvil. Se ignora para otras variantes de línea de tendencia. El valor debe estar entre 2 y 255. Leer **uint8_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Devuelve la presentación. Solo lectura [IPresentation](../../aspose.slides/ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_RelatedLegendEntry](./get_relatedlegendentry/)() | Representa la entrada de leyenda relacionada con esta línea de tendencia. Solo lectura [ILegendEntryProperties](../ilegendentryproperties/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Devuelve la diapositiva base. Solo lectura [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | Devuelve el formato de texto del gráfico. Solo lectura [IChartTextFormat](../icharttextformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](../ioverridabletext/get_textframeforoverriding/)() | Puede contener un texto con formato enriquecido. Si esta propiedad no es nula, entonces este valor de texto con formato sobrescribe el texto autogenerado. El texto autogenerado es una propiedad implícita de la etiqueta de datos, la etiqueta de unidad de visualización del eje de valores, el título del eje, el título del gráfico, la etiqueta de la línea de tendencia. El texto autogenerado se da formato con la propiedad [IFormattedTextContainer::get_TextFormat](../iformattedtextcontainer/get_textformat/). Solo lectura [ITextFrame](../../aspose.slides/itextframe/). |
| virtual [System::String](../../system/string/) [get_TrendlineName](./get_trendlinename/)() | Obtiene el nombre de la línea de tendencia. Leer [System::String](../../system/string/). |
| virtual [Aspose::Slides::Charts::TrendlineType](../trendlinetype/) [get_TrendlineType](./get_trendlinetype/)() | Obtiene el tipo de línea de tendencia. Leer [TrendlineType](../trendlinetype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo al método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite el hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Análogo a la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Análogo al operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la instrucción C# lock(). Llame directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo al método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. Realmente no copia nada, solo inicializa un nuevo objeto y permite la construcción de copias de subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. Realmente no copia nada, solo inicializa un nuevo objeto y permite la construcción de copias de subclases. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia el objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| virtual void [set_Backward](./set_backward/)(**double**) | Especifica el número de categorías (o unidades en un gráfico de dispersión) que la línea de tendencia se extiende antes de los datos de la serie que se está tendiendo. En gráficos de dispersión y no dispersión, el valor debe ser cualquier valor no negativo. Escribir **double**. |
| virtual void [set_DisplayEquation](./set_displayequation/)(**bool**) | Especifica que la ecuación de la línea de tendencia se muestra en el gráfico (en la misma etiqueta que Rsquaredvalue). Escribir **bool**. |
| virtual void [set_DisplayRSquaredValue](./set_displayrsquaredvalue/)(**bool**) | Especifica que el valor R-cuadrado de la línea de tendencia se muestra en el gráfico (en la misma etiqueta que la ecuación). Escribir **bool**. |
| virtual void [set_Format](./set_format/)([System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\>) | Representa el formato de la línea de tendencia. Escribir [IFormat](../iformat/). |
| virtual void [set_Forward](./set_forward/)(**double**) | Especifica el número de categorías (o unidades en un gráfico de dispersión) que la línea de tendencia se extiende después de los datos de la serie que se está tendiendo. En gráficos de dispersión y no dispersión, el valor debe ser cualquier valor no negativo. Escribir **double**. |
| virtual void [set_Intercept](./set_intercept/)(**double**) | Especifica el valor donde la línea de tendencia debe cruzar el eje y. Esta propiedad solo se admite cuando el tipo de línea de tendencia es exp, linear o poly. Escribir **double**. |
| virtual void [set_Order](./set_order/)(**uint8_t**) | Especifica el orden de la línea de tendencia polinómica. Se ignora para otros tipos de línea de tendencia. El valor debe estar entre 2 y 6. Escribir **uint8_t**. |
| virtual void [set_Period](./set_period/)(**uint8_t**) | Especifica el período de la línea de tendencia para una media móvil. Se ignora para otras variantes de línea de tendencia. El valor debe estar entre 2 y 255. Escribir **uint8_t**. |
| virtual void [set_TrendlineName](./set_trendlinename/)([System::String](../../system/string/)) | Establece el nombre de la línea de tendencia. Escribir [System::String](../../system/string/). |
| virtual void [set_TrendlineType](./set_trendlinetype/)([Aspose::Slides::Charts::TrendlineType](../trendlinetype/)) | Establece el tipo de línea de tendencia. Escribir [TrendlineType](../trendlinetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como un puntero débil (en lugar de compartido). Permite cambiar los punteros en contenedores al modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo al método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la instrucción C# lock(). Llame directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras internas. |

## Ver también

* Clase [IOverridableText](../ioverridabletext/)
* Espacio de nombres [Aspose::Slides::Charts](../)
* Library [Aspose.Slides](../../)