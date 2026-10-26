---
title: ICell
second_title: Referencia de API de Aspose.Slides para C++
description: Representa una celda en una tabla.
type: docs
weight: 1639
url: /es/aspose.slides/icell/
---
## ICell clase

Representa una celda en una tabla.

```cpp
class ICell : public Aspose::Slides::ISlideComponent
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor al estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque, según IEC 60559:1989, NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque, según IEC 60559:1989, NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para uso interno. |
| virtual **bool** [get_AnchorCenter](./get_anchorcenter/)() | Determina si el cuadro de texto está centrado dentro de una celda. Lectura **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICellFormat](../icellformat/)\> [get_CellFormat](./get_cellformat/)() | Devuelve el objeto [CellFormat](../cellformat/) que contiene propiedades de formato para esta celda. Solo lectura [ICellFormat](../icellformat/). |
| virtual **int32_t** [get_ColSpan](./get_colspan/)() | Devuelve el número de columnas de cuadrícula en la cuadrícula de tabla del padre que debe abarcar la celda actual. Esta propiedad permite que las celdas parezcan fusionadas, ya que abarcan los límites verticales de otras celdas en la tabla. Solo lectura **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColumn](../icolumn/)\> [get_FirstColumn](./get_firstcolumn/)() | Obtiene la primera columna de la celda. Solo lectura [IColumn](../icolumn/). |
| virtual **int32_t** [get_FirstColumnIndex](./get_firstcolumnindex/)() | Devuelve el índice de la primera columna cubierta por la celda. Solo lectura **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IRow](../irow/)\> [get_FirstRow](./get_firstrow/)() | Obtiene la primera fila de la celda. Solo lectura [IRow](../irow/). |
| virtual **int32_t** [get_FirstRowIndex](./get_firstrowindex/)() | Devuelve el índice de la primera fila cubierta por la celda. Solo lectura **int32_t**. |
| virtual **double** [get_Height](./get_height/)() | Devuelve la altura de la celda. Solo lectura **double**. |
| virtual **bool** [get_IsMergedCell](./get_ismergedcell/)() | Devuelve verdadero si la celda está fusionada con alguna celda ajustada, falso en caso contrario. Solo lectura **bool**. |
| virtual **double** [get_MarginBottom](./get_marginbottom/)() | Devuelve el margen inferior en un [TextFrame](../textframe/). Lectura **double**. |
| virtual **double** [get_MarginLeft](./get_marginleft/)() | Devuelve el margen izquierdo en un [TextFrame](../textframe/). Lectura **double**. |
| virtual **double** [get_MarginRight](./get_marginright/)() | Devuelve el margen derecho en un [TextFrame](../textframe/). Lectura **double**. |
| virtual **double** [get_MarginTop](./get_margintop/)() | Devuelve el margen superior en un [TextFrame](../textframe/). Lectura **double**. |
| virtual **double** [get_MinimalHeight](./get_minimalheight/)() | Devuelve la altura mínima de una celda. Esta es la suma de las alturas mínimas de todas las filas cubiertas por la celda. Solo lectura **double**. |
| virtual **double** [get_OffsetX](./get_offsetx/)() | Devuelve la distancia desde el lado izquierdo de una tabla hasta el lado izquierdo de una celda. Solo lectura **double**. |
| virtual **double** [get_OffsetY](./get_offsety/)() | Devuelve la distancia desde el lado superior de una tabla hasta el lado superior de una celda. Solo lectura **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | Devuelve la presentación. Solo lectura [IPresentation](../ipresentation/). |
| virtual **int32_t** [get_RowSpan](./get_rowspan/)() | Devuelve el número de filas que abarca una celda fusionada. Se usa en combinación con el atributo vMerge en otras celdas para especificar la celda inicial de una fusión horizontal. Solo lectura **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | Devuelve la diapositiva base. Solo lectura [IBaseSlide](../ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITable](../itable/)\> [get_Table](./get_table/)() | Devuelve el objeto [Table](../table/) padre de una celda. Solo lectura [ITable](../itable/). |
| virtual [Aspose::Slides::TextAnchorType](../textanchortype/) [get_TextAnchorType](./get_textanchortype/)() | Devuelve el tipo de ancla de texto. Lectura [Slides::TextAnchorType](../textanchortype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../itextframe/)\> [get_TextFrame](./get_textframe/)() | Devuelve el marco de texto de una celda. Solo lectura [ITextFrame](../itextframe/). |
| virtual [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() | Devuelve el tipo de texto vertical. Lectura [Slides::TextVerticalType](../textverticaltype/). |
| virtual **double** [get_Width](./get_width/)() | Devuelve el ancho de la celda. Solo lectura **double**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociado al objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo del método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite el hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Análogo de la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Análogo del operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa la declaración C# lock() para bloquear. Llame directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo del método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. No copia nada, solo inicializa un nuevo objeto y permite la construcción de copias en subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. No copia nada, solo inicializa un nuevo objeto y permite la construcción de copias en subclases. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decrementa el contador de referencias compartidas en el valor especificado. |
| virtual void [set_AnchorCenter](./set_anchorcenter/)(**bool**) | Determina si el cuadro de texto está centrado dentro de una celda. Escritura **bool**. |
| virtual void [set_MarginBottom](./set_marginbottom/)(**double**) | Establece el margen inferior en un [TextFrame](../textframe/). Escritura **double**. |
| virtual void [set_MarginLeft](./set_marginleft/)(**double**) | Establece el margen izquierdo en un [TextFrame](../textframe/). Escritura **double**. |
| virtual void [set_MarginRight](./set_marginright/)(**double**) | Establece el margen derecho en un [TextFrame](../textframe/). Escritura **double**. |
| virtual void [set_MarginTop](./set_margintop/)(**double**) | Establece el margen superior en un [TextFrame](../textframe/). Escritura **double**. |
| virtual void [set_TextAnchorType](./set_textanchortype/)([Aspose::Slides::TextAnchorType](../textanchortype/)) | Establece el tipo de ancla de texto. Escritura [Slides::TextAnchorType](../textanchortype/). |
| virtual void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) | Establece el tipo de texto vertical. Escritura [Slides::TextVerticalType](../textverticaltype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como un puntero débil (en lugar de compartido). Permite cambiar los punteros en contenedores al modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debe llamarse directamente; use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debe llamarse directamente; use punteros inteligentes o ThisProtector. |
| virtual void [SplitByColSpan](./splitbycolspan/)(**int32_t**) | Divide la celda en dos celdas por índice de columna. |
| virtual void [SplitByHeight](./splitbyheight/)(**double**) | Divide la celda por altura. |
| virtual void [SplitByRowSpan](./splitbyrowspan/)(**int32_t**) | Divide la celda en dos celdas por índice de fila. |
| virtual void [SplitByWidth](./splitbywidth/)(**double**) | Divide la celda por ancho. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo del método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa la declaración C# lock() para desbloquear. Llame directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debe llamarse directamente; use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debe llamarse directamente; use punteros inteligentes o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |

## Ver también

* Class [ISlideComponent](../islidecomponent/)
* Namespace [Aspose::Slides](../)
* Library [Aspose.Slides](../../)