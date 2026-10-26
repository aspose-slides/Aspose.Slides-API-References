---
title: Cell
second_title: Referencia de la API de Aspose.Slides for C++
description: Representa una celda de una tabla.
type: docs
weight: 300
url: /es/aspose.slides/cell/
---
## Cell clase

Representa una celda de una tabla.

```cpp
class Cell : public Aspose::Slides::IDOMObject,
             public Aspose::Slides::ICell
```

## Métodos

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica de C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia en estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor en estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aun cuando según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aun cuando según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para propósitos internos. |
| **bool** [get_AnchorCenter](./get_anchorcenter/)() override | Determina si el cuadro de texto está centrado dentro de una celda. Lee **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICellFormat](../icellformat/)\> [get_CellFormat](./get_cellformat/)() override | Devuelve el objeto [CellFormat](../cellformat/) que contiene las propiedades de formato para esta celda. Solo lectura [ICellFormat](../icellformat/). |
| **int32_t** [get_ColSpan](./get_colspan/)() override | Devuelve el número de columnas de la cuadrícula en la tabla principal que debe ser abarcado por la celda actual. Esta propiedad permite que las celdas tengan la apariencia de estar fusionadas, ya que abarcan los límites verticales de otras celdas en la tabla. Solo lectura **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IColumn](../icolumn/)\> [get_FirstColumn](./get_firstcolumn/)() override | Obtiene la primera columna de la celda. Solo lectura [IColumn](../icolumn/). |
| **int32_t** [get_FirstColumnIndex](./get_firstcolumnindex/)() override | Devuelve el índice de la primera columna cubierto por la celda. Solo lectura **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IRow](../irow/)\> [get_FirstRow](./get_firstrow/)() override | Obtiene la primera fila de la celda. Solo lectura [IRow](../irow/). |
| **int32_t** [get_FirstRowIndex](./get_firstrowindex/)() override | Devuelve el índice de la primera fila cubierto por la celda. Solo lectura **int32_t**. |
| **double** [get_Height](./get_height/)() override | Devuelve la altura de la celda. Solo lectura **double**. |
| **bool** [get_IsMergedCell](./get_ismergedcell/)() override | Devuelve verdadero si la celda está fusionada con alguna celda ajustada, falso en caso contrario. Solo lectura **bool**. |
| **double** [get_MarginBottom](./get_marginbottom/)() override | Devuelve el margen inferior en un [TextFrame](../textframe/). Lee **double**. |
| **double** [get_MarginLeft](./get_marginleft/)() override | Devuelve el margen izquierdo en un [TextFrame](../textframe/). Lee **double**. |
| **double** [get_MarginRight](./get_marginright/)() override | Devuelve el margen derecho en un [TextFrame](../textframe/). Lee **double**. |
| **double** [get_MarginTop](./get_margintop/)() override | Devuelve el margen superior en un [TextFrame](../textframe/). Lee **double**. |
| **double** [get_MinimalHeight](./get_minimalheight/)() override | Devuelve la altura mínima de una celda. Esto es la suma de las alturas mínimas de todas las filas cubiertas por la celda. Solo lectura **double**. |
| **double** [get_OffsetX](./get_offsetx/)() override | Devuelve la distancia desde el lado izquierdo de una tabla hasta el lado izquierdo de una celda. Solo lectura **double**. |
| **double** [get_OffsetY](./get_offsety/)() override | Devuelve la distancia desde el lado superior de una tabla hasta el lado superior de una celda. Solo lectura **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](./get_presentation/)() override | Devuelve la presentación principal de una celda. Solo lectura [IPresentation](../ipresentation/). |
| **int32_t** [get_RowSpan](./get_rowspan/)() override | Devuelve el número de filas que una celda fusionada abarca. Esto se usa en combinación con el atributo vMerge en otras celdas para especificar la celda inicial de una fusión horizontal. Solo lectura **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](./get_slide/)() override | Devuelve la diapositiva principal de una celda. Solo lectura [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITable](../itable/)\> [get_Table](./get_table/)() override | Devuelve el objeto [Table](../table/) principal para una celda. Solo lectura [ITable](../itable/). |
| [Aspose::Slides::TextAnchorType](../textanchortype/) [get_TextAnchorType](./get_textanchortype/)() override | Devuelve el tipo de anclaje de texto. Lee [Slides::TextAnchorType](../textanchortype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../itextframe/)\> [get_TextFrame](./get_textframe/)() override | Devuelve el marco de texto de una celda. Solo lectura [ITextFrame](../itextframe/). |
| [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() override | Devuelve el tipo de texto vertical. Lee [Slides::TextVerticalType](../textverticaltype/). |
| **double** [get_Width](./get_width/)() override | Devuelve el ancho de la celda. Solo lectura **double**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada con el objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del método C# [Object.GetHashCode()](../../system/object/gethashcode/). Habilita el hashing de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Analogo de la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica si el objeto representa una instancia del tipo descrito por targetType. Analogo del operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la instrucción C# lock(). Llámese directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Habilita la clonación de tipos personalizados. |
| [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. No copia nada realmente, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. No copia nada realmente, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| void [set_AnchorCenter](./set_anchorcenter/)(**bool**) override | Determina si el cuadro de texto está centrado dentro de una celda. Escribe **bool**. |
| void [set_MarginBottom](./set_marginbottom/)(**double**) override | Establece el margen inferior en un [TextFrame](../textframe/). Escribe **double**. |
| void [set_MarginLeft](./set_marginleft/)(**double**) override | Establece el margen izquierdo en un [TextFrame](../textframe/). Escribe **double**. |
| void [set_MarginRight](./set_marginright/)(**double**) override | Establece el margen derecho en un [TextFrame](../textframe/). Escribe **double**. |
| void [set_MarginTop](./set_margintop/)(**double**) override | Establece el margen superior en un [TextFrame](../textframe/). Escribe **double**. |
| void [set_TextAnchorType](./set_textanchortype/)([Aspose::Slides::TextAnchorType](../textanchortype/)) override | Establece el tipo de anclaje de texto. Escribe [Slides::TextAnchorType](../textanchortype/). |
| void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) override | Establece el tipo de texto vertical. Escribe [Slides::TextVerticalType](../textverticaltype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como un puntero débil (en lugar de compartido). Permite cambiar los punteros en contenedores a modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [SplitByColSpan](./splitbycolspan/)(**int32_t**) override | Divide la celda en dos celdas por el índice de la columna. |
| void [SplitByHeight](./splitbyheight/)(**double**) override | Divide la celda por altura. |
| void [SplitByRowSpan](./splitbyrowspan/)(**int32_t**) override | Divide la celda en dos celdas por el índice de la fila. |
| void [SplitByWidth](./splitbywidth/)(**double**) override | Divide la celda por anchura. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del método C# [Object.ToString()](../../system/object/tostring/). Habilita la conversión de objetos personalizados a cadena. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la instrucción C# lock(). Llámese directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |

## Ver también

* Clase [IDOMObject](../idomobject/)
* Clase [ICell](../icell/)
* Espacio de nombres [Aspose::Slides](../)
* Biblioteca [Aspose.Slides](../../)