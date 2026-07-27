---
title: IReflection
second_title: Referencia de API de Aspose.Slides para C++
description: Representa un efecto de reflexión.
type: docs
weight: 937
url: /es/aspose.slides.effects/ireflection/
---
## IReflection clase

Representa un efecto de reflexión.

```cpp
class IReflection : public virtual Aspose::Slides::Effects::IImageTransformOperation,
                    public Aspose::Slides::IAccessiblePVIObject<System::SharedPtr<Aspose::Slides::Effects::IReflectionEffectiveData>>
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos utilizando la semántica de C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo de C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor al estilo de C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para uso interno. |
| virtual **double** [get_BlurRadius](./get_blurradius/)() | [Blur](../blur/) radio. Lee **double**. |
| virtual **float** [get_Direction](./get_direction/)() | Dirección de la reflexión. Lee **float**. |
| virtual **double** [get_Distance](./get_distance/)() | Distancia de la reflexión. Lee **double**. |
| virtual **float** [get_EndPosAlpha](./get_endposalpha/)() | Especifica la posición final (a lo largo de la rampa del gradiente alfa) del valor alfa final (porcientos). Lee **float**. |
| virtual **float** [get_EndReflectionOpacity](./get_endreflectionopacity/)() | Opacidad final de la reflexión. (porcientos). Lee **float**. |
| virtual **float** [get_FadeDirection](./get_fadedirection/)() | Especifica la dirección para desplazar la reflexión. (ángulo). Lee **float**. |
| virtual [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() | Alineación del rectángulo. Lee [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| virtual **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() | Especifica si la reflexión debe rotar con la forma cuando la forma está rotada. Lee **bool**. |
| virtual **double** [get_ScaleHorizontal](./get_scalehorizontal/)() | Especifica el factor de escala horizontal, el escalado negativo provoca una inversión. (porcientos) Lee **double**. |
| virtual **double** [get_ScaleVertical](./get_scalevertical/)() | Especifica el factor de escala vertical, el escalado negativo provoca una inversión. (porcientos) Lee **double**. |
| virtual **double** [get_SkewHorizontal](./get_skewhorizontal/)() | Especifica el ángulo de sesgo horizontal. Lee **double**. |
| virtual **double** [get_SkewVertical](./get_skewvertical/)() | Especifica el ángulo de sesgo vertical. Lee **double**. |
| virtual **float** [get_StartPosAlpha](./get_startposalpha/)() | Especifica la posición inicial (a lo largo de la rampa del gradiente alfa) del valor alfa inicial (porcientos). Lee **float**. |
| virtual **float** [get_StartReflectionOpacity](./get_startreflectionopacity/)() | Opacidad inicial de la reflexión. (porcientos). Lee **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| virtual T [GetEffective](../../aspose.slides/iaccessiblepviobject/geteffective/)() | Obtiene los datos efectivos con la herencia aplicada. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo al método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite el hashing de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Análogo a la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Análogo al operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la declaración C# lock(). Llámese directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
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
| virtual void [set_BlurRadius](./set_blurradius/)(**double**) | [Blur](../blur/) radio. Escribe **double**. |
| virtual void [set_Direction](./set_direction/)(**float**) | Dirección de la reflexión. Escribe **float**. |
| virtual void [set_Distance](./set_distance/)(**double**) | Distancia de la reflexión. Escribe **double**. |
| virtual void [set_EndPosAlpha](./set_endposalpha/)(**float**) | Especifica la posición final (a lo largo de la rampa del gradiente alfa) del valor alfa final (porcientos). Escribe **float**. |
| virtual void [set_EndReflectionOpacity](./set_endreflectionopacity/)(**float**) | Opacidad final de la reflexión. (porcientos). Escribe **float**. |
| virtual void [set_FadeDirection](./set_fadedirection/)(**float**) | Especifica la dirección para desplazar la reflexión. (ángulo). Escribe **float**. |
| virtual void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) | Alineación del rectángulo. Escribe [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| virtual void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) | Especifica si la reflexión debe rotar con la forma cuando la forma está rotada. Escribe **bool**. |
| virtual void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) | Especifica el factor de escala horizontal, el escalado negativo provoca una inversión. (porcientos) Escribe **double**. |
| virtual void [set_ScaleVertical](./set_scalevertical/)(**double**) | Especifica el factor de escala vertical, el escalado negativo provoca una inversión. (porcientos) Escribe **double**. |
| virtual void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) | Especifica el ángulo de sesgo horizontal. Escribe **double**. |
| virtual void [set_SkewVertical](./set_skewvertical/)(**double**) | Especifica el ángulo de sesgo vertical. Escribe **double**. |
| virtual void [set_StartPosAlpha](./set_startposalpha/)(**float**) | Especifica la posición inicial (a lo largo de la rampa del gradiente alfa) del valor alfa inicial (porcientos). Escribe **float**. |
| virtual void [set_StartReflectionOpacity](./set_startreflectionopacity/)(**float**) | Opacidad inicial de la reflexión. (porcientos). Escribe **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como puntero débil (en lugar de compartido). Permite cambiar los punteros en contenedores a modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo al método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la declaración C# lock(). Llámese directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroye el objeto. Libera todas las estructuras de datos internas. |

## Ver también

* Clase [IImageTransformOperation](../iimagetransformoperation/)
* Clase [IAccessiblePVIObject](../../aspose.slides/iaccessiblepviobject/)
* Espacio de nombres [Aspose::Slides::Effects](../)
* Biblioteca [Aspose.Slides](../../)