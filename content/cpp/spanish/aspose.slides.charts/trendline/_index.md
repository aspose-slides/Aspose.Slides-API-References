---
title: Trendline
second_title: Referencia de API de Aspose.Slides para C++
description: Clase que representa la línea de tendencia de la serie del gráfico
type: docs
weight: 1366
url: /es/aspose.slides.charts/trendline/
---
## Clase Trendline

La clase representa la línea de tendencia de la serie del gráfico

```cpp
class Trendline : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::TrendlineCollection>>,
                  public Aspose::Slides::Charts::ITrendline
```

## Métodos

| Método | Descripción |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](./addtextframeforoverriding/)([System::String](../../system/string/)) override | Inicializa TextFrameForOverriding con el texto del parámetro "text". Si TextFrameForOverriding ya está inicializado, entonces simplemente cambia su texto. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica de C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo de C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor al estilo de C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo de C# donde dos NaNs se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo de C# donde dos NaNs se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para uso interno. |
| **double** [get_Backward](./get_backward/)() override | Especifica el número de categorías (o unidades en un gráfico de dispersión) que la línea de tendencia se extiende antes de los datos de la serie que se está tendiendo. En gráficos de dispersión y no dispersión, el valor debe ser cualquier valor no negativo. Leer **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Devuelve el gráfico principal. Solo lectura [IChart](../ichart/). |
| **bool** [get_DisplayEquation](./get_displayequation/)() override | Especifica que la ecuación de la línea de tendencia se muestra en el gráfico (en la misma etiqueta que el Rsquaredvalue). Leer **bool**. |
| **bool** [get_DisplayRSquaredValue](./get_displayrsquaredvalue/)() override | Especifica que el valor R al cuadrado de la línea de tendencia se muestra en el gráfico (en la misma etiqueta que la ecuación). Leer **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | Representa el formato de la línea de tendencia. Leer [IFormat](../iformat/). |
| **double** [get_Forward](./get_forward/)() override | Especifica el número de categorías (o unidades en un gráfico de dispersión) que la línea de tendencia se extiende después de los datos de la serie que se está tendiendo. En gráficos de dispersión y no dispersión, el valor debe ser cualquier valor no negativo. Leer **double**. |
| **double** [get_Intercept](./get_intercept/)() override | Especifica el valor donde la línea de tendencia cruza el eje y. Esta propiedad solo se admite cuando el tipo de línea de tendencia es exp, linear o poly. Leer **double**. |
| **uint8_t** [get_Order](./get_order/)() override | Especifica el orden de la línea de tendencia polinómica. Se ignora para otros tipos de línea de tendencia. El valor debe estar entre 2 y 6. Leer **uint8_t**. |
| **uint8_t** [get_Period](./get_period/)() override | Especifica el período de la línea de tendencia para una línea de tendencia de media móvil. Se ignora para otras variantes de línea de tendencia. El valor debe estar entre 2 y 255. Leer **uint8_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_RelatedLegendEntry](./get_relatedlegendentry/)() override | Representa la entrada de leyenda relacionada con esta línea de tendencia. Solo lectura [ILegendEntryProperties](../ilegendentryproperties/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | Devuelve el formato de texto. Solo lectura [IChartTextFormat](../icharttextformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](./get_textframeforoverriding/)() override | Puede contener un texto con formato enriquecido. Si esta propiedad no es nula, entonces este valor de texto con formato sobrescribe el texto autogenerado de la etiqueta de datos. El texto autogenerado de la etiqueta de datos significa el texto que es gestionado por las propiedades ShowSeriesName, ShowValue, ... y se formatea con la propiedad TextFormatManager.TextFormat. Solo lectura [ITextFrame](../../aspose.slides/itextframe/). |
| [System::String](../../system/string/) [get_TrendlineName](./get_trendlinename/)() override | Obtiene el nombre de la línea de tendencia. Leer [System::String](../../system/string/). |
| [Aspose::Slides::Charts::TrendlineType](../trendlinetype/) [get_TrendlineType](./get_trendlinetype/)() override | Obtiene el tipo de línea de tendencia. Leer [Charts::TrendlineType](../trendlinetype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo al método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite el hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Análogo a la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Análogo al operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la instrucción C# lock(). Llámalo directamente o usa el objeto centinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo al método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. En realidad no copia nada, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. En realidad no copia nada, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| void [set_Backward](./set_backward/)(**double**) override | Especifica el número de categorías (o unidades en un gráfico de dispersión) que la línea de tendencia se extiende antes de los datos de la serie que se está tendiendo. En gráficos de dispersión y no dispersión, el valor debe ser cualquier valor no negativo. Escribir **double**. |
| void [set_DisplayEquation](./set_displayequation/)(**bool**) override | Especifica que la ecuación de la línea de tendencia se muestra en el gráfico (en la misma etiqueta que el Rsquaredvalue). Escribir **bool**. |
| void [set_DisplayRSquaredValue](./set_displayrsquaredvalue/)(**bool**) override | Especifica que el valor R al cuadrado de la línea de tendencia se muestra en el gráfico (en la misma etiqueta que la ecuación). Escribir **bool**. |
| void [set_Format](./set_format/)([System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\>) override | Representa el formato de la línea de tendencia. Escribir [IFormat](../iformat/). |
| void [set_Forward](./set_forward/)(**double**) override | Especifica el número de categorías (o unidades en un gráfico de dispersión) que la línea de tendencia se extiende después de los datos de la serie que se está tendiendo. En gráficos de dispersión y no dispersión, el valor debe ser cualquier valor no negativo. Escribir **double**. |
| void [set_Intercept](./set_intercept/)(**double**) override | Especifica el valor donde la línea de tendencia cruza el eje y. Esta propiedad solo se admite cuando el tipo de línea de tendencia es exp, linear o poly. Escribir **double**. |
| void [set_Order](./set_order/)(**uint8_t**) override | Especifica el orden de la línea de tendencia polinómica. Se ignora para otros tipos de línea de tendencia. El valor debe estar entre 2 y 6. Escribir **uint8_t**. |
| void [set_Period](./set_period/)(**uint8_t**) override | Especifica el período de la línea de tendencia para una línea de tendencia de media móvil. Se ignora para otras variantes de línea de tendencia. El valor debe estar entre 2 y 255. Escribir **uint8_t**. |
| void [set_TrendlineName](./set_trendlinename/)([System::String](../../system/string/)) override | Establece el nombre de la línea de tendencia. Escribir [System::String](../../system/string/). |
| void [set_TrendlineType](./set_trendlinetype/)([Aspose::Slides::Charts::TrendlineType](../trendlinetype/)) override | Establece el tipo de línea de tendencia. Escribir [Charts::TrendlineType](../trendlinetype/). |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Establece el n-ésimo argumento de plantilla como puntero débil (en lugar de compartido). Permite cambiar punteros en contenedores al modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo al método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la instrucción C# lock(). Llámalo directamente o usa el objeto centinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |

## Ver también

* Clase [DomObject](../../aspose.slides/domobject/)
* Clase [ITrendline](../itrendline/)
* Espacio de nombres [Aspose::Slides::Charts](../)
* Biblioteca [Aspose.Slides](../../)