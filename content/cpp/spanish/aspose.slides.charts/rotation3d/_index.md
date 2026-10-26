---
title: Rotation3D
second_title: Referencia de API de Aspose.Slides para C++
description: Representa la rotación 3D de un gráfico.
type: docs
weight: 1327
url: /es/aspose.slides.charts/rotation3d/
---
## Rotation3D clase

Representa la rotación 3D de un gráfico.

```cpp
class Rotation3D : public Aspose::Slides::Charts::IRotation3D,
                   public Aspose::Slides::IDOMObject
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia en estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor en estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para uso interno. |
| **uint16_t** [get_DepthPercents](./get_depthpercents/)() override | Devuelve la profundidad de un gráfico 3D como un porcentaje del ancho del gráfico (entre 20 y 2000 por ciento). Leer **uint16_t**. |
| **uint16_t** [get_HeightPercents](./get_heightpercents/)() override | Especifica la altura de un gráfico 3D como un porcentaje del ancho del gráfico (entre 5 y 500 por ciento). Leer **uint16_t**. |
| **uint8_t** [get_Perspective](./get_perspective/)() override | Devuelve el valor de perspectiva (ángulo de campo de visión) para gráficos 3D (entre 0 y 240). Se ignora si el valor de la propiedad RightAngleAxes es true. Leer **uint8_t**. |
| **bool** [get_RightAngleAxes](./get_rightangleaxes/)() override | Determina si los ejes del gráfico están a ángulos rectos, en lugar de dibujarse en perspectiva. En otras palabras, determina si los ángulos de los ejes del gráfico son independientes de la rotación o elevación del gráfico. Leer **bool**. |
| **int8_t** [get_RotationX](./get_rotationx/)() override | Devuelve el grado de rotación alrededor del eje X, es decir, en la dirección Y para gráficos 3D (entre -90 y 90 grados). La propiedad coincide con el elemento 21.2.2.157 rotX (X Rotation) en ECMA-376 y con la opción "Y Rotation" en PowerPoint 2007+. Leer **int8_t**. |
| **uint16_t** [get_RotationY](./get_rotationy/)() override | Devuelve el grado de rotación alrededor del eje Y, es decir, en la dirección X para gráficos 3D (entre 0 y 360 grados). La propiedad coincide con el elemento 21.2.2.158 rotY (Y Rotation) en ECMA-376 y con la opción "X Rotation" en PowerPoint 2007+. Leer **uint16_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociado al objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo al método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite el hashing de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Análogo a la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Análogo al operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la sentencia C# lock(). Llamar directamente o usar el objeto centinela [LockContext](../../system/lockcontext/). |
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
| void [set_DepthPercents](./set_depthpercents/)(**uint16_t**) override | Establece la profundidad de un gráfico 3D como un porcentaje del ancho del gráfico (entre 20 y 2000 por ciento). Escribir **uint16_t**. |
| void [set_HeightPercents](./set_heightpercents/)(**uint16_t**) override | Especifica la altura de un gráfico 3D como un porcentaje del ancho del gráfico (entre 5 y 500 por ciento). Escribir **uint16_t**. |
| void [set_Perspective](./set_perspective/)(**uint8_t**) override | Establece el valor de perspectiva (ángulo de campo de visión) para gráficos 3D (entre 0 y 240). Se ignora si el valor de la propiedad RightAngleAxes es true. Escribir **uint8_t**. |
| void [set_RightAngleAxes](./set_rightangleaxes/)(**bool**) override | Determina si los ejes del gráfico están a ángulos rectos, en lugar de dibujarse en perspectiva. En otras palabras, determina si los ángulos de los ejes del gráfico son independientes de la rotación o elevación del gráfico. Escribir **bool**. |
| void [set_RotationX](./set_rotationx/)(**int8_t**) override | Establece el grado de rotación alrededor del eje X, es decir, en la dirección Y para gráficos 3D (entre -90 y 90 grados). La propiedad coincide con el elemento 21.2.2.157 rotX (X Rotation) en ECMA-376 y con la opción "Y Rotation" en PowerPoint 2007+. Escribir **int8_t**. |
| void [set_RotationY](./set_rotationy/)(**uint16_t**) override | Establece el grado de rotación alrededor del eje Y, es decir, en la dirección X para gráficos 3D (entre 0 y 360 grados). La propiedad coincide con el elemento 21.2.2.158 rotY (Y Rotation) en ECMA-376 y con la opción "X Rotation" en PowerPoint 2007+. Escribir **uint16_t**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como un puntero débil (en lugar de compartido). Permite cambiar los punteros en contenedores a modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo al método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la sentencia C# lock(). Llamar directamente o usar el objeto centinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |

## Ver también

* Clase [IRotation3D](../irotation3d/)
* Clase [IDOMObject](../../aspose.slides/idomobject/)
* Espacio de nombres [Aspose::Slides::Charts](../)
* Biblioteca [Aspose.Slides](../../)