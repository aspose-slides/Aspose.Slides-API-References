---
title: ParagraphFormat
second_title: Referencia de la API de Aspose.Slides para C++
description: Esta clase contiene las propiedades de formato de párrafo. A diferencia de IParagraphFormatEffectiveData, todas las propiedades de esta clase son modificables.
type: docs
weight: 4668
url: /es/aspose.slides/paragraphformat/
---
## ParagraphFormat clase

Esta clase contiene las propiedades de formato de párrafo. A diferencia de [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/), todas las propiedades de esta clase son modificables.

```cpp
class ParagraphFormat : public Aspose::Slides::PVIObject,
                        public Aspose::Slides::IParagraphFormat,
                        public Aspose::Slides::Charts::IChartParagraphFormat
```

## Métodos

| Método | Descripción |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Compara con el objeto especificado. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para uso interno. |
| [TextAlignment](../textalignment/) [get_Alignment](./get_alignment/)() override | Devuelve la alineación del texto en un párrafo sin herencia. Leer [TextAlignment](../textalignment/). |
| **float** [get_DefaultTabSize](./get_defaulttabsize/)() override | Devuelve el tamaño de tabulación predeterminado sin herencia. Leer **float**. |
| [NullableBool](../nullablebool/) [get_EastAsianLineBreak](./get_eastasianlinebreak/)() override | Determina si se usa el salto de línea Este-Ásico en un párrafo. No se aplica herencia. Leer [NullableBool](../nullablebool/). |
| [Aspose::Slides::FontAlignment](../fontalignment/) [get_FontAlignment](./get_fontalignment/)() override | Devuelve una alineación de fuente en un párrafo sin herencia. Leer [Slides::FontAlignment](../fontalignment/). |
| [NullableBool](../nullablebool/) [get_HangingPunctuation](./get_hangingpunctuation/)() override | Determina si se usa la puntuación colgante en un párrafo. No se aplica herencia. Leer [NullableBool](../nullablebool/). |
| **float** [get_Indent](./get_indent/)() override | Devuelve la sangría de la primera línea / sangría colgante del párrafo sin herencia. La sangría colgante puede definirse con valores negativos. Leer **float**. |
| [NullableBool](../nullablebool/) [get_LatinLineBreak](./get_latinlinebreak/)() override | Determina si se usa el salto de línea Latino en un párrafo. No se aplica herencia. Leer [NullableBool](../nullablebool/). |
| **float** [get_MarginLeft](./get_marginleft/)() override | Devuelve el margen izquierdo en un párrafo sin herencia. Leer **float**. |
| **float** [get_MarginRight](./get_marginright/)() override | Devuelve el margen derecho en un párrafo sin herencia. Leer **float**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Devuelve el objeto Parent_Immediate. Solo lectura [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Devuelve el padre [IPresentationComponent](../ipresentationcomponent/). Solo lectura [IPresentationComponent](../ipresentationcomponent/). |
| [NullableBool](../nullablebool/) [get_RightToLeft](./get_righttoleft/)() override | Determina si se usa la escritura de derecha a izquierda en un párrafo. No se aplica herencia. Leer [NullableBool](../nullablebool/). |
| **float** [get_SpaceAfter](./get_spaceafter/)() override | Devuelve la cantidad de espacio después de la última línea en un párrafo sin herencia. Un valor positivo indica el porcentaje del tamaño de la fuente que debe ocupar el espacio en blanco. Un valor negativo indica el tamaño del espacio en blanco en puntos. Leer **float**. |
| **float** [get_SpaceBefore](./get_spacebefore/)() override | Devuelve la cantidad de espacio antes de la primera línea en un párrafo sin herencia. Un valor positivo indica el porcentaje del tamaño de la fuente que debe ocupar el espacio en blanco. Un valor negativo indica el tamaño del espacio en blanco en puntos. Leer **float**. |
| **float** [get_SpaceWithin](./get_spacewithin/)() override | Devuelve la cantidad de espacio entre líneas base en un párrafo. Un valor positivo indica porcentaje, negativo - tamaño en puntos. No se aplica herencia. Leer **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ITab](../itab/)\> [get_Tab](./get_tab/)(**int32_t**) override | Devuelve la tabulación de un párrafo en el índice especificado. No se aplica herencia. Solo lectura [Aspose::Slides::ITab](../itab/) |
| [System::SharedPtr](../../system/sharedptr/)\<[ITabCollection](../itabcollection/)\> [get_Tabs](./get_tabs/)() override | Devuelve las tabulaciones de un párrafo. No se aplica herencia. Solo lectura [ITabCollection](../itabcollection/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| [System::SharedPtr](../../system/sharedptr/)\<[IParagraphFormatEffectiveData](../iparagraphformateffectivedata/)\> [GetEffective](./geteffective/)() override | Obtiene los datos de formato de párrafo efectivos con la herencia aplicada. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Devuelve el código hash. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Análogo a la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Análogo al operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la instrucción C# lock(). Llame directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo al método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
| [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. En realidad no copia nada, solo inicializa un nuevo objeto y permite construir copias de subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. En realidad no copia nada, solo inicializa un nuevo objeto y permite construir copias de subclases. |
| [ParagraphFormat](./paragraphformat/)() | Inicializa una nueva instancia de la clase [ParagraphFormat](./). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| void [set_Alignment](./set_alignment/)([TextAlignment](../textalignment/)) override | Establece la alineación del texto en un párrafo sin herencia. Escribir [TextAlignment](../textalignment/). |
| void [set_DefaultTabSize](./set_defaulttabsize/)(**float**) override | Establece el tamaño de tabulación predeterminado sin herencia. Escribir **float**. |
| void [set_EastAsianLineBreak](./set_eastasianlinebreak/)([NullableBool](../nullablebool/)) override | Determina si se usa el salto de línea Este-Ásico en un párrafo. No se aplica herencia. Escribir [NullableBool](../nullablebool/). |
| void [set_FontAlignment](./set_fontalignment/)([Aspose::Slides::FontAlignment](../fontalignment/)) override | Establece una alineación de fuente en un párrafo sin herencia. Escribir [Slides::FontAlignment](../fontalignment/). |
| void [set_HangingPunctuation](./set_hangingpunctuation/)([NullableBool](../nullablebool/)) override | Determina si se usa la puntuación colgante en un párrafo. No se aplica herencia. Escribir [NullableBool](../nullablebool/). |
| void [set_Indent](./set_indent/)(**float**) override | Establece la sangría de la primera línea / sangría colgante del párrafo sin herencia. La sangría colgante puede definirse con valores negativos. Escribir **float**. |
| void [set_LatinLineBreak](./set_latinlinebreak/)([NullableBool](../nullablebool/)) override | Determina si se usa el salto de línea Latino en un párrafo. No se aplica herencia. Escribir [NullableBool](../nullablebool/). |
| void [set_MarginLeft](./set_marginleft/)(**float**) override | Establece el margen izquierdo en un párrafo sin herencia. Escribir **float**. |
| void [set_MarginRight](./set_marginright/)(**float**) override | Establece el margen derecho en un párrafo sin herencia. Escribir **float**. |
| void [set_RightToLeft](./set_righttoleft/)([NullableBool](../nullablebool/)) override | Determina si se usa la escritura de derecha a izquierda en un párrafo. No se aplica herencia. Escribir [NullableBool](../nullablebool/). |
| void [set_SpaceAfter](./set_spaceafter/)(**float**) override | Establece la cantidad de espacio después de la última línea en un párrafo sin herencia. Un valor positivo indica el porcentaje del tamaño de la fuente que debe ocupar el espacio en blanco. Un valor negativo indica el tamaño del espacio en blanco en puntos. Escribir **float**. |
| void [set_SpaceBefore](./set_spacebefore/)(**float**) override | Establece la cantidad de espacio antes de la primera línea en un párrafo sin herencia. Un valor positivo indica el porcentaje del tamaño de la fuente que debe ocupar el espacio en blanco. Un valor negativo indica el tamaño del espacio en blanco en puntos. Escribir **float**. |
| void [set_SpaceWithin](./set_spacewithin/)(**float**) override | Establece la cantidad de espacio entre líneas base en un párrafo. Un valor positivo indica porcentaje, negativo - tamaño en puntos. No se aplica herencia. Escribir **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como un puntero débil (en lugar de compartido). Permite cambiar los punteros en contenedores a modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo al método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la instrucción C# lock(). Llame directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |

## Observaciones

Esta clase se usa para devolver y manipular las propiedades de formato de párrafo definidas para el párrafo particular. Esto significa que no se aplica herencia al obtener los valores, por lo que en la mayoría de los casos obtendrá valores que significan "undefined".

Para obtener los valores efectivos de los parámetros de formato, incluidos los heredados, necesita usar el método [ParagraphFormat::GetEffective](./geteffective/) que devuelve una instancia [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/).

## Ver también

* Clase [PVIObject](../pviobject/)
* Clase [IParagraphFormat](../iparagraphformat/)
* Clase [IChartParagraphFormat](../../aspose.slides.charts/ichartparagraphformat/)
* Espacio de nombres [Aspose::Slides](../)
* Biblioteca [Aspose.Slides](../../)