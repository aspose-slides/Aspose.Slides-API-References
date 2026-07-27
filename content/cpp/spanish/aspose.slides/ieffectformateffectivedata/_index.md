---
title: IEffectFormatEffectiveData
second_title: Referencia de API de Aspose.Slides para C++
description: Objeto inmutable que contiene propiedades de formato de efecto efectivas.
type: docs
weight: 2042
url: /es/aspose.slides/ieffectformateffectivedata/
---
## IEffectFormatEffectiveData clase

Objeto inmutable que contiene propiedades de formato de efecto efectivas.

```cpp
class IEffectFormatEffectiveData : public Aspose::Slides::IEffectParamSource
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica de C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia en estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor en estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque, según IEC 60559:1989, NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque, según IEC 60559:1989, NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para propósitos internos. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IBlurEffectiveData](../../aspose.slides.effects/iblureffectivedata/)\> [get_BlurEffect](./get_blureffect/)() | Efecto de desenfoque. Solo lectura [Effects::IBlurEffectiveData](../../aspose.slides.effects/iblureffectivedata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IFillOverlayEffectiveData](../../aspose.slides.effects/ifilloverlayeffectivedata/)\> [get_FillOverlayEffect](./get_filloverlayeffect/)() | Efecto de superposición de relleno. Solo lectura [Effects::IFillOverlayEffectiveData](../../aspose.slides.effects/ifilloverlayeffectivedata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IGlowEffectiveData](../../aspose.slides.effects/igloweffectivedata/)\> [get_GlowEffect](./get_gloweffect/)() | Efecto de resplandor. Solo lectura [Effects::IGlowEffectiveData](../../aspose.slides.effects/igloweffectivedata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IInnerShadowEffectiveData](../../aspose.slides.effects/iinnershadoweffectivedata/)\> [get_InnerShadowEffect](./get_innershadoweffect/)() | Sombra interna. Solo lectura [Effects::IInnerShadowEffectiveData](../../aspose.slides.effects/iinnershadoweffectivedata/). |
| virtual **bool** [get_IsNoEffects](./get_isnoeffects/)() | Devuelve true si todos los efectos están deshabilitados (como el objeto recién creado, predeterminado [EffectFormat](../effectformat/)). Solo lectura **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IOuterShadowEffectiveData](../../aspose.slides.effects/ioutershadoweffectivedata/)\> [get_OuterShadowEffect](./get_outershadoweffect/)() | Sombra externa. Solo lectura [Effects::IOuterShadowEffectiveData](../../aspose.slides.effects/ioutershadoweffectivedata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IPresetShadowEffectiveData](../../aspose.slides.effects/ipresetshadoweffectivedata/)\> [get_PresetShadowEffect](./get_presetshadoweffect/)() | Sombra predefinida. Solo lectura [Effects::IPresetShadowEffectiveData](../../aspose.slides.effects/ipresetshadoweffectivedata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IReflectionEffectiveData](../../aspose.slides.effects/ireflectioneffectivedata/)\> [get_ReflectionEffect](./get_reflectioneffect/)() | Reflexión. Solo lectura [Effects::IReflectionEffectiveData](../../aspose.slides.effects/ireflectioneffectivedata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::ISoftEdgeEffectiveData](../../aspose.slides.effects/isoftedgeeffectivedata/)\> [get_SoftEdgeEffect](./get_softedgeeffect/)() | Borde suave. Solo lectura [Effects::ISoftEdgeEffectiveData](../../aspose.slides.effects/isoftedgeeffectivedata/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo al método [Object.GetHashCode()](../../system/object/gethashcode/) de C#. Permite el hashing de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Análogo a la llamada [System.Object.GetType()](../../system/object/gettype/) de C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Análogo al operador 'is' de C#. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la sentencia C# lock(). Llámese directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo al método [Object.MemberwiseClone()](../../system/object/memberwiseclone/) de C#. Permite la clonación de tipos personalizados. |
|  [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. Realmente no copia nada, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. Realmente no copia nada, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como puntero débil (en lugar de compartido). Permite cambiar los punteros en contenedores al modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo al método [Object.ToString()](../../system/object/tostring/) de C#. Permite convertir objetos personalizados a cadena. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la sentencia C# lock(). Llámese directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |

## Observaciones

Esta interfaz se usa junto con la interfaz [IEffectFormat](../ieffectformat/) para devolver valores de formato efectivos con herencia aplicada.

## Ver también

* Clase [IEffectParamSource](../ieffectparamsource/)
* Espacio de nombres [Aspose::Slides](../)
* Biblioteca [Aspose.Slides](../../)