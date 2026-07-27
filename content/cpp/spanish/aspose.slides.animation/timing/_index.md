---
title: Timing
second_title: Referencia de API de Aspose.Slides para C++
description: Representa la sincronización de animación.
type: docs
weight: 625
url: /es/aspose.slides.animation/timing/
---
## Timing clase

Representa la sincronización de animación.

```cpp
class Timing : public Aspose::Slides::Animation::ITiming,
               public Aspose::Slides::IDOMObject
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica de C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia en estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor en estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaNs se consideran iguales aunque, según IEC 60559:1989, NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaNs se consideran iguales aunque, según IEC 60559:1989, NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para propósitos internos. |
| **float** [get_Accelerate](./get_accelerate/)() override | Describe el porcentaje de la duración del efecto de aceleración. Lee **float**. |
| **bool** [get_AutoReverse](./get_autoreverse/)() override | Describe si reproducir automáticamente la animación en reversa después de reproducirla en dirección normal. Lee **bool**. |
| **float** [get_Decelerate](./get_decelerate/)() override | Describe el porcentaje de la duración del efecto de desaceleración. Lee **float**. |
| **float** [get_Duration](./get_duration/)() override | Describe la duración del efecto de animación. Lee **float**. |
| **float** [get_RepeatCount](./get_repeatcount/)() override | Describe el número de veces que el efecto debe repetirse. Lee **float**. |
| **float** [get_RepeatDuration](./get_repeatduration/)() override | Describe el número de veces que el efecto debe repetirse. Lee **float**. |
| **bool** [get_RepeatUntilEndSlide](./get_repeatuntilendslide/)() override | Este atributo especifica si el efecto se repetirá hasta el final de la diapositiva. Lee **bool**. |
| **bool** [get_RepeatUntilNextClick](./get_repeatuntilnextclick/)() override | Este atributo especifica si el efecto se repetirá hasta el siguiente clic. Lee **bool**. |
| [EffectRestartType](../effectrestarttype/) [get_Restart](./get_restart/)() override | Especifica si un efecto debe reiniciarse después de completarse. Lee [EffectRestartType](../effectrestarttype/). |
| **bool** [get_Rewind](./get_rewind/)() override | Este atributo especifica si el efecto retrocederá cuando haya terminado de reproducirse. Lee **bool**. |
| **float** [get_Speed](./get_speed/)() override | Especifica el porcentaje en que acelerar (o ralentizar) la sincronización. Lee **float**. |
| **float** [get_TriggerDelayTime](./get_triggerdelaytime/)() override | Describe el tiempo de retardo después del disparador. Lee **float**. |
| [EffectTriggerType](../effecttriggertype/) [get_TriggerType](./get_triggertype/)() override | Describe el tipo de disparador. Lee [EffectTriggerType](../effecttriggertype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociado al objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo al método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite el hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Análogo a la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Análogo al operador 'is' de C#. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la sentencia C# lock(). Llámese directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo al método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. En realidad no copia nada, solo inicializa un nuevo objeto y permite la copia de construcción de subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. En realidad no copia nada, solo inicializa un nuevo objeto y permite la copia de construcción de subclases. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el conteo de referencias compartidas en el valor especificado. |
| void [set_Accelerate](./set_accelerate/)(**float**) override | Describe el porcentaje de la duración del efecto de aceleración. Escribe **float**. |
| void [set_AutoReverse](./set_autoreverse/)(**bool**) override | Describe si reproducir automáticamente la animación en reversa después de reproducirla en dirección normal. Escribe **bool**. |
| void [set_Decelerate](./set_decelerate/)(**float**) override | Describe el porcentaje de la duración del efecto de desaceleración. Escribe **float**. |
| void [set_Duration](./set_duration/)(**float**) override | Describe la duración del efecto de animación. Escribe **float**. |
| void [set_RepeatCount](./set_repeatcount/)(**float**) override | Describe el número de veces que el efecto debe repetirse. Escribe **float**. |
| void [set_RepeatDuration](./set_repeatduration/)(**float**) override | Describe el número de veces que el efecto debe repetirse. Escribe **float**. |
| void [set_RepeatUntilEndSlide](./set_repeatuntilendslide/)(**bool**) override | Este atributo especifica si el efecto se repetirá hasta el final de la diapositiva. Escribe **bool**. |
| void [set_RepeatUntilNextClick](./set_repeatuntilnextclick/)(**bool**) override | Este atributo especifica si el efecto se repetirá hasta el siguiente clic. Escribe **bool**. |
| void [set_Restart](./set_restart/)([EffectRestartType](../effectrestarttype/)) override | Especifica si un efecto debe reiniciarse después de completarse. Escribe [EffectRestartType](../effectrestarttype/). |
| void [set_Rewind](./set_rewind/)(**bool**) override | Este atributo especifica si el efecto retrocederá cuando haya terminado de reproducirse. Escribe **bool**. |
| void [set_Speed](./set_speed/)(**float**) override | Especifica el porcentaje en que acelerar (o ralentizar) la sincronización. Escribe **float**. |
| void [set_TriggerDelayTime](./set_triggerdelaytime/)(**float**) override | Describe el tiempo de retardo después del disparador. Escribe **float**. |
| void [set_TriggerType](./set_triggertype/)([EffectTriggerType](../effecttriggertype/)) override | Describe el tipo de disparador. Escribe [EffectTriggerType](../effecttriggertype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como un puntero débil (en lugar de compartido). Permite cambiar punteros en contenedores al modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el conteo de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el conteo de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo al método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la sentencia C# lock(). Llámese directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el conteo de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el conteo de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |

## Ver también

* Clase [ITiming](../itiming/)
* Clase [IDOMObject](../../aspose.slides/idomobject/)
* Espacio de nombres [Aspose::Slides::Animation](../)
* Biblioteca [Aspose.Slides](../../)