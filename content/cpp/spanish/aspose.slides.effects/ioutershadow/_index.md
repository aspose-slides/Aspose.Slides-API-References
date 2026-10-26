---
title: IOuterShadow
second_title: Referencia de la API de Aspose.Slides para C++
description: Representa un efecto de sombra exterior.
type: docs
weight: 885
url: /es/aspose.slides.effects/ioutershadow/
---
## IOuterShadow clase

Representa un efecto de sombra exterior.

```cpp
class IOuterShadow : public virtual Aspose::Slides::Effects::IImageTransformOperation,
                     public Aspose::Slides::IAccessiblePVIObject<System::SharedPtr<Aspose::Slides::Effects::IOuterShadowEffectiveData>>
```

## Métodos

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia en estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor en estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque, según IEC 60559:1989, NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque, según IEC 60559:1989, NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para uso interno. |
| virtual **double** [get_BlurRadius](./get_blurradius/)() | [Blur](../blur/) radio, en puntos. Valor predeterminado – 0 pt. Lectura **double**. |
| virtual **float** [get_Direction](./get_direction/)() | Dirección de la sombra, en grados. Valor predeterminado – 0 ° (izquierda a derecha). Lectura **float**. |
| virtual **double** [get_Distance](./get_distance/)() | Distancia de la sombra al objeto, en puntos. Valor predeterminado – 0 pt. Lectura **double**. |
| virtual [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() | Alineación del rectángulo. Valor predeterminado – [RectangleAlignment::Bottom](../../aspose.slides/rectanglealignment/). Lectura [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| virtual **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() | Indica si la sombra rota junto con la forma. Valor predeterminado – true. Lectura **bool**. |
| virtual **double** [get_ScaleHorizontal](./get_scalehorizontal/)() | Factor de escala horizontal, en porcentaje del tamaño original. Un escalado negativo causa una rotación. Valor predeterminado – 100 %. Lectura **double**. |
| virtual **double** [get_ScaleVertical](./get_scalevertical/)() | Factor de escala vertical, en porcentaje del tamaño original. Un escalado negativo causa una rotación. Valor predeterminado – 100 %. Lectura **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_ShadowColor](./get_shadowcolor/)() | Color de la sombra. Valor predeterminado – negro automático (dependiendo del tema). Solo lectura [IColorFormat](../../aspose.slides/icolorformat/). |
| virtual **double** [get_SkewHorizontal](./get_skewhorizontal/)() | Ángulo de sesgo horizontal, en grados. Valor predeterminado – 0 °. Lectura **double**. |
| virtual **double** [get_SkewVertical](./get_skewvertical/)() | Ángulo de sesgo vertical, en grados. Valor predeterminado – 0 °. Lectura **double**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| virtual T [GetEffective](../../aspose.slides/iaccessiblepviobject/geteffective/)() | Obtiene los datos efectivos con la herencia aplicada. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo al método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite el hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Análogo a la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Análogo al operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la sentencia C# lock(). Llame directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo al método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. Realmente no copia nada, solo inicializa un nuevo objeto y permite la copia de construcción de subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. Realmente no copia nada, solo inicializa un nuevo objeto y permite la copia de construcción de subclases. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| virtual void [set_BlurRadius](./set_blurradius/)(**double**) | [Blur](../blur/) radio, en puntos. Valor predeterminado – 0 pt. Escritura **double**. |
| virtual void [set_Direction](./set_direction/)(**float**) | Dirección de la sombra, en grados. Valor predeterminado – 0 ° (izquierda a derecha). Escritura **float**. |
| virtual void [set_Distance](./set_distance/)(**double**) | Distancia de la sombra al objeto, en puntos. Valor predeterminado – 0 pt. Escritura **double**. |
| virtual void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) | Alineación del rectángulo. Valor predeterminado – [RectangleAlignment::Bottom](../../aspose.slides/rectanglealignment/). Escritura [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| virtual void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) | Indica si la sombra rota junto con la forma. Valor predeterminado – true. Escritura **bool**. |
| virtual void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) | Factor de escala horizontal, en porcentaje del tamaño original. Un escalado negativo causa una rotación. Valor predeterminado – 100 %. Escritura **double**. |
| virtual void [set_ScaleVertical](./set_scalevertical/)(**double**) | Factor de escala vertical, en porcentaje del tamaño original. Un escalado negativo causa una rotación. Valor predeterminado – 100 %. Escritura **double**. |
| virtual void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) | Ángulo de sesgo horizontal, en grados. Valor predeterminado – 0 °. Escritura **double**. |
| virtual void [set_SkewVertical](./set_skewvertical/)(**double**) | Ángulo de sesgo vertical, en grados. Valor predeterminado – 0 °. Escritura **double**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como un puntero débil (en lugar de compartido). Permite cambiar los punteros en contenedores al modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo al método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la sentencia C# lock(). Llame directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |

## Ver también

* Clase [IImageTransformOperation](../iimagetransformoperation/)
* Clase [IAccessiblePVIObject](../../aspose.slides/iaccessiblepviobject/)
* Espacio de nombres [Aspose::Slides::Effects](../)
* Biblioteca [Aspose.Slides](../../)