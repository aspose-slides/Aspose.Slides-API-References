---
title: IAutoShapeLock
second_title: Referencia de API de Aspose.Slides para C++
description: Determina qué operaciones están deshabilitadas en el AutoshapeEx padre.
type: docs
weight: 1379
url: /es/aspose.slides/iautoshapelock/
---
## IAutoShapeLock clase


Determina qué operaciones están deshabilitadas en el AutoshapeEx padre.

```cpp
class IAutoShapeLock : public virtual Aspose::Slides::IBaseShapeLock
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
| virtual **bool** [get_AdjustHandlesLocked](./get_adjusthandleslocked/)() | Determina si cambiar los valores de ajuste está prohibido. Lee **bool**. |
| virtual **bool** [get_ArrowheadsLocked](./get_arrowheadslocked/)() | Determina si cambiar las cabezas de flecha está prohibido. Lee **bool**. |
| virtual **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() | Determina si una forma debe conservar la relación de aspecto al redimensionar. Lee **bool**. |
| virtual **bool** [get_EditPointsLocked](./get_editpointslocked/)() | Determina si cambiar directamente el contorno de esta forma está prohibido. Lee **bool**. |
| virtual **bool** [get_GroupingLocked](./get_groupinglocked/)() | Determina si añadir esta forma a un grupo está prohibido. Lee **bool**. |
| virtual **bool** [get_NoLocks](../ibaseshapelock/get_nolocks/)() | Devuelve true si todas las banderas de bloqueo están desactivadas. **bool** de solo lectura. |
| virtual **bool** [get_PositionLocked](./get_positionlocked/)() | Determina si mover esta forma está prohibido. Lee **bool**. |
| virtual **bool** [get_RotateLocked](./get_rotatelocked/)() | Determina si cambiar el ángulo de rotación de esta forma está prohibido. Lee **bool**. |
| virtual **bool** [get_SelectLocked](./get_selectlocked/)() | Determina si seleccionar esta forma está prohibido. Lee **bool**. |
| virtual **bool** [get_ShapeTypeLocked](./get_shapetypelocked/)() | Determina si cambiar el tipo de forma está prohibido. Lee **bool**. |
| virtual **bool** [get_SizeLocked](./get_sizelocked/)() | Determina si redimensionar esta forma está prohibido. Lee **bool**. |
| virtual **bool** [get_TextLocked](./get_textlocked/)() | Determina si editar texto está prohibido. Lee **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo al método C# [Object.GetHashCode()](../../system/object/gethashcode/). Habilita el hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Análogo a la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Análogo al operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la sentencia C# lock(). Llamar directamente o usar el objeto centinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo al método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Habilita la clonación de tipos personalizados. |
|  [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. No copia nada en realidad, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. No copia nada en realidad, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| virtual void [set_AdjustHandlesLocked](./set_adjusthandleslocked/)(**bool**) | Determina si cambiar los valores de ajuste está prohibido. Escribe **bool**. |
| virtual void [set_ArrowheadsLocked](./set_arrowheadslocked/)(**bool**) | Determina si cambiar las cabezas de flecha está prohibido. Escribe **bool**. |
| virtual void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) | Determina si una forma debe conservar la relación de aspecto al redimensionar. Escribe **bool**. |
| virtual void [set_EditPointsLocked](./set_editpointslocked/)(**bool**) | Determina si cambiar directamente el contorno de esta forma está prohibido. Escribe **bool**. |
| virtual void [set_GroupingLocked](./set_groupinglocked/)(**bool**) | Determina si añadir esta forma a un grupo está prohibido. Escribe **bool**. |
| virtual void [set_PositionLocked](./set_positionlocked/)(**bool**) | Determina si mover esta forma está prohibido. Escribe **bool**. |
| virtual void [set_RotateLocked](./set_rotatelocked/)(**bool**) | Determina si cambiar el ángulo de rotación de esta forma está prohibido. Escribe **bool**. |
| virtual void [set_SelectLocked](./set_selectlocked/)(**bool**) | Determina si seleccionar esta forma está prohibido. Escribe **bool**. |
| virtual void [set_ShapeTypeLocked](./set_shapetypelocked/)(**bool**) | Determina si cambiar el tipo de forma está prohibido. Escribe **bool**. |
| virtual void [set_SizeLocked](./set_sizelocked/)(**bool**) | Determina si redimensionar esta forma está prohibido. Escribe **bool**. |
| virtual void [set_TextLocked](./set_textlocked/)(**bool**) | Determina si editar texto está prohibido. Escribe **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como un puntero débil (en lugar de compartido). Permite cambiar punteros en contenedores al modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo al método C# [Object.ToString()](../../system/object/tostring/). Habilita la conversión de objetos personalizados a cadena. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la sentencia C# lock(). Llamar directamente o usar el objeto centinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |

## Ver también

* Clase [IBaseShapeLock](../ibaseshapelock/)
* Espacio de nombres [Aspose::Slides](../)
* Biblioteca [Aspose.Slides](../../)