---
title: ITextFrameFormat
second_title: Referencia de API de Aspose.Slides para C++
description: Contiene las propiedades de formato del TextFrame.
type: docs
weight: 4083
url: /es/aspose.slides/itextframeformat/
---
## ITextFrameFormat clase

Contiene las propiedades de formato de [TextFrame](../textframe/).

```cpp
class ITextFrameFormat : public virtual System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor al estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para uso interno. |
| virtual [TextAnchorType](../textanchortype/) [get_AnchoringType](./get_anchoringtype/)() | Devuelve el texto de anclaje vertical en un [TextFrame](../textframe/). Lectura [TextAnchorType](../textanchortype/). |
| virtual [TextAutofitType](../textautofittype/) [get_AutofitType](./get_autofittype/)() | Devuelve el modo de ajuste automático del texto. Lectura [TextAutofitType](../textautofittype/). |
| virtual [NullableBool](../nullablebool/) [get_CenterText](./get_centertext/)() | Si [NullableBool::True](../nullablebool/) entonces el texto debe estar centrado horizontalmente en la caja. Lectura [NullableBool](../nullablebool/). |
| virtual **int32_t** [get_ColumnCount](./get_columncount/)() | Devuelve el número de columnas en el área de texto. Este valor debe ser un número positivo. De lo contrario, el valor se establecerá en cero. El valor 0 significa valor indefinido. Lectura **int32_t**. |
| virtual **double** [get_ColumnSpacing](./get_columnspacing/)() | Devuelve el espacio entre columnas de texto en el área de texto (en puntos). Esto solo debe aplicarse cuando hay más de 1 columna presente. Este valor debe ser un número positivo. De lo contrario, el valor se establecerá en cero. Lectura **double**. |
| virtual **bool** [get_KeepTextFlat](./get_keeptextflat/)() | Devuelve o establece mantener el texto fuera de la escena 3D por completo. Lectura **bool**. |
| virtual **double** [get_MarginBottom](./get_marginbottom/)() | Devuelve el margen inferior (puntos) en un [TextFrame](../textframe/). Lectura **double**. |
| virtual **double** [get_MarginLeft](./get_marginleft/)() | Devuelve el margen izquierdo (puntos) en un [TextFrame](../textframe/). Lectura **double**. |
| virtual **double** [get_MarginRight](./get_marginright/)() | Devuelve el margen derecho (puntos) en un [TextFrame](../textframe/). Lectura **double**. |
| virtual **double** [get_MarginTop](./get_margintop/)() | Devuelve el margen superior (puntos) en un [TextFrame](../textframe/). Lectura **double**. |
| virtual **float** [get_RotationAngle](./get_rotationangle/)() | Especifica la rotación personalizada que se aplica al texto dentro del cuadro delimitador. Si no se especifica, se utiliza la rotación de la forma asociada. Si se especifica, se aplica de forma independiente de la forma. Es decir, la forma puede tener una rotación aplicada además de que el propio texto tenga una rotación aplicada. El valor resultante de la rotación visual del texto se resume a partir de esta propiedad y del tipo vertical predefinido en la propiedad TextVerticalType. Lectura **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextStyle](../itextstyle/)\> [get_TextStyle](./get_textstyle/)() | Devuelve el estilo del texto. Solo lectura [ITextStyle](../itextstyle/). |
| virtual [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() | Determina la orientación del texto. El valor resultante de la rotación visual del texto se resume a partir de esta propiedad y del ángulo personalizado en la propiedad RotationAngle. Lectura [Slides::TextVerticalType](../textverticaltype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](./get_threedformat/)() | Devuelve el objeto [ThreeDFormat](../threedformat/) que representa las propiedades de efecto 3D para un texto. Solo lectura [IThreeDFormat](../ithreedformat/). |
| virtual [TextShapeType](../textshapetype/) [get_Transform](./get_transform/)() | Obtiene la forma de ajuste de texto. Lectura [TextShapeType](../textshapetype/). |
| virtual [NullableBool](../nullablebool/) [get_WrapText](./get_wraptext/)() | **True** si el texto se ajusta en los márgenes de [TextFrame](../textframe/). Lectura [NullableBool](../nullablebool/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrameFormatEffectiveData](../itextframeformateffectivedata/)\> [GetEffective](./geteffective/)() | Obtiene los datos de formato efectivos del marco de texto con la herencia aplicada. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo del método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite el hashing de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Análogo de la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Análogo del operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la sentencia C# lock(). Llámese directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo del método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras internas de datos. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. En realidad no copia nada, solo inicializa un nuevo objeto y permite la construcción de copias de subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. En realidad no copia nada, solo inicializa un nuevo objeto y permite la construcción de copias de subclases. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| virtual void [set_AnchoringType](./set_anchoringtype/)([TextAnchorType](../textanchortype/)) | Establece el texto de anclaje vertical en un [TextFrame](../textframe/). Escritura [TextAnchorType](../textanchortype/). |
| virtual void [set_AutofitType](./set_autofittype/)([TextAutofitType](../textautofittype/)) | Establece el modo de ajuste automático del texto. Escritura [TextAutofitType](../textautofittype/). |
| virtual void [set_CenterText](./set_centertext/)([NullableBool](../nullablebool/)) | Si [NullableBool::True](../nullablebool/) entonces el texto debe estar centrado horizontalmente en la caja. Escritura [NullableBool](../nullablebool/). |
| virtual void [set_ColumnCount](./set_columncount/)(**int32_t**) | Establece el número de columnas en el área de texto. Este valor debe ser un número positivo. De lo contrario, el valor se establecerá en cero. El valor 0 significa valor indefinido. Escritura **int32_t**. |
| virtual void [set_ColumnSpacing](./set_columnspacing/)(**double**) | Establece el espacio entre columnas de texto en el área de texto (en puntos). Esto solo debe aplicarse cuando hay más de 1 columna presente. Este valor debe ser un número positivo. De lo contrario, el valor se establecerá en cero. Escritura **double**. |
| virtual void [set_KeepTextFlat](./set_keeptextflat/)(**bool**) | Devuelve o establece mantener el texto fuera de la escena 3D por completo. Escritura **bool**. |
| virtual void [set_MarginBottom](./set_marginbottom/)(**double**) | Establece el margen inferior (puntos) en un [TextFrame](../textframe/). Escritura **double**. |
| virtual void [set_MarginLeft](./set_marginleft/)(**double**) | Establece el margen izquierdo (puntos) en un [TextFrame](../textframe/). Escritura **double**. |
| virtual void [set_MarginRight](./set_marginright/)(**double**) | Establece el margen derecho (puntos) en un [TextFrame](../textframe/). Escritura **double**. |
| virtual void [set_MarginTop](./set_margintop/)(**double**) | Establece el margen superior (puntos) en un [TextFrame](../textframe/). Escritura **double**. |
| virtual void [set_RotationAngle](./set_rotationangle/)(**float**) | Especifica la rotación personalizada que se aplica al texto dentro del cuadro delimitador. Si no se especifica, se utiliza la rotación de la forma asociada. Si se especifica, se aplica de forma independiente de la forma. Es decir, la forma puede tener una rotación aplicada además de que el propio texto tenga una rotación aplicada. El valor resultante de la rotación visual del texto se resume a partir de esta propiedad y del tipo vertical predefinido en la propiedad TextVerticalType. Escritura **float**. |
| virtual void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) | Determina la orientación del texto. El valor resultante de la rotación visual del texto se resume a partir de esta propiedad y del ángulo personalizado en la propiedad RotationAngle. Escritura [Slides::TextVerticalType](../textverticaltype/). |
| virtual void [set_Transform](./set_transform/)([TextShapeType](../textshapetype/)) | Establece la forma de ajuste de texto. Escritura [TextShapeType](../textshapetype/). |
| virtual void [set_WrapText](./set_wraptext/)([NullableBool](../nullablebool/)) | **True** si el texto se ajusta en los márgenes de [TextFrame](../textframe/). Escritura [NullableBool](../nullablebool/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como un puntero débil (en lugar de compartido). Permite cambiar punteros en contenedores a modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo del método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la sentencia C# lock(). Llámese directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras internas de datos. |

## Ver también

* Clase [Object](../../system/object/)
* Espacio de nombres [Aspose::Slides](../)
* Biblioteca [Aspose.Slides](../../)