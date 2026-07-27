---
title: Reflection
second_title: Referencia de la API de Aspose.Slides para C++
description: Representa un efecto de reflexión.
type: docs
weight: 1067
url: /es/aspose.slides.effects/reflection/
---
## Reflection clase

Representa un efecto [Reflection](./).

```cpp
class Reflection : public Aspose::Slides::Effects::IReflection,
                   public Aspose::Slides::Effects::IVisualEffect,
                   public Aspose::Slides::IPVIObject
```

## Métodos

| Método | Descripción |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Determina si el [Reflection](./) especificado es igual al [Reflection](./) actual. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica [Object.Equals](../../system/object/equals/) de C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo de C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo de C# donde dos NaN se consideran iguales aunque, según IEC 60559:1989, NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo de C# donde dos NaN se consideran iguales aunque, según IEC 60559:1989, NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para uso interno. |
| **double** [get_BlurRadius](./get_blurradius/)() override | [Blur](../blur/) radio. Leer **double**. |
| **float** [get_Direction](./get_direction/)() override | Dirección de la reflexión. Leer **float**. |
| **double** [get_Distance](./get_distance/)() override | Distancia de la reflexión. Leer **double**. |
| **float** [get_EndPosAlpha](./get_endposalpha/)() override | Especifica la posición final (a lo largo de la rampa de gradiente alfa) del valor alfa final (porcentajes). Leer **float**. |
| **float** [get_EndReflectionOpacity](./get_endreflectionopacity/)() override | Opacidad final de la reflexión. (porcentajes). Leer **float**. |
| **float** [get_FadeDirection](./get_fadedirection/)() override | Especifica la dirección para desplazar la reflexión. (ángulo). Leer **float**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../../aspose.slides/ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../../aspose.slides/ipviobject/get_parent_ipresentationcomponent/)() | Devuelve el [IPresentationComponent](../../aspose.slides/ipresentationcomponent/) padre. Solo lectura [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). |
| [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() override | Alineación del rectángulo. Lectura [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() override | Especifica si la reflexión debe rotar con la forma cuando la forma está rotada. Leer **bool**. |
| **double** [get_ScaleHorizontal](./get_scalehorizontal/)() override | Especifica el factor de escala horizontal, una escala negativa provoca una inversión. (porcentajes) Leer **double**. |
| **double** [get_ScaleVertical](./get_scalevertical/)() override | Especifica el factor de escala vertical, una escala negativa provoca una inversión. (porcentajes) Leer **double**. |
| **double** [get_SkewHorizontal](./get_skewhorizontal/)() override | Especifica el ángulo de sesgo horizontal. Leer **double**. |
| **double** [get_SkewVertical](./get_skewvertical/)() override | Especifica el ángulo de sesgo vertical. Leer **double**. |
| **float** [get_StartPosAlpha](./get_startposalpha/)() override | Especifica la posición inicial (a lo largo de la rampa de gradiente alfa) del valor alfa inicial (porcentajes). Leer **float**. |
| **float** [get_StartReflectionOpacity](./get_startreflectionopacity/)() override | Opacidad inicial de la reflexión. (porcentajes). Leer **float**. |
| virtual ASPOSE_SLIDES_LOCAL_API **uint32_t** [get_Version](../../aspose.slides/ipviobject/get_version/)() | Versión. Solo lectura **uint32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| [System::SharedPtr](../../system/sharedptr/)\<[IReflectionEffectiveData](../ireflectioneffectivedata/)\> [GetEffective](./geteffective/)() override | Obtiene los datos efectivos del efecto [Reflection](./) con la herencia aplicada. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Funciona como una función hash para un tipo particular. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Análogo a la llamada [System.Object.GetType()](../../system/object/gettype/) de C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Análogo al operador 'is' de C#. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la instrucción C# lock(). Llamar directamente o usar el objeto centinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo al método [Object.MemberwiseClone()](../../system/object/memberwiseclone/) de C#. Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. En realidad no copia nada, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. En realidad no copia nada, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| void [set_BlurRadius](./set_blurradius/)(**double**) override | [Blur](../blur/) radio. Escritura **double**. |
| void [set_Direction](./set_direction/)(**float**) override | Dirección de la reflexión. Escritura **float**. |
| void [set_Distance](./set_distance/)(**double**) override | Distancia de la reflexión. Escritura **double**. |
| void [set_EndPosAlpha](./set_endposalpha/)(**float**) override | Especifica la posición final (a lo largo de la rampa de gradiente alfa) del valor alfa final (porcentajes). Escritura **float**. |
| void [set_EndReflectionOpacity](./set_endreflectionopacity/)(**float**) override | Opacidad final de la reflexión. (porcentajes). Escritura **float**. |
| void [set_FadeDirection](./set_fadedirection/)(**float**) override | Especifica la dirección para desplazar la reflexión. (ángulo). Escritura **float**. |
| void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) override | Alineación del rectángulo. Escritura [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) override | Especifica si la reflexión debe rotar con la forma cuando la forma está rotada. Escritura **bool**. |
| void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) override | Especifica el factor de escala horizontal, una escala negativa provoca una inversión. (porcentajes) Escritura **double**. |
| void [set_ScaleVertical](./set_scalevertical/)(**double**) override | Especifica el factor de escala vertical, una escala negativa provoca una inversión. (porcentajes) Escritura **double**. |
| void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) override | Especifica el ángulo de sesgo horizontal. Escritura **double**. |
| void [set_SkewVertical](./set_skewvertical/)(**double**) override | Especifica el ángulo de sesgo vertical. Escritura **double**. |
| void [set_StartPosAlpha](./set_startposalpha/)(**float**) override | Especifica la posición inicial (a lo largo de la rampa de gradiente alfa) del valor alfa inicial (porcentajes). Escritura **float**. |
| void [set_StartReflectionOpacity](./set_startreflectionopacity/)(**float**) override | Opacidad inicial de la reflexión. (porcentajes). Escritura **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como un puntero débil (en lugar de compartido). Permite cambiar los punteros en contenedores a modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo al método [Object.ToString()](../../system/object/tostring/) de C#. Permite convertir objetos personalizados a cadena. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la instrucción C# lock(). Llamar directamente o usar el objeto centinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |

## Ver también

* Clase [IReflection](../ireflection/)
* Clase [IVisualEffect](../ivisualeffect/)
* Clase [IPVIObject](../../aspose.slides/ipviobject/)
* Espacio de nombres [Aspose::Slides::Effects](../)
* Biblioteca [Aspose.Slides](../../)