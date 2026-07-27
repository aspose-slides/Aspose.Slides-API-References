---
title: Legend
second_title: Referencia de API de Aspose.Slides para C++
description: Representa las propiedades de la leyenda del gráfico.
type: docs
weight: 1262
url: /es/aspose.slides.charts/legend/
---
## Legend clase

Representa las propiedades de la leyenda del gráfico.

```cpp
class Legend : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::Chart>>,
               public Aspose::Slides::Charts::ILegend
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica de C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia en estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor en estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para uso interno. |
| **float** [get_ActualHeight](./get_actualheight/)() override | Especifica la altura real del elemento del gráfico. Llama al método [IChart::ValidateChartLayout](../ichart/validatechartlayout/) antes para obtener los valores reales. Lee **float**. |
| **float** [get_ActualWidth](./get_actualwidth/)() override | Especifica el ancho real del elemento del gráfico. Llama al método [IChart::ValidateChartLayout](../ichart/validatechartlayout/) antes para obtener los valores reales. Lee **float**. |
| **float** [get_ActualX](./get_actualx/)() override | Especifica la ubicación x (izquierda) real del elemento del gráfico relativa a la esquina superior izquierda del gráfico. Llama al método [IChart::ValidateChartLayout](../ichart/validatechartlayout/) antes para obtener los valores reales. Lee **float**. |
| **float** [get_ActualY](./get_actualy/)() override | Especifica la parte superior real del elemento del gráfico relativa a la esquina superior izquierda del gráfico. Llama al método [IChart::ValidateChartLayout](../ichart/validatechartlayout/) antes para obtener los valores reales. Lee **float**. |
| **float** [get_Bottom](./get_bottom/)() override | Fondo. Solo de lectura **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Devuelve el gráfico. Solo de lectura [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryCollection](../ilegendentrycollection/)\> [get_Entries](./get_entries/)() override | Obtiene las entradas de la leyenda. Solo de lectura [ILegendEntryCollection](../ilegendentrycollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_Entry](./get_entry/)(**int32_t**) override | Obtiene las propiedades de la entrada de leyenda correspondiente al punto de datos en el gráfico en el índice especificado. En los tipos de gráfico: bar-of-pie, exploded pie, exploded pie 3D, pie, pie 3D, pie-of-pie, el punto de datos se toma de la primera serie. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | Devuelve el formato de una leyenda. Solo de lectura [IFormat](../iformat/). |
| **float** [get_Height](./get_height/)() override | Devuelve la altura de una leyenda como una fracción de la altura del gráfico. Lee **float**. |
| **bool** [get_Overlay](./get_overlay/)() override | Determina si se permite que otros elementos del gráfico se superpongan a la leyenda. Lee **bool**. |
| [LegendPositionType](../legendpositiontype/) [get_Position](./get_position/)() override | Especifica la posición de la leyenda en un gráfico. Los valores no NaN de las propiedades X, Y, Width, Heigt sobrescriben el efecto de esta propiedad. Lee [LegendPositionType](../legendpositiontype/). |
| **float** [get_Right](./get_right/)() override | Derecha. Solo de lectura **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | Formato de texto. Solo de lectura [IChartTextFormat](../icharttextformat/). |
| **float** [get_Width](./get_width/)() override | Devuelve el ancho de una leyenda como una fracción del ancho del gráfico. Lee **float**. |
| **float** [get_X](./get_x/)() override | Devuelve la coordenada x de una leyenda como una fracción del ancho del gráfico. Lee **float**. |
| **float** [get_Y](./get_y/)() override | Devuelve la coordenada y de una leyenda como una fracción de la altura del gráfico. Lee **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo al método C# [Object.GetHashCode()](../../system/object/gethashcode/). Habilita el hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Análogo a la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Análogo al operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la instrucción C# lock(). Llama directamente o usa el objeto centinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo al método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Habilita la clonación de tipos personalizados. |
|  [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. Realmente no copia nada, solo inicializa un nuevo objeto y permite la copia de subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. Realmente no copia nada, solo inicializa un nuevo objeto y permite la copia de subclases. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| void [set_Height](./set_height/)(**float**) override | Establece la altura de una leyenda como una fracción de la altura del gráfico. Escribe **float**. |
| void [set_Overlay](./set_overlay/)(**bool**) override | Determina si se permite que otros elementos del gráfico se superpongan a la leyenda. Escribe **bool**. |
| void [set_Position](./set_position/)([LegendPositionType](../legendpositiontype/)) override | Especifica la posición de la leyenda en un gráfico. Los valores no NaN de las propiedades X, Y, Width, Heigt sobrescriben el efecto de esta propiedad. Escribe [LegendPositionType](../legendpositiontype/). |
| void [set_Width](./set_width/)(**float**) override | Establece el ancho de una leyenda como una fracción del ancho del gráfico. Escribe **float**. |
| void [set_X](./set_x/)(**float**) override | Establece la coordenada x de una leyenda como una fracción del ancho del gráfico. Escribe **float**. |
| void [set_Y](./set_y/)(**float**) override | Establece la coordenada y de una leyenda como una fracción de la altura del gráfico. Escribe **float**. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Establece el n-ésimo argumento de plantilla como un puntero débil (en lugar de compartido). Permite cambiar punteros en contenedores a modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo al método C# [Object.ToString()](../../system/object/tostring/). Habilita la conversión de objetos personalizados a cadena. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la instrucción C# lock(). Llama directamente o usa el objeto centinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |

## Ver también

* Clase [DomObject](../../aspose.slides/domobject/)
* Clase [ILegend](../ilegend/)
* Espacio de nombres [Aspose::Slides::Charts](../)
* Biblioteca [Aspose.Slides](../../)