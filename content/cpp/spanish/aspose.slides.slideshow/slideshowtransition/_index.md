---
title: SlideShowTransition
second_title: Referencia de API de Aspose.Slides para C++
description: Representa la transición de la presentación de diapositivas.
type: docs
weight: 404
url: /es/aspose.slides.slideshow/slideshowtransition/
---
## SlideShowTransition clase

Representa la transición de la presentación de diapositivas.

```cpp
class SlideShowTransition : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::BaseSlide>>,
                            public Aspose::Slides::ISlideShowTransition
```

## Métodos

| Método | Descripción |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Determina si las dos instancias [SlideShowTransition](./) son iguales. Lectura/escritura **bool**. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para uso interno. |
| **bool** [get_AdvanceAfter](./get_advanceafter/)() override | Este atributo especifica si la presentación avanzará a la diapositiva siguiente después de un tiempo determinado. Lectura **bool**. |
| **uint32_t** [get_AdvanceAfterTime](./get_advanceaftertime/)() override | Especifica el tiempo, en milisegundos, después del cual debe iniciarse la transición. Esta configuración puede usarse junto con el atributo advClick. Si este atributo no se especifica, se asume que no habrá avance automático. Lectura **uint32_t**. |
| **bool** [get_AdvanceOnClick](./get_advanceonclick/)() override | Especifica si un clic del ratón avanzará la diapositiva o no. Si este atributo no se especifica, se asume un valor verdadero. Lectura **bool**. |
| **int32_t** [get_Duration](./get_duration/)() override | Obtiene la duración del efecto de transición de diapositiva en milisegundos. Lectura **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../../aspose.slides/iaudio/)\> [get_Sound](./get_sound/)() override | Devuelve los datos de audio incrustados. Lectura [IAudio](../../aspose.slides/iaudio/). |
| **bool** [get_SoundIsBuiltIn](./get_soundisbuiltin/)() override | Especifica si este sonido es un sonido incorporado o no. Si este atributo se establece en verdadero, la aplicación generadora se alerta para comprobar el atributo name especificado para este sonido en su lista de sonidos incorporados y puede entonces presentar un nombre o interfaz personalizada según sea necesario. Lectura **bool**. |
| **bool** [get_SoundLoop](./get_soundloop/)() override | Este atributo especifica si el sonido se reproducirá en bucle hasta que ocurra el siguiente evento de sonido en la presentación. Lectura **bool**. |
| [TransitionSoundMode](../transitionsoundmode/) [get_SoundMode](./get_soundmode/)() override | Establece o devuelve el modo de sonido para la transición de diapositiva. Lectura [TransitionSoundMode](../transitionsoundmode/). |
| [System::String](../../system/string/) [get_SoundName](./get_soundname/)() override | Especifica un nombre legible por humanos para el sonido de la transición. El [ISlideShowTransition::set_Sound](../../aspose.slides/islideshowtransition/set_sound/) debe asignarse para obtener o establecer el nombre del sonido. Lectura [System::String](../../system/string/). |
| [TransitionSpeed](../transitionspeed/) [get_Speed](./get_speed/)() override | Especifica la velocidad de transición que se usará al pasar de la diapositiva actual a la siguiente. Lectura [TransitionSpeed](../transitionspeed/). |
| [TransitionType](../transitiontype/) [get_Type](./get_type/)() override | Tipo de transición. Lectura [TransitionType](../transitiontype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITransitionValueBase](../itransitionvaluebase/)\> [get_Value](./get_value/)() override | [Slide](../../aspose.slides/slide/) muestra el valor de transición. Solo lectura [ITransitionValueBase](../itransitionvaluebase/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Sirve como función hash para un tipo particular, adecuada para su uso en algoritmos de hash y estructuras de datos como una tabla hash. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Análogo a la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Análogo al operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la instrucción C# lock(). Llamar directamente o usar el objeto centinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo al método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
| [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. En realidad no copia nada, solo inicializa un nuevo objeto y permite la construcción de copias en subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. En realidad no copia nada, solo inicializa un nuevo objeto y permite la construcción de copias en subclases. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| void [set_AdvanceAfter](./set_advanceafter/)(**bool**) override | Este atributo especifica si la presentación avanzará a la diapositiva siguiente después de un tiempo determinado. Escritura **bool**. |
| void [set_AdvanceAfterTime](./set_advanceaftertime/)(**uint32_t**) override | Especifica el tiempo, en milisegundos, después del cual debe iniciarse la transición. Esta configuración puede usarse junto con el atributo advClick. Si este atributo no se especifica, se asume que no habrá avance automático. Escritura **uint32_t**. |
| void [set_AdvanceOnClick](./set_advanceonclick/)(**bool**) override | Especifica si un clic del ratón avanzará la diapositiva o no. Si este atributo no se especifica, se asume un valor verdadero. Escritura **bool**. |
| void [set_Duration](./set_duration/)(**int32_t**) override | Establece la duración del efecto de transición de diapositiva en milisegundos. Escritura **int32_t**. |
| void [set_Sound](./set_sound/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../../aspose.slides/iaudio/)\>) override | Establece los datos de audio incrustados. Escritura [IAudio](../../aspose.slides/iaudio/). |
| void [set_SoundIsBuiltIn](./set_soundisbuiltin/)(**bool**) override | Especifica si este sonido es un sonido incorporado o no. Si este atributo se establece en verdadero, la aplicación generadora se alerta para comprobar el atributo name especificado para este sonido en su lista de sonidos incorporados y puede entonces presentar un nombre o interfaz personalizada según sea necesario. Escritura **bool**. |
| void [set_SoundLoop](./set_soundloop/)(**bool**) override | Este atributo especifica si el sonido se reproducirá en bucle hasta que ocurra el siguiente evento de sonido en la presentación. Escritura **bool**. |
| void [set_SoundMode](./set_soundmode/)([TransitionSoundMode](../transitionsoundmode/)) override | Establece o devuelve el modo de sonido para la transición de diapositiva. Escritura [TransitionSoundMode](../transitionsoundmode/). |
| void [set_SoundName](./set_soundname/)([System::String](../../system/string/)) override | Especifica un nombre legible por humanos para el sonido de la transición. El [ISlideShowTransition::set_Sound](../../aspose.slides/islideshowtransition/set_sound/) debe asignarse para obtener o establecer el nombre del sonido. Escritura [System::String](../../system/string/). |
| void [set_Speed](./set_speed/)([TransitionSpeed](../transitionspeed/)) override | Especifica la velocidad de transición que se usará al pasar de la diapositiva actual a la siguiente. Escritura [TransitionSpeed](../transitionspeed/). |
| void [set_Type](./set_type/)([TransitionType](../transitiontype/)) override | Tipo de transición. Escritura [TransitionType](../transitiontype/). |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Establece el n-ésimo argumento de plantilla como un puntero débil (en lugar de compartido). Permite cambiar punteros en contenedores a modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo al método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la instrucción C# lock(). Llamar directamente o usar el objeto centinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |

## Ver también

* Clase [DomObject](../../aspose.slides/domobject/)
* Clase [ISlideShowTransition](../../aspose.slides/islideshowtransition/)
* Espacio de nombres [Aspose::Slides::SlideShow](../)
* Biblioteca [Aspose.Slides](../../)