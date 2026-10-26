---
title: PictureFrameLock
second_title: Referencia de API de Aspose.Slides para C++
description: Determina qué operaciones están deshabilitadas en el elemento padre PictureFrame.
type: docs
weight: 4746
url: /es/aspose.slides/pictureframelock/
---
## PictureFrameLock clase

Determina qué operaciones están deshabilitadas en el elemento padre [PictureFrame](../pictureframe/).

```cpp
class PictureFrameLock : public Aspose::Slides::BaseShapeLock,
                         public Aspose::Slides::IPictureFrameLock
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor al estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para fines internos. |
| **bool** [get_AdjustHandlesLocked](./get_adjusthandleslocked/)() override | Determina si un cambio de valores de ajuste está prohibido. Lectura **bool**. |
| **bool** [get_ArrowheadsLocked](./get_arrowheadslocked/)() override | Determina si un cambio de puntas de flecha está prohibido. Lectura **bool**. |
| **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() override | Determina si una forma debe preservar la relación de aspecto al redimensionar. Lectura **bool**. |
| **bool** [get_CropLocked](./get_croplocked/)() override | Determina si el recorte de una imagen está prohibido. Lectura **bool**. |
| **bool** [get_EditPointsLocked](./get_editpointslocked/)() override | Determina si un cambio directo del contorno de esta forma está prohibido. Lectura **bool**. |
| **bool** [get_GroupingLocked](./get_groupinglocked/)() override | Determina si añadir esta forma a un grupo está prohibido. Lectura **bool**. |
| **bool** [get_NoLocks](../baseshapelock/get_nolocks/)() override | Devuelve true si todas las banderas de bloqueo están desactivadas. Solo lectura **bool**. |
| **bool** [get_PositionLocked](./get_positionlocked/)() override | Determina si mover esta forma está prohibido. Lectura **bool**. |
| **bool** [get_RotationLocked](./get_rotationlocked/)() override | Determina si cambiar el ángulo de rotación de esta forma está prohibido. Lectura **bool**. |
| **bool** [get_SelectLocked](./get_selectlocked/)() override | Determina si seleccionar esta forma está prohibido. Lectura **bool**. |
| **bool** [get_ShapeTypeLocked](./get_shapetypelocked/)() override | Determina si cambiar el tipo de una forma está prohibido. Lectura **bool**. |
| **bool** [get_SizeLocked](./get_sizelocked/)() override | Determina si redimensionar esta forma está prohibido. Lectura **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analógico del método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite generar hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Analógico de la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Analógico del operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la instrucción C# lock(). Llamar directamente o usar el objeto centinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analógico del método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. En realidad no copia nada, solo inicializa un nuevo objeto y permite la construcción de copias en subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. En realidad no copia nada, solo inicializa un nuevo objeto y permite la construcción de copias en subclases. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| void [set_AdjustHandlesLocked](./set_adjusthandleslocked/)(**bool**) override | Determina si un cambio de valores de ajuste está prohibido. Escritura **bool**. |
| void [set_ArrowheadsLocked](./set_arrowheadslocked/)(**bool**) override | Determina si un cambio de puntas de flecha está prohibido. Escritura **bool**. |
| void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) override | Determina si una forma debe preservar la relación de aspecto al redimensionar. Escritura **bool**. |
| void [set_CropLocked](./set_croplocked/)(**bool**) override | Determina si el recorte de una imagen está prohibido. Escritura **bool**. |
| void [set_EditPointsLocked](./set_editpointslocked/)(**bool**) override | Determina si un cambio directo del contorno de esta forma está prohibido. Escritura **bool**. |
| void [set_GroupingLocked](./set_groupinglocked/)(**bool**) override | Determina si añadir esta forma a un grupo está prohibido. Escritura **bool**. |
| void [set_PositionLocked](./set_positionlocked/)(**bool**) override | Determina si mover esta forma está prohibido. Escritura **bool**. |
| void [set_RotationLocked](./set_rotationlocked/)(**bool**) override | Determina si cambiar el ángulo de rotación de esta forma está prohibido. Escritura **bool**. |
| void [set_SelectLocked](./set_selectlocked/)(**bool**) override | Determina si seleccionar esta forma está prohibido. Escritura **bool**. |
| void [set_ShapeTypeLocked](./set_shapetypelocked/)(**bool**) override | Determina si cambiar el tipo de una forma está prohibido. Escritura **bool**. |
| void [set_SizeLocked](./set_sizelocked/)(**bool**) override | Determina si redimensionar esta forma está prohibido. Escritura **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como puntero débil (en lugar de compartido). Permite cambiar punteros en contenedores a modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debe llamarse directamente; use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debe llamarse directamente; use punteros inteligentes o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analógico del método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la instrucción C# lock(). Llamar directamente o usar el objeto centinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debe llamarse directamente; use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debe llamarse directamente; use punteros inteligentes o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |

## Ver también

* Clase [BaseShapeLock](../baseshapelock/)
* Clase [IPictureFrameLock](../ipictureframelock/)
* Espacio de nombres [Aspose::Slides](../)
* Biblioteca [Aspose.Slides](../../)