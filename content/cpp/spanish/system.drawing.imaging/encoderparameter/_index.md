---
title: EncoderParameter
second_title: Referencia de API de Aspose.Slides para C++
description: "Sirve como un contenedor utilizado para pasar valores a un codificador de imágenes. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento."
type: docs
weight: 66
url: /es/system.drawing.imaging/encoderparameter/
---
## EncoderParameter clase

Sirve como un contenedor utilizado para pasar valores a un codificador de imágenes. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class EncoderParameter : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
|  [EncoderParameter](./encoderparameter/)() | Construye una nueva instancia de la clase [EncoderParameter](./). |
|  [EncoderParameter](./encoderparameter/)(const [SharedPtr](../../system/sharedptr/)\<[Encoder](../encoder/)\>\&, **uint8_t**, **bool**) | Construye una nueva instancia de la clase [EncoderParameter](./). |
|  [EncoderParameter](./encoderparameter/)(const [SharedPtr](../../system/sharedptr/)\<[Encoder](../encoder/)\>\&, **int16_t**) | Construye una nueva instancia de la clase [EncoderParameter](./). |
|  [EncoderParameter](./encoderparameter/)(const [SharedPtr](../../system/sharedptr/)\<[Encoder](../encoder/)\>\&, **int64_t**) | Construye una nueva instancia de la clase [EncoderParameter](./). |
|  [EncoderParameter](./encoderparameter/)(const [SharedPtr](../../system/sharedptr/)\<[Encoder](../encoder/)\>\&, **int32_t**) | Construye una nueva instancia de la clase [EncoderParameter](./). |
|  [EncoderParameter](./encoderparameter/)(const [SharedPtr](../../system/sharedptr/)\<[Encoder](../encoder/)\>\&, **int32_t**, **int32_t**) | Construye una nueva instancia de la clase [EncoderParameter](./) que representa una fracción. |
|  [EncoderParameter](./encoderparameter/)(const [SharedPtr](../../system/sharedptr/)\<[Encoder](../encoder/)\>\&, **int64_t**, **int64_t**) | Construye una nueva instancia de la clase [EncoderParameter](./) que representa un rango de valores enteros. |
|  [EncoderParameter](./encoderparameter/)(const [SharedPtr](../../system/sharedptr/)\<[Encoder](../encoder/)\>\&, **int32_t**, **int32_t**, **int32_t**, **int32_t**) | Construye una nueva instancia de la clase [EncoderParameter](./) que representa un rango de fracciones. |
|  [EncoderParameter](./encoderparameter/)(const [SharedPtr](../../system/sharedptr/)\<[Encoder](../encoder/)\>\&, const [String](../../system/string/)\&) | Construye una nueva instancia de la clase [EncoderParameter](./). |
|  [EncoderParameter](./encoderparameter/)(const [SharedPtr](../../system/sharedptr/)\<[Encoder](../encoder/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **bool**) | Construye una nueva instancia de la clase [EncoderParameter](./) que representa una matriz de valores. |
|  [EncoderParameter](./encoderparameter/)(const [SharedPtr](../../system/sharedptr/)\<[Encoder](../encoder/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<**int16_t**\>\&) | Construye una nueva instancia de la clase [EncoderParameter](./) que representa una matriz de valores. |
|  [EncoderParameter](./encoderparameter/)(const [SharedPtr](../../system/sharedptr/)\<[Encoder](../encoder/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<**int64_t**\>\&) | Construye una nueva instancia de la clase [EncoderParameter](./) que representa una matriz de valores. |
|  [EncoderParameter](./encoderparameter/)(const [SharedPtr](../../system/sharedptr/)\<[Encoder](../encoder/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<**int32_t**\>\&, const [ArrayPtr](../../system/arrayptr/)\<**int32_t**\>\&) | Construye una nueva instancia de la clase [EncoderParameter](./) que representa una matriz de fracciones. |
|  [EncoderParameter](./encoderparameter/)(const [SharedPtr](../../system/sharedptr/)\<[Encoder](../encoder/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<**int64_t**\>\&, const [ArrayPtr](../../system/arrayptr/)\<**int64_t**\>\&) | Construye una nueva instancia de la clase [EncoderParameter](./) que representa una matriz de rangos de enteros. |
|  [EncoderParameter](./encoderparameter/)(const [SharedPtr](../../system/sharedptr/)\<[Encoder](../encoder/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<**int32_t**\>\&, const [ArrayPtr](../../system/arrayptr/)\<**int32_t**\>\&, const [ArrayPtr](../../system/arrayptr/)\<**int32_t**\>\&, const [ArrayPtr](../../system/arrayptr/)\<**int32_t**\>\&) | Construye una nueva instancia de la clase [EncoderParameter](./) que representa una matriz de rangos de fracciones. |
|  [EncoderParameter](./encoderparameter/)(const [SharedPtr](../../system/sharedptr/)\<[Encoder](../encoder/)\>\&, int, [EncoderParameterValueType](../encoderparametervaluetype/), void *) | Construye una nueva instancia de la clase [EncoderParameter](./) que representa el número especificado de valores del tipo especificado que se leen del buffer especificado. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica de C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor al estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque, según IEC 60559:1989, NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque, según IEC 60559:1989, NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para uso interno. |
| [EncoderPtr](../encoderptr/) [get_Encoder](./get_encoder/)() const | Devuelve el objeto [Encoder](../encoder/) asociado al objeto [EncoderParameter](./) actual. |
| int [get_NumberOfValues](./get_numberofvalues/)() const | Devuelve el número de valores representados por el objeto actual. |
| [EncoderParameterValueType](../encoderparametervaluetype/) [get_Type](./get_type/)() const | Devuelve el tipo de los valores representados por el objeto actual. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo del método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite hashing de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Análogo de la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Análogo del operador 'is' de C#. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la sentencia C# lock(). Llamar directamente o usar el objeto centinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo del método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. No copia nada, en realidad, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. No copia nada, en realidad, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| void [set_Encoder](./set_encoder/)(const [EncoderPtr](../encoderptr/)\&) | Asocia el objeto [Encoder](../encoder/) especificado con el objeto [EncoderParameter](./) actual. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como un puntero débil (en lugar de compartido). Permite cambiar los punteros en contenedores a modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo del método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la sentencia C# lock(). Llamar directamente o usar el objeto centinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
|  [~EncoderParameter](./~encoderparameter/)() | Destructor. |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |
## Ver también

* Clase [Object](../../system/object/)
* Espacio de nombres [System::Drawing::Imaging](../)
* Biblioteca [Aspose.Slides](../../)