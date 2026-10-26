---
title: IParagraphFormat
second_title: Referencia de la API de Aspose.Slides para C++
description: Esta clase contiene las propiedades de formato de párrafo. A diferencia de IParagraphFormatEffectiveData, todas las propiedades de esta clase son modificables.
type: docs
weight: 3147
url: /es/aspose.slides/iparagraphformat/
---
## IParagraphFormat clase


Esta clase contiene las propiedades de formato de párrafo. A diferencia de [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/), todas las propiedades de esta clase son modificables.

```cpp
class IParagraphFormat : public virtual System::Object
```

## Métodos

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica de C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia en estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor en estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque, según IEC 60559:1989, NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque, según IEC 60559:1989, NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para uso interno. |
| virtual [TextAlignment](../textalignment/) [get_Alignment](./get_alignment/)() | Devuelve la alineación del texto en un párrafo sin herencia. Consulte [TextAlignment](../textalignment/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBulletFormat](../ibulletformat/)\> [get_Bullet](./get_bullet/)() | Devuelve el formato de viñeta del párrafo. Solo lectura [IBulletFormat](../ibulletformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPortionFormat](../iportionformat/)\> [get_DefaultPortionFormat](./get_defaultportionformat/)() | Devuelve el formato de porción predeterminado de un párrafo. No se aplica herencia. Solo lectura [IPortionFormat](../iportionformat/). |
| virtual **float** [get_DefaultTabSize](./get_defaulttabsize/)() | Devuelve el tamaño predeterminado de tabulación sin herencia. Lea **float**. |
| virtual **int16_t** [get_Depth](./get_depth/)() | Devuelve la profundidad del párrafo. El valor 0 significa valor indefinido. Lea **int16_t**. |
| virtual [NullableBool](../nullablebool/) [get_EastAsianLineBreak](./get_eastasianlinebreak/)() | Determina si se utiliza el salto de línea de Asia Oriental en un párrafo. No se aplica herencia. Consulte [NullableBool](../nullablebool/). |
| virtual [Aspose::Slides::FontAlignment](../fontalignment/) [get_FontAlignment](./get_fontalignment/)() | Devuelve la alineación de fuente en un párrafo sin herencia. Consulte [Slides::FontAlignment](../fontalignment/). |
| virtual [NullableBool](../nullablebool/) [get_HangingPunctuation](./get_hangingpunctuation/)() | Determina si se usa la puntuación colgante en un párrafo. No se aplica herencia. Consulte [NullableBool](../nullablebool/). |
| virtual **float** [get_Indent](./get_indent/)() | Devuelve la sangría de la primera línea/ sangría colgante del párrafo sin herencia. La sangría colgante puede definirse con valores negativos. Lea **float**. |
| virtual [NullableBool](../nullablebool/) [get_LatinLineBreak](./get_latinlinebreak/)() | Determina si se usa el salto de línea latino en un párrafo. No se aplica herencia. Consulte [NullableBool](../nullablebool/). |
| virtual **float** [get_MarginLeft](./get_marginleft/)() | Devuelve el margen izquierdo en un párrafo sin herencia. Lea **float**. |
| virtual **float** [get_MarginRight](./get_marginright/)() | Devuelve el margen derecho en un párrafo sin herencia. Lea **float**. |
| virtual [NullableBool](../nullablebool/) [get_RightToLeft](./get_righttoleft/)() | Determina si se utiliza la escritura de derecha a izquierda en un párrafo. No se aplica herencia. Consulte [NullableBool](../nullablebool/). |
| virtual **float** [get_SpaceAfter](./get_spaceafter/)() | Devuelve la cantidad de espacio después de la última línea en un párrafo sin herencia. Un valor positivo especifica el porcentaje del tamaño de la fuente que debe tener el espacio en blanco. Un valor negativo especifica el tamaño del espacio en blanco en puntos. Lea **float**. |
| virtual **float** [get_SpaceBefore](./get_spacebefore/)() | Devuelve la cantidad de espacio antes de la primera línea en un párrafo sin herencia. Un valor positivo especifica el porcentaje del tamaño de la fuente que debe tener el espacio en blanco. Un valor negativo especifica el tamaño del espacio en blanco en puntos. Lea **float**. |
| virtual **float** [get_SpaceWithin](./get_spacewithin/)() | Devuelve la cantidad de espacio entre líneas base en un párrafo. Un valor positivo indica porcentaje, uno negativo indica tamaño en puntos. No se aplica herencia. Lea **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITab](../itab/)\> [get_Tab](./get_tab/)(**int32_t**) | Devuelve la tabulación de un párrafo en el índice especificado. No se aplica herencia. Solo lectura [Aspose::Slides::ITab](../itab/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITabCollection](../itabcollection/)\> [get_Tabs](./get_tabs/)() | Devuelve las tabulaciones de un párrafo. No se aplica herencia. Solo lectura [ITabCollection](../itabcollection/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IParagraphFormatEffectiveData](../iparagraphformateffectivedata/)\> [GetEffective](./geteffective/)() | Obtiene los datos de formato de párrafo efectivos con la herencia aplicada. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo al método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite el hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Analogo a la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Analogo al operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la instrucción C# lock(). Llame directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo al método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. En realidad no copia nada, solo inicializa un nuevo objeto y permite la copia de construcción de subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. En realidad no copia nada, solo inicializa un nuevo objeto y permite la copia de construcción de subclases. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| virtual void [set_Alignment](./set_alignment/)([TextAlignment](../textalignment/)) | Establece la alineación del texto en un párrafo sin herencia. Escriba [TextAlignment](../textalignment/). |
| virtual void [set_DefaultTabSize](./set_defaulttabsize/)(**float**) | Establece el tamaño predeterminado de tabulación sin herencia. Escriba **float**. |
| virtual void [set_Depth](./set_depth/)(**int16_t**) | Establece la profundidad del párrafo. El valor 0 significa valor indefinido. Escriba **int16_t**. |
| virtual void [set_EastAsianLineBreak](./set_eastasianlinebreak/)([NullableBool](../nullablebool/)) | Determina si se usa el salto de línea de Asia Oriental en un párrafo. No se aplica herencia. Escriba [NullableBool](../nullablebool/). |
| virtual void [set_FontAlignment](./set_fontalignment/)([Aspose::Slides::FontAlignment](../fontalignment/)) | Establece una alineación de fuente en un párrafo sin herencia. Escriba [Slides::FontAlignment](../fontalignment/). |
| virtual void [set_HangingPunctuation](./set_hangingpunctuation/)([NullableBool](../nullablebool/)) | Determina si se usa la puntuación colgante en un párrafo. No se aplica herencia. Escriba [NullableBool](../nullablebool/). |
| virtual void [set_Indent](./set_indent/)(**float**) | Establece la sangría de la primera línea / sangría colgante del párrafo sin herencia. La sangría colgante puede definirse con valores negativos. Escriba **float**. |
| virtual void [set_LatinLineBreak](./set_latinlinebreak/)([NullableBool](../nullablebool/)) | Determina si se usa el salto de línea latino en un párrafo. No se aplica herencia. Escriba [NullableBool](../nullablebool/). |
| virtual void [set_MarginLeft](./set_marginleft/)(**float**) | Establece el margen izquierdo en un párrafo sin herencia. Escriba **float**. |
| virtual void [set_MarginRight](./set_marginright/)(**float**) | Establece el margen derecho en un párrafo sin herencia. Escriba **float**. |
| virtual void [set_RightToLeft](./set_righttoleft/)([NullableBool](../nullablebool/)) | Determina si se utiliza la escritura de derecha a izquierda en un párrafo. No se aplica herencia. Escriba [NullableBool](../nullablebool/). |
| virtual void [set_SpaceAfter](./set_spaceafter/)(**float**) | Establece la cantidad de espacio después de la última línea en un párrafo sin herencia. Un valor positivo especifica el porcentaje del tamaño de la fuente que debe tener el espacio en blanco. Un valor negativo especifica el tamaño del espacio en blanco en puntos. Escriba **float**. |
| virtual void [set_SpaceBefore](./set_spacebefore/)(**float**) | Establece la cantidad de espacio antes de la primera línea en un párrafo sin herencia. Un valor positivo especifica el porcentaje del tamaño de la fuente que debe tener el espacio en blanco. Un valor negativo especifica el tamaño del espacio en blanco en puntos. Escriba **float**. |
| virtual void [set_SpaceWithin](./set_spacewithin/)(**float**) | Establece la cantidad de espacio entre líneas base en un párrafo. Un valor positivo indica porcentaje, uno negativo indica tamaño en puntos. No se aplica herencia. Escriba **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como un puntero débil (en lugar de compartido). Permite cambiar punteros en contenedores a modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo al método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la instrucción C# lock(). Llame directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |

## Comentarios


Esta clase se utiliza para devolver y manipular las propiedades de formato de párrafo definidas para el párrafo concreto. Esto significa que no se aplica herencia al obtener los valores, por lo que en la mayoría de los casos se obtendrán valores que significan "indefinido".

Para obtener los valores de los parámetros de formato efectivos, incluidos los heredados, es necesario usar el método [IParagraphFormat::GetEffective](./geteffective/) que devuelve una instancia [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/).

## Ver también

* Clase [Object](../../system/object/)
* Espacio de nombres [Aspose::Slides](../)
* Biblioteca [Aspose.Slides](../../)