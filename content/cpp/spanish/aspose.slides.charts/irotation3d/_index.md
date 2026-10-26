---
title: IRotation3D
second_title: Referencia de API de Aspose.Slides para C++
description: Representa la rotación 3D de un gráfico.
type: docs
weight: 1171
url: /es/aspose.slides.charts/irotation3d/
---
## IRotation3D clase

Representa la rotación 3D de un gráfico.

```cpp
class IRotation3D : public virtual System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia en estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor en estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque, según IEC 60559:1989, NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque, según IEC 60559:1989, NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para propósitos internos. |
| virtual **uint16_t** [get_DepthPercents](./get_depthpercents/)() | Devuelve la profundidad de un gráfico 3D como porcentaje del ancho del gráfico (entre 20 y 2000 por ciento). Lectura **uint16_t**. |
| virtual **uint16_t** [get_HeightPercents](./get_heightpercents/)() | Especifica la altura de un gráfico 3D como porcentaje del ancho del gráfico (entre 5 y 500 por ciento). Lectura **uint16_t**. |
| virtual **uint8_t** [get_Perspective](./get_perspective/)() | Devuelve el valor de perspectiva (ángulo de campo de visión) para gráficos 3D (entre 0 y 100). Se ignora si el valor de la propiedad RightAngleAxes es true. Lectura **uint8_t**. |
| virtual **bool** [get_RightAngleAxes](./get_rightangleaxes/)() | Determina si los ejes del gráfico están en ángulos rectos, en lugar de dibujados en perspectiva. En otras palabras, determina si los ángulos de los ejes del gráfico son independientes de la rotación o elevación del gráfico. Lectura **bool**. |
| virtual **int8_t** [get_RotationX](./get_rotationx/)() | Devuelve el grado de rotación alrededor del eje X, es decir, en la dirección Y para gráficos 3D (entre -90 y 90 grados). La propiedad coincide con el elemento 21.2.2.157 rotX (Rotación X) en ECMA-376 y con la opción "Y Rotation" en PowerPoint 2007+. Lectura **int8_t**. |
| virtual **uint16_t** [get_RotationY](./get_rotationy/)() | Devuelve el grado de rotación alrededor del eje Y, es decir, en la dirección X para gráficos 3D (entre 0 y 360 grados). La propiedad coincide con el elemento 21.2.2.158 rotY (Rotación Y) en ECMA-376 y con la opción "X Rotation" en PowerPoint 2007+. Lectura **uint16_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo del método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite el hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Análogo a la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Análogo al operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la sentencia C# lock(). Llamar directamente o usar el objeto centinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo del método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. En realidad no copia nada, solo inicializa un nuevo objeto y permite la construcción de copias de subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. En realidad no copia nada, solo inicializa un nuevo objeto y permite la construcción de copias de subclases. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de string y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| virtual void [set_DepthPercents](./set_depthpercents/)(**uint16_t**) | Establece la profundidad de un gráfico 3D como porcentaje del ancho del gráfico (entre 20 y 2000 por ciento). Escritura **uint16_t**. |
| virtual void [set_HeightPercents](./set_heightpercents/)(**uint16_t**) | Especifica la altura de un gráfico 3D como porcentaje del ancho del gráfico (entre 5 y 500 por ciento). Escritura **uint16_t**. |
| virtual void [set_Perspective](./set_perspective/)(**uint8_t**) | Establece el valor de perspectiva (ángulo de campo de visión) para gráficos 3D (entre 0 y 100). Se ignora si el valor de la propiedad RightAngleAxes es true. Escritura **uint8_t**. |
| virtual void [set_RightAngleAxes](./set_rightangleaxes/)(**bool**) | Determina si los ejes del gráfico están en ángulos rectos, en lugar de dibujados en perspectiva. En otras palabras, determina si los ángulos de los ejes del gráfico son independientes de la rotación o elevación del gráfico. Escritura **bool**. |
| virtual void [set_RotationX](./set_rotationx/)(**int8_t**) | Establece el grado de rotación alrededor del eje X, es decir, en la dirección Y para gráficos 3D (entre -90 y 90 grados). La propiedad coincide con el elemento 21.2.2.157 rotX (Rotación X) en ECMA-376 y con la opción "Y Rotation" en PowerPoint 2007+. Escritura **int8_t**. |
| virtual void [set_RotationY](./set_rotationy/)(**uint16_t**) | Establece el grado de rotación alrededor del eje Y, es decir, en la dirección X para gráficos 3D (entre 0 y 360 grados). La propiedad coincide con el elemento 21.2.2.158 rotY (Rotación Y) en ECMA-376 y con la opción "X Rotation" en PowerPoint 2007+. Escritura **uint16_t**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como puntero débil (en lugar de compartido). Permite cambiar punteros en contenedores a modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo del método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la sentencia C# lock(). Llamar directamente o usar el objeto centinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |

## Ver también

* Clase [Object](../../system/object/)
* Espacio de nombres [Aspose::Slides::Charts](../)
* Biblioteca [Aspose.Slides](../../)